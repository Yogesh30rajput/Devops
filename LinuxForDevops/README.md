Linux practice for Devops.

Commands   meaning

date     = today's date and time display
top      = cpu used shows details of every process. like pid, mode of process.
free/ free -h = ram used

ls       = list
ls -l/la = details of current directory (d__ = d stands for directory and it's in a color font)
mkdir    = (make a directory) creation of file or folder through terminal
touch    = create a file
pwd      = it shows working directory
cd       = (change directory)
cd ..    = one step back from the current working directory
clear    = clear the terminal
rm filename = remove/delete a file
rm -r directory name = remove/delete directory recursively(-r)
rmdir    = remove/delete a directory
cat filename = check the content of file
echo "hello" = print hello message on terminal display
echo "hello friends" > filename = send the message into the mention file
echo "Hello newfile" > newfile.txt = it creates automatically file if file is not present
head filename  =  print top lines from the file
tail filename  =  print bottom lines from the file
tail -f filename  = it used to check logs in the file, like monitoring new lines
less/more filename = display information in paginated form
cp sourcename destination directory (cp demofile.txt Devops/) = copy file from folder to another directory
cp Linux/demofile.txt Clouds/  = copy file from one directory to another directory from root directory
cp -r sourceDirectory DestinationDirectory = copy complete directory to another directory.
mv sourcefile ../destination directory/ = move file to different directory
mv sourceName/ newName  =  rename/change name of the source
wc fileName  = display the details of file.. like lines, words and bytes

SoftLink & HardLink
ln -s path of file shortcutname = make a softlink shortcut of a file (ln link, -s softlink) 
                    [softlink deleted after     main file deleted]
Ex:- (ln -s /workspaces/Devops/LinuxForDevops/Demo/demofile.txt soft.tx)

ln  path of file shortcutname = make a hardlink shortcut of a file (ln link) 
                    [hardlink not deleted after main file deleted]
Ex:- (ln /workspaces/Devops/LinuxForDevops/Demo/demofile.txt soft.tx)
