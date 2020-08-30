# Linux-Shell-Lite
I build my own simplistic Unix Shell by using C language. Linux Shell Lite is a simple implementation of a shell in C. It demonstrates the basics of how a shell works. That is: read, parse, fork, exec, and wait. Since its purpose is demonstration (not feature completeness or even fitness for casual use), it has many limitations, including:

Commands must be on a single line.
Arguments must be separated by whitespace.
No quoting arguments or escaping whitespace.
Only builtins are: echo, pwd, cd, jobs, quit, kjob, killallbg, fg, pinfo.
