I/O Redirection Tasks

 0-Print text to stdout:
   echo Hello, World
 1-script that displays confused smiley:
   echo "\"(Ôo)'"
 2-Display contents of '/etc/passwd':cat '/etc/passwd'
 3-Display contents of '/etc/passwd' & '/etc/host':
   cat '/etc/passwd' 'etc/hosts'
 4-Last 10 lines of '/etc/passwd':
   tail -10 /etc/passwd
 5-Last 10 lines of '/etc/passwd'2-Display contents of '/etc/passwd':
   head -10 /etc/passwd
 6-Display 3rd line of iacta
   head -n 3 ./iacta | tail -n 1
 7-Create file containing 'Best School'

 8-Write outout of ls -la into ls_cwd_content
   ls -la > ls_cwd_content
 9-Duplicate last line of 'iacta
   tail -n 1./iacta >> ./iacta
10-find . -name"*.js" -type f -delete
11-sort | uniq -u
12-grep root /etc/passwd
13-grep -c 'bin' /etc/passwd
14-grep -A 3 root /etc/passwd
15-grep -v 'bin' /etc/passwd
16-grep -h '^[a-zA-Z]' /etc/sshd__config
17-tr Ac Ze
18-tr-d'cC'
19-cut -d ":" -f1,6 /etc/passwd |sort

