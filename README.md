# shell-data-processing
#### *Some useful powershell command*
```powershell
cd \\ navigation
rm \\deleting folders
ni \\ creating new items
```

### Bash cheatshheet
- *Curl to a file*
  ``` bash
  curl "Url" -o file.txt
  ```
- *pipe the output sort* 
```bash
tr ' ' '\12'filetoREad.txt | sort
```
- *Redirecting output to result*
```bash
tr ' ' '\12' <file.txt | sort | uniq -c | sort -nr > result.txt
```
### Text files
- Input file .[data.txt](https://github.com/Rajeevbro/shell-data-processing/blob/main/data.txt)
- Result file .[result.txt](https://github.com/Rajeevbro/shell-data-processing/blob/main/result.txt)


    