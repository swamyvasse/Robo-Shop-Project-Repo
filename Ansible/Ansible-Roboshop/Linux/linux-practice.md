linux commands:--
----------------------
pwd --> present working directory 
ls  --> listing files
uname --> kernel
uname -a --> all the details
ls -l --> lengthy formate
touch ---> create file 
mkdir ---> create directory 
cat > filename ---> add text on file
cat filename ---> see the text 
cat >> filename ---> add onemore text 
rm filename ---> remove filename
rmdir (directory name) ---> remove directory 
cp ---> copy command (cp sourcefile destination file)
mv ---> cut command (mv sourcefile destination file)
grep --> to find the text in file
grep (to find word) filename
grep -i ---> gives caseinsensative command
head ---> first 10 lines of the file
head -n 2 filename ---> it gives first 2 lines of the file
tail ----> gives last 10 lines of the file
tail -n 2 filename ---> gives last 2 lines of the file
wget ---> download the file
wget <url> visible the data 
cut ---> it is used to cut the string based on the delimitor
cut -d / -f1
awk ---> 
awk -F / '{print $1F}'
vim editor commands
:/<word-to-find> --> it will search for the word from top
:?<word-to-find> --> it will search for the 
:noh ---> it will no highlight
:q ---> quit the file comeout of the file
:q! ---> it will not write what you entered and quit

ESC Mode
--------------------
u --> undo the changes
yy ---> yank/copy ---> copies the line
p ---> paste it 
dd ---> cut the line 
10p ---> paste for 10times
gg --> it will take you to the top of the file
shift+G ---> it will take you to the bottom of the file

permissions in linux:--
--------------------------
R --> read -- 4
W --> write -- 2
X --> Execute -- 1

User/owner ---> the one who created the file
Group ---> Generally the group belongs to or any group 
Others ---> other than user and group




