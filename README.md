# Office 365 x64 Upgrade

This xml can be used to install the x64 version instead of the x32 version of Microsoft Office 365. For some reason, the official setup still installs the x32 version on x64 systems by default.

- Get the newest Office 365 version: https://www.microsoft.com/microsoft-365/business/

Then run the following command:

- .\OfficeSetup.exe /configure GoTo64.xml

This xml doesn't change anything dramatic about the installation, it's simply a configuration that will make the installer use the x64 version.
