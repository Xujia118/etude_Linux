# Etude_Linux

cd (go root)
cd- (go previous)

ls -a (hidden files)
ls -A (hidden files without . and ..)
ls -R (all the files in the sub-directories)
ls -al (all files and directories and detailed info)

cat (list content of a file)
cat > filename (create a a new file) 
cat filename1 filename2 > filename2 (join to files and put content in a third file)
cat -n (give number to output lines)
cat -s (suppress repeated outlines that are empty)

- To save file, ctrl + D


head -n 5 /etc/password (display the first 5 lines of a text file)
tail (would do the opposite)

pr -m (print two files side by side)
pr -l (set page length)

touch filename (create a new file with date and time)

echo text > filename (write content in a file and create the file)

rm -r foldername (delete all file and directories)

mv (mv or rename)

grep -i word /ect/password (find a word in a file. -i to ignore case)

less /etc/password (read a page with pagination)

diff -q filename1 filename2 (find differences of two texts, issue a message to express it with -q)

sudo apt update (to check updates)
sudo apt upgrade (to update)

vim:
:q! to quit without saving
:wq to save and quit
