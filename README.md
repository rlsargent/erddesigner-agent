# ERD Designer Agent — downloads

This repository holds the released builds of the **ERD Designer Agent**, the
small program that lets [ERD Designer](https://www.erddesigner.com) read a
schema from, and apply DDL to, a database on your own computer or network.

**What the Agent is, what it can and cannot do, and how to set it up:**
https://www.erddesigner.com/agent

The builds are on the [Releases](../../releases) page, one release per version
of the DDL engine. ERD Designer links you to the build that matches it, so the
simplest way to get the right one is the download button in the application or
on the page above.

| File | For |
|---|---|
| `ddl-apply-macos-arm64` | macOS on Apple silicon |
| `ddl-apply-macos-x64` | macOS on Intel |
| `ddl-apply-win-x64.exe` | Windows |
| `ddl-apply-linux-x64` | Linux |

The Agent is not yet code-signed. On macOS, right-click the file and choose
Open the first time; on Windows, choose More info, then Run anyway.

There is no source code here. Questions: support@erddesigner.com
