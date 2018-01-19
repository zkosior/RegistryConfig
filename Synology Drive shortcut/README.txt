1. Generate new GUID. Can be generated with PowerShell command: [guid]::NewGUID()
2. Replace "newCLSID" with one generated in previous step.
3. Copy Windows SID from registry key [HKEY_USERS]. Will look like: S-1-5-21-XXXXXXXXXX-XXXXXXXXXX-XXXXXXXXXX-1001
4. Replace "WindowsSID" with one copied in previous step.
5. Replace "localUserFolder" with correct folder name.
6. Make sure all paths are valid on the system.
7. Play with name of storage provider (SynologyDrive). Maybe it uses different name, maybe you want different name.