# onelines

- Rename files in the current directory with a sequential set of numbers
```
$ ls -v | cat -n | while read n f; do mv -n "$f" "$n.ext"; done 
```
