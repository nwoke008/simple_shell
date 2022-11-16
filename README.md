# simple_shell
A BASIC LINUX INTERPRETER
Compilation and Usage
1. Compilation
First clone the repository.
git clone https://<YOUR_PAT>@github.com/lakelexy/simple_shell.git

After cloning the repository, change your current working directory to the just cloned directory and compile the source files using the following commands.
(vagrant@ubuntu-focal)-[~]
-$ cd simple_shell

(vagrant@ubuntu-focal)-[~/simple_shell]
-$ gcc *.c -o hsh

(vagrant@ubuntu-focal)-[~/simple_shell]
-$
2. Usage
To run simply type ./hsh
(vagrant@ubuntu-focal)-[~/simple_shell]
-$ ./hsh
$
To exit just type exit or hit 'Ctrl+D'.
Unsuported features
The following features have not yet been implemented
Shell I/O Redirection
Piping
and some other features.
For Contributors
To push back to the repo do the following
(vagrant@ubuntu-focal)-[~/simple_shell]
-$ git push -u origin master
