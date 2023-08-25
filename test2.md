  
netsh advfirewall firewall add rule name="Kantech Workstation All Incoming" program="C:\Program Files (x86)\Kantech\Workstation_CE\Bin\EpCEWorkstation.exe" dir=in action=allow protocol=any profile=domain
netsh advfirewall firewall add rule name="Kantech Registration All Incoming" program="C:\Program Files (x86)\Kantech\Workstation_CE\Bin\EpCeConnect.exe" dir=in action=allow protocol=any profile=domain![image](https://github.com/samersultan/test2/assets/2245542/63d62351-bda9-4272-b01c-f34310645a72)
