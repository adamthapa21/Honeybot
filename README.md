This is a lightweight Windows Port-based honeypot that can listen on all ports from 1-65535 both TCP and UDP (it doesn't appear to work on port 0).

The file HoneyBOT_018.exe is a Windows installer, and runs on most modern versions of Microsoft Windows.

Tested on Windows 7,10,11 and Server 2016,2019,2022.

Once it is installed, the ports it listens on can be seen within the configuration file service.ini which normally exists within the location C:\HoneyBOT

The accompanying file  service.ini  can be downloaded and copied over the existing service.ini as this adds a number of extra ports whilst removing ports that cause a lot of extra noise on a lan such as SSDP, SMB, RPC, etc. These missing ports can of course always be added if required. When overwriting the service.ini it is recommended that you take a backup first. Failing that you could always uninstall and reinstall the application.
