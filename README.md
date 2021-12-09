# A simple UNIX command interpreter.

![](https://user.oc-static.com/files/160001_161000/160278.png)

# Requirements
#### General
- Allowed editors: vi, vim, emacs
- All Our files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
- All Our files should end with a new line
- A README.md file, at the root of the folder of the project is mandatory
- Our code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- Our shell should not have any memory leaks
No more than 5 functions per file
- All Our header files should be include guarded
Use system calls only when you need to 

# List of allowed functions and system calls
access (man 2 access)
chdir (man 2 chdir)
close (man 2 close)
closedir (man 3 closedir)
execve (man 2 execve)
exit (man 3 exit)
_exit (man 2 _exit)
fflush (man 3 fflush)
fork (man 2 fork)
free (man 3 free)
getcwd (man 3 getcwd)
getline (man 3 getline)
getpid (man 2 getpid)
isatty (man 3 isatty)
kill (man 2 kill)
malloc (man 3 malloc)
open (man 2 open)
opendir (man 3 opendir)
perror (man 3 perror)
read (man 2 read)
readdir (man 3 readdir)
signal (man 2 signal)
stat (__xstat) (man 2 stat)
lstat (__lxstat) (man 2 lstat)
fstat (__fxstat) (man 2 fstat)
strtok (man 3 strtok)
wait (man 2 wait)
waitpid (man 2 waitpid)
wait3 (man 2 wait3)
wait4 (man 2 wait4)
write (man 2 write)
# Compilation
### Our shell will be compiled this way:

gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
# This project was made by
Mouhamed Rafed Riahi (rafedriahi.rr@gmail.com)
Mouhamed Amine Houiji(amine.houiji20@gmail.com)
Haythem Abidi(haythem.abidi@icloud.com)
