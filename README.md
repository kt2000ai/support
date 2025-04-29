#Outlook File Max size 100GB

Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\PST]
"WarnLargeFileSize"=dword:00017318
"MaxLargeFileSize"=dword:000186a0

++++
reg add "HKCU\Software\Microsoft\Office\16.0\Outlook\PST" /v WarnLargeFileSize /t REG_DWORD /d 94996 /f
reg add "HKCU\Software\Microsoft\Office\16.0\Outlook\PST" /v MaxLargeFileSize /t REG_DWORD /d 100000 /f
