## Lab 01

- Name: Seniya Senanayake
- Email: senanayake.5@wright.edu

## Part 1 - GitHub Profile

1. [AyineS's GitHub Profile](https://github.com/AyineS)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         | command which can be used to learn how specific commands work/behave  |
| Get-Location | pwd    | display the path of your currect location       |
| Get-ChildItem | ls    | list files and/or folders in a directory       |
| mkdir   | mkdir       | create a new directory at the current location or a specific path       |
| Set-Location | cd     | change the current location to a specific directory       |
| New-Item | touch      | create a new file       |
| Move-Item | mv        | move a file or a folder from one location to another      |
| Copy-Item | cp        | copy a file or a folder from one location to another       |
| Remove-Item | rm      | delete one or more items       |
| notepad.exe | vim     | open the notepad       |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [ ] Linux
- [ ] Mac

My Command Line Shell is: Windows Powershell

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: C:\Users\Devika>
2. Create a directory named `DirA`: mkdir DirA
3. Create a directory named `Dir B`: mkdir "Dir B"
4. Go into `DirA`: cd DirA
5. Go into `Dir B` from `DirA`: cd ..\\"Dir B"
6. Return to your user's home directory: cd ~
7. Create a file named `test.txt`: New-Item text.txt
8. Move the file named `test.txt` into `DirA`: Move-Item text.txt DirA
9. Contents of `test.txt`:  
   cd DirA  
   echo "You got this" >> text.txt
```
You got this
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: Copy-Item text.txt copy.txt
11. View the contents of `DirA`: Get-ChildItem
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: Copy-Item "C:\Users\Seniya\DirA\text.txt" "C:\Users\Seniya\Dir B\fodder.txt"
13. Delete / remove both `fodder.txt` AND `Dir B`: Remove-Item "C:\Users\Seniya\Dir B" -Recurse

## Citations

Source used for help with command 13 where **-Recurse** deletes not only the specified directory but also all its subdirectories and files recursively, without prompting for confirmation for each item.   
(https://stackoverflow.com/questions/7909167/how-to-quietly-remove-a-directory-with-content-in-powershell)



