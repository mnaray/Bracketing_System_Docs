# Documentation

## Research

### Sources

### Requirements


| **Req. No.** | **Mandatory/Optional** | **Func./Qual./Margin.** | **Requirement** |
| :----------- | ---------------------- | :---------------------- | --------------- |
|              |                        |                         |                 |

### Tech Stack

- Languages
- Frameworks
- Hosts
- Database

## Plan

### Work Packages


| Nr. | Due Date | Description | Estimated Time (45 min.) |
| --- | -------- | ----------- | ------------------------ |
|     |          |             |                          |

**Total Time Spent (estimate)**

Here is the calculation of how many lessons the project should take to implement. Please note, that a single lesson equals 45 minutes

```
team members: 3
total weeks: 7
lessons per week: 5
lessons per member: 7 * 5 = 35
total lessons: 35 * 3 = 105
```

**The total amount of lessons should be 105** as every one of the 3 members works 5 lessons per week over the course of 7 weeks.

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
