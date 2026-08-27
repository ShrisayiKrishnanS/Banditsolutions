# Banditsolutions

bandit1 :
(used cat readme)
6y2kwnwK6grgvwvpvLaa2T1cpFEKOhNR

bandit2 :
(filename= "-" so to refer to it we use "./" before it.)
PK8fYLZg2hnHSz83plBL1iEPKdD3QToB

bandit3:
(filename has spaces so include in quotes"./<filename with space>")
7ZZ2LFrykP2zEyvBl4m3clcL7tGYJPME

bandit4:
(ls -a for ALL files in there including hidden ones, also cat <filename including the dots>)
xzTXq1rDJQVVAzdv5cHq1TQytTWufAMq

bandit5:
(file command allows you to see the type of file and human readable format is ASCII: command is file <directory>/* )
6C7h9GD8M6ai5nr7wo1RonrzFjj9yIrG

bandit6:
(using find syntax: -type <types like f> and -size 1033c *c stands for bytes, k also exists*)
pXa26xhMWaC2SvDotA4r9EgZkulOeSBW

bandit7:
(had to cd .. all the way out then run the find with size, type, group and user)
./var/lib/dpkg/info/bandit7.password is the file 
Bmnnvf82KzQlfxgAI2d1zYbr1u9pr3E3

bandit8:
(using command grep <type of search> pattern <filename> used -w with word)
VR1ljMayciFxbnUokuQmJFw6QC9VKtub

bandit9:
(sort has to be done b4 uniq and since we cant save as a file we do it simultanouesly, cant use grep for finding unique)
EjmOSvuAu7sGAHqHVcBDPirRe9T03kxl	

bandit10:
(this needs strings <filename> to get all the strings then simultaneously use grep "===" to filter starting with ===)
B0s2khmbT9u0geKuOoVGW3JZKhndE3BG

bandit11:
(using  strings data.txt| base64 -d take the string and use the base64 command to translate)
pYfOY6HwUsDj5rL9UvyhU7MCmv8vN5Ro

bandit12:
(using rot13 and tr [set1] [set2] )
	

bandit13:
(multiple times of tar -xf and gzip -d and bzip2 -d finally found my answer at data8.bin)(magic numbers:BZ (= ‘425a’),gzip compressed files the header is \x1F\x8B\x08)
qQYQiHOBPR8zR61qxYqX45quvihF2uzk

bandit14:
(using the bandit 13 password and scp <port> <address in the server>:<file> then using ssh -i <filename> bandit14@<servername> <port> )
no password just private ssh key
next submit this aaWecNkG4FhxJQxz07uiwzVP6bJiYS65 and get password for next
password: pbLYuZtTg4MgaqfJx8jbA9gKKGqM68A7

bandit15:
(using openssl s_client -connect localhost 30001 to connect to server and send the current password to get a new one back)
kS0Hf0u5HiXFwKMKFqXvPdOTNGGa0X8V

bandit16:
(using the previous password and openssl client connection i also had to use -ign_eof to give the password then we get a new private key which i saved to the precvious sshkey file we had in the prev level)
only private key no password

bandit17:
(used the previously saved private key to get into bandit 17 then used diff command with new placed second)
OQxXZjELndr90zuhOTDYBEomI0SZITXI

bandit18:
(using direct commands in the ssh line itself)
KpsOfPkcP7i1FlIExk2QEjyt6dw8dxZI

bandit19:
(using ./bandit20-do  to execute as another user)
4pIjcunZ0fK2vmp3IwfG8Vf7VhxD6pOA

bandit20:
(used netcat*using -l for listening and -p and setting on same port* using echo to send message and specifying the port 1234)
bW9kBv5WC3P4yoDyf12LSdGuNz5ka6hY

bandit21:
(use of cat in a file to see what a program does in the background and finding the bash file)
RYVux2rHEm9tiXHmLFzuR7Vhx6AZQMEz

bandit22:
(the code i got did not lead me to the tmp file for some reason)
gKXDTAXnIz3OBxiPjRZ2uqutUlPZrBsw

bandit23:
