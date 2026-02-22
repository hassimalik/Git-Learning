## So we are starting learning Git 


## Day 1

``` git init ``` <br>
This Command creates an empty git folder that is hide by default and contains all git history of your code.

```mkdir "something"```<br>
This command creates a folder in the directory where u are

```git status```<br>
This command shows all the known files to git and branch and some other info

```echo "text">[file name + extension]```<br>
This command will enter and save a text u will type to a new file the name of which u saved and defined.

```git add .``` for all folder files and ```git add "filename" + "filename"``` <br>
If u want to stage one files or multiples this command is used 

```git commit -m "message"```<br>
This command is use to commit with a message

```git log``` or ```git log --oneline``` <br>
This command will show u all the commit history of your repo.<br>
commit e5b7048c24cb1f402526ed4adc11f76bf89a9a45<br>
That long weird code?<br>
That is your Commit ID (SHA).<br>
It is:<br>
Unique<br>
Permanent<br>
Like a fingerprint<br>
No two commits in the world share it<br>
You can use this ID later to:<br>
Go back in time<br>
Compare changes<br>
Reset history<br>
Cherry-pick<br>
Git is basically building a blockchain for your code 😄<br>


## Day 2

```git restore <filename>``` <br>
This command is used to restore last changes to a file if they are done by mistake.

```git revert <commitid>``` <br>
This command is used to restore  last commit that was done to that repo and to esc vim type ```:qa``` then press  ```Enter``` <br>

