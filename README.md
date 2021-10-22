laba 1
========================
#root@f798856ead4d:/# pwd/

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

1)root@f798856ead4d:~# mkdir classics

2)root@f798856ead4d:~#  rmdir classics

3)root@f798856ead4d:~# uname -a

Linux f798856ead4d 4.19.0-16-amd64 #1 SMP Debian 4.19.181-1 (2021-03-19) x86_64 x86_64 x86_64 GNU/Linux

4)root@f798856ead4d:~# uname -s

Linux

5)root@f798856ead4d:~# uname -r

4.19.0-16-amd64

6)root@f798856ead4d:~# date

Fri Oct 15 15:48:04 MSK 2021

7)root@f798856ead4d:~# cal 

bash: cal: command not found

8)

9)/clean 

10)root@f798856ead4d:~# pwd

/root

11)root@f798856ead4d:~# cd ~

root@f798856ead4d:~# 

12)root@f798856ead4d:~# ls

classics  dir1  dir2  dir3  file1  file2  file3  t.sh  test  test1  test2

root@f798856ead4d:~# ls -R

.:

classics  dir1  dir2  dir3  file1  file2  file3  t.sh  test  test1  test2

./classics:

./dir1:

f1

./dir2:

./dir3:

./test:

subtest

./test/subtest:

./test1:

subtest

./test1/subtest:

./test2:

subtest

./test2/subtest:

13)root@f798856ead4d:~# ls -a

.  ..  .bash_history  .bashrc  .local  .profile  classics  dir1  dir2  dir3  file1  file2  file3  t.sh  test  test1  test2

14)root@f798856ead4d:~# ls -R

.:

classics  dir1  dir2  dir3  file1  file2  file3  t.sh  test  test1  test2

./classics:

./dir1:

f1

./dir2:

./dir3:

./test:

subtest

./test/subtest:

./test1:

subtest

./test1/subtest:

./test2:

subtest

./test2/subtest:

15)root@f798856ead4d:~# type -F

bash: type: -F: invalid option

type: usage: type [-afptP] name [name ...]

16 и 17)root@f798856ead4d:~# mkdir etc

root@f798856ead4d:~# cd etc

root@f798856ead4d:~/etc# mkdir X11

root@f798856ead4d:~/etc# cd X11

root@f798856ead4d:~/etc/X11# 

18)root@f798856ead4d:~/etc/X11# cd ~

root@f798856ead4d:~# 

19)root@f798856ead4d:~# cd etc

root@f798856ead4d:~/etc# 

20)root@f798856ead4d:~/etc# ls group

ls: cannot access 'group': No such file or directory

root@f798856ead4d:~/etc# mkdir group

root@f798856ead4d:~/etc# ls group

root@f798856ead4d:~/etc# 

21)21)root@f798856ead4d:~/classics/etc# cat group passwd Hello Good morning

22)root@f798856ead4d:~/classics/etc# cat group | head -n 5 Hello

23)root@f798856ead4d:~/classics/etc# cat passwd | tail -n 3 Good morning

24)root@f798856ead4d:~/classics/etc# wc -l passwd
1 passwd

25)root@f798856ead4d:~# cd student

26)root@f798856ead4d:/student# touch file1 file2 file3 root@f798856ead4d:/student# ls file1 file2 file3

27)root@f798856ead4d:/student# mkdir dir1 dir2 dir3 root@f798856ead4d:/student# ls dir1 dir2 dir3 file1 file2 file3

28)root@f798856ead4d:~/student# cp file1 dir1


