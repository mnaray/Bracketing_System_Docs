# Documentation

## Research

### Sources

- [Firebase Documentation](https://firebase.google.com/docs)
- [React Router Documentaiton](https://reactrouter.com/en/main)
- [Firestore Indexes](https://stackoverflow.com/questions/53790175/why-does-this-firestore-query-require-an-index)
- [Passing Parameters on Redirect](https://stackoverflow.com/questions/72017435/how-can-i-pass-parameters-to-route-with-navigate-function-in-react)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs/installation)

### Requirements


| **Req. No.** | **Mandatory/Optional** | **Func./Qual./Margin.** | **Requirement**                                                                            |
| ------------ | ---------------------- | ----------------------- | ------------------------------------------------------------------------------------------ |
| 1            | Mandatory              | Func.                   | Login with Email and Password                                                              |
| 2            | Mandatory              | Func.                   | Registration with Email and Password                                                       |
| 3            | Mandatory              | Qual.                   | Login with OAuth (any Provider)                                                            |
| 4            | Mandatory              | Qual.                   | Registration with OAuth (any Provider)                                                     |
| 5            | Mandatory              | Func.                   | Creation of new brackets                                                                   |
| 6            | Mandatory              | Func.                   | Deletion of old brackets                                                                   |
| 7            | Mandatory              | Func.                   | Overview of all brackets that belong to the logged in user                                 |
| 8            | Optional               | Func.                   | Ability to add competitors to a bracket before start                                       |
| 9            | Optional               | Func.                   | Ability to remove competitors from a bracket before start                                  |
| 10           | Optional               | Qual.                   | Handling of uneven competitor amounts (all matches must have two competitors as opponents) |
| 11           | Mandatory              | Func.                   | Overview of all the brackets in their current state                                        |
| 12           | Optional               | Func.                   | Clicking on the winner of a match makes them advance to the next one                       |
| 13           | Optional               | Qual.                   | Correction of unstarted matches (editing outcome of parent matches)                        |
| 14           | Mandatory              | Margin.                 | Use of Firestore DB instead of Realtime DB                                                 |
| 15           | Mandatory              | Margin.                 | Use of Typescript to ensure type safety                                                    |

### Tech Stack

* Languages
    * [Typescript](https://www.typescriptlang.org/)
* Frameworks/Libraries
    * [React](https://react.dev/)
* Hosts
    * [Netlify](https://www.netlify.com/)
    * [Firebase](https://firebase.google.com/)
* Database/Backend
    * [Firestore](https://firebase.google.com/docs/firestore)

## Plan

### Work Packages


| Nr. | Due Date   | Description                                                                         | Estimated Time (in 45 min.) |
| --- | ---------- | ----------------------------------------------------------------------------------- | --------------------------- |
| 1   | 14.3.2024  | Set up repositories and GH-project                                                  | 2                           |
| 2   | 21.3.2024  | Create requirements                                                                 | 2                           |
| 3   | 21.3.2024  | Set up React project                                                                | 1                           |
| 4   | 21.3.2024  | Set up Tailwinds                                                                    | 1                           |
| 5   | 28.3.2024  | Create work packages                                                                | 3                           |
| 6   | 21.3.2024  | Configure Firebase                                                                  | 2                           |
| 7   | 21.3.2024  | Create DB schema for Firestore                                                      | 3                           |
| 8   | 28.03.2024 | Overall research                                                                    | 5                           |
| 9   | 28.03.2024 | Create UI wireframe                                                                 | 3                           |
| 10  | 28.03.2024 | Implement internal DB service for client                                            | 4                           |
| 11  | 28.03.2024 | Plan state management                                                               | 2                           |
| 12  | 25.4.2024  | Write test cases (including test env.)                                              | 3                           |
| 13  | 28.03.2024 | Implement local persistence where needed                                            | 3                           |
| 14  | 4.4.2024   | Implement login/registration pages                                                  | 2                           |
| 15  | 25.4.2024  | Implement bracket overview page (with test data)                                    | 3                           |
| 16  | 25.4.2024  | Implement bracket representation                                                    | 5                           |
| 17  | 25.4.2024  | Implement competitor management (including the clicking of winners and corrections) | 5                           |
| 18  | 25.4.2024  | Implement handling of uneven competitor amounts                                     | 5                           |
| 19  | 2.5.2024   | Test the project and document results                                               | 2                           |
| 20  | 2.5.2024   | Evaluate the project                                                                | 1                           |
| 21  | 2.5.2024   | Portfolio entry                                                                     | 3                           |

**Total Time Spent (estimate)**

Here is the calculation of how many lessons the project should take to implement. Please note, that a single lesson equals 45 minutes

```
team members: 2
total weeks: 6
lessons per week: 5
lessons per member: 6 * 5 = 35
total lessons: 30 * 2 = 60
```

**The total amount of lessons should be 60** as every one of the 2 members works 5 lessons per week over the course of 6 weeks.

### Test Cases


| Testcase<br />Nr. | Req.<br />Nr. | Requirements | Testenvironment | Input/Output | Predicted Output |
| ----------------- | ------------- | ------------ | --------------- | ------------ | :--------------- |
|                   |               |              |                 |              |                  |

#### Testenvironment

**Microsoft Visual Studio Enterprise (VS)**

- Microsoft Visual Studio Enterprise 2022
- Version: 17.9.1
- VisualStudio.17.Release/17.9.1+34616.47
- Microsoft .NET Framework: Version 4.8.09032
- Installed Version: Enterprise
- C# Tools: 4.9.0-3.24081.11+989117396f26e5453ff157df610d22ce45b6b0a9
- Microsoft JVM Debugger: 1.0
- NuGet Package Manager: 6.9.1
- Visual Studio IntelliCode: 2.2

  **Visual Studio Code (VSC)**
- Version: 1.85.2 (user setup)
- Commit: 8b3775030ed1a69b13e4f4c628c612102e30a681
- Chromium: 114.0.5735.289
- Electron: 25.9.7
- ElectronBuildId: 26354273
- Node.js: 18.15.0
- V8: 11.4.183.29-electron.0
- OS: Windows_NT x64 10.0.22621
- Sandboxed: Yes

  **Microsoft SQL Server Management Studio 18**
- Version: 18.11.1

  **Chrome (for PDFs und Documentation)**
- Version 122.0.6261.58 (Official Build) (64-bit)

  **Visual Paradigm**
- Version: 17.1

### DB schema for Firestore

Due to Firestore being a No-SQL database, we had to come up with a schema that can still represent relation to some extent. This was of great importance because to the bracket structure, which essentialy is a binary tree.

This is the schema we will be using for the brackets:

* root/
    * etc.../
    * brackets/
        * bracketId/
            * title: string
            * createdAt: int
            * editedAt: int
            * ownerName: string *(username)*
            * started: bool
            * startedAt: int
            * rounds: **IRound[]**


**Interfaces:**

* IRound:
    * roundNumber: int
    * matches: **IMatch[]**
* IMatch:
    * id: string
    * competitor1: **ICompetitor**
    * competitor2: **ICompetitor**
    * winner: **ICompetitor** | undefined
    * started: bool
    * nextMatch: string | undefined
* ICompetitor:
    * name: string *(must be unique in the bracket)*
    * previousMatchId: string | undefined

### Simple UI wireframe

![](assets/20240328_104117_Bracketingsystems.drawio.png)

## Decide

### Database Type and Engine

At the very beginning of the project we were thinking about using a realtime NoSQL database such as [Firebase](https://firebase.google.com/docs/database) to avoid having to deal with failed transactions. That would have worked by attaching observers to certain nodes (JSON elements) in the database and subscribing them to update events.

However, we decided to go with a relational database in the end, so that we can avoid redundancy. Our final decision on this subject came down to [Microsoft SQL Server 2022 Express](https://www.microsoft.com/de-de/download/details.aspx?id=104781). We chose that engine due to its range of feature and our experience with it.

### Database Hosting

### Documentation Site

In terms of hosting the documentation there were interesting discussions as well. They were mostly about whether we should stay with [Docusaurus](https://docusaurus.io/) (a technology we all know from previous projects) or if we should try out something new as an alternative. This is due to Docusaurus being a struggle to fully integrate and automate with GitHub-Pages.

As a replacement we found several other tools. Most of them were sadly even less convenient or just overly complicated compared to docusaurus. One of the top candidates was [Sphinx](https://www.sphinx-doc.org/en/master/), but it uses a very odd syntax over the regular Markdown everyone in the team is used to.

When looking for a potential host for it we found [Read the Docs](https://about.readthedocs.com/?ref=readthedocs.com). It can even fully automate previews and deployments from a GitHub repository by simply setting up a Webhook in it. This feature spared us the creation of a dedicated workflow and the debugging of it, which took a good while with Docusaurus originally. So this is the host we went with for the documentation, instead of GitHub-Pages.

While skimming through the documentation of the new host, we found out that it also works with a Markdown based framework called [MkDocs](https://www.mkdocs.org/). After reading up a bit on MkDoc's customization possibilities we found the [Material Theme for MkDocs by Squidfunk](https://squidfunk.github.io/mkdocs-material/) to be suitable for our needs. It provides more or less the same features as Docusaurus, just without the complications we had. As so, our final decision regarding the documentation side of things was to use MkDocs with the Material Theme and host it on Read the Docs.

### Linting and Linters

Yet to be determined

## Realise

### Achitecture

### Execution Table

### Execution Table

This is the table that shows the actual time it took to fully implement the project.


| Nr. | Due Date | Description | Actual Time | Estimated Time (45 min.) |
| --- | -------- | ----------- | ----------- | ------------------------ |
|     |          |             |             |                          |

## Control

### Test Protocol


| Test-Nr. | Note | Result | Date | Signature |
| -------- | ---- | ------ | ---- | --------- |
|          |      |        |      |           |

### Conclusion

## Evaluate
