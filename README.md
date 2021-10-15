# root@f798856ead4d:/# pwd/

  bash: pwd/: No such file or directory
  
  root@f798856ead4d:/# ~ $ pwd
  
  bash: /root: Is a directory
  
  root@f798856ead4d:/# ~ $ cd/
  
bash: /root: Is a directory

root@f798856ead4d:/# $ ls

bash: $: command not found

root@f798856ead4d:/# / $ ls

bash: /: Is a directory

root@f798856ead4d:/# / $ ls -F --color

bash: /: Is a directory

root@f798856ead4d:/# pwd 

/

root@f798856ead4d:/# cd/

bash: cd/: No such file or directory

root@f798856ead4d:/# cd /

root@f798856ead4d:/# ls

bin  boot  dev  dir1  dir2  dir3  etc  file.1  file.2  file.3  home  lib  lib32  lib64  libx32  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var  vegetables

root@f798856ead4d:/# ls -F --color

bin@   dev/   dir2/  etc/    file.2  home/  lib32@  libx32@  mnt/  proc/  run/   srv/  tmp/  var/
boot/  dir1/  dir3/  file.1  file.3  lib@   lib64@  media/   opt/  root/  sbin@  sys/  usr/  vegetables

root@f798856ead4d:/# cd

root@f798856ead4d:~# mkdir test

mkdir: cannot create directory 'test': File exists

root@f798856ead4d:~# ls

dir1  dir2  dir3  file1  file2  file3  t.sh  test  test1

root@f798856ead4d:~# mkdir test2

root@f798856ead4d:~# ls -F --color

dir1/  dir2/  dir3/  file1  file2  file3  t.sh  test/  test1/  test2/

root@f798856ead4d:~# ls -F --color test/

subtest/

root@f798856ead4d:~# ls -F --color test2/

root@f798856ead4d:~# mkdir tesr2/subtest

mkdir: cannot create directory 'tesr2/subtest': No such file or directory

root@f798856ead4d:~# mkdir test2/subtest

root@f798856ead4d:~# ls test2

subtest

root@f798856ead4d:~# mkdir classics

root@f798856ead4d:~#  rmdir classics

root@f798856ead4d:~# uname -a

Linux f798856ead4d 4.19.0-16-amd64 #1 SMP Debian 4.19.181-1 (2021-03-19) x86_64 x86_64 x86_64 GNU/Linux

root@f798856ead4d:~# uname -s

Linux

root@f798856ead4d:~# uname -r

4.19.0-16-amd64

root@f798856ead4d:~# date

Fri Oct 15 15:48:04 MSK 2021

root@f798856ead4d:~# cal 

bash: cal: command not found

root@f798856ead4d:~# cal

bash: cal: command not found

root@f798856ead4d:~# ^C

root@f798856ead4d:~# 
