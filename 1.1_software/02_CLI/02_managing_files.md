
## ⭐ Activity 2: Creating and Managing Files

### 🎯 Goal  
Practise working with files and folders.

### 📝 Tasks


*Push everything to your GitHub assigment. Make as many commits as needed.*

`images/CLI_step7.png`
![A VS Code terminal shows file-management commands run in the practice directory: cd practice, touch file1.txt, touch file2.txt, mv file1.txt notes.txt, cp noes.txt notes_backup.txt, cp notes.txt notes_backup.txt, and rm file2.txt. The first copy command returns cp: cannot stat noes.txt: No such file or directory; the corrected copy command succeeds. The dark terminal displays the commands and output in sequence, with a neutral instructional tone.](screenshots/ss_7.png)

1. Create a new folder called `practice` in your CLI directory:
   ```bash
   mkdir practice
   ```
2. Move into it:
   ```bash
   cd practice
   ```
3. Create two files:
   ```bash
   touch file1.txt file2.txt
   ```
4. Rename `file1.txt` to `notes.txt`:
   ```bash
   mv file1.txt notes.txt
   ```
5. Copy `notes.txt` to a new file called `notes_backup.txt`:
   ```bash
   cp notes.txt notes_backup.txt
   ```
6. Delete `file2.txt`:
   ```bash
   rm file2.txt
   ```
