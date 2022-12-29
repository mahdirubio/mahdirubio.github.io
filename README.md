# alfayda

> Welcome to alfayda.

* command to change extension of files
>$ find . -name '*.html' -exec sh -c 'mv "$0" "${0%.html}.md"' {} \;
* command to concat all files into one file 
>$ cat *.md >> All.md