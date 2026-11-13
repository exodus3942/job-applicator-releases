# Job Applicator releases

This repository holds the Windows installers for Job Applicator and nothing else. The app's source code is kept in a private repository.

The app checks this page for updates on start and once a day. When a newer version is here, it offers to install it. Nothing installs until you click Install.

## Install by hand

1. Open the latest release on the right of this page (Releases).
2. Download `JobApplicator-Setup-<version>.exe`.
3. Optional check: download the matching `.sha256` file. In PowerShell run `Get-FileHash .\JobApplicator-Setup-<version>.exe` and compare the value with the file.
4. Run the installer. The installer is not signed yet, so Windows SmartScreen may warn: click More info, then Run anyway.

Installing over an older version keeps your data (profile, documents, applications). Your data stays on your computer in `%APPDATA%\JobApplicator`.
