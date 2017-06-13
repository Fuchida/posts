title: Save terminal output to a file
date: June, 2017

All output will be sent to terminal
and file.

```
bash-4.2$ command | tee output.txt
```

Append to existing file

```
bash-4.2$ command | tee -a output.txt
```

[Source: Stackoverflow](https://askubuntu.com/a/731237)
