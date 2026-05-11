# Task 2 – Linux Commands

## Navigation
```bash
pwd               # print working directory
cd /path/to/dir   # change directory
cd ..             # go up one level
ls                # list files
ls -la            # list with details + hidden files
```

## File Operations
```bash
touch file.txt          # create empty file
cat file.txt            # display file
more file.txt           # view page by page
less file.txt           # scrollable view
head -n 10 file.txt     # first 10 lines
nano file.txt           # edit in nano
mkdir my_folder         # make directory
rm file.txt             # remove file
rmdir my_folder         # remove empty directory
rm -rf my_folder        # force remove directory
cp src dest             # copy
mv src dest             # move / rename
file filename           # show file type
```

## System
```bash
sudo command            # run as superuser
man ls                  # manual for a command
alias ll='ls -la'       # create alias
ps aux                  # list processes
kill <PID>              # kill process
shutdown -h now         # shutdown
reboot                  # restart
chmod 755 file.sh       # change permissions
bash script.sh          # run bash script
sh script.sh            # run shell script
dpkg -l                 # list installed packages
```

## Redirection & Pipes
```bash
echo "hello" > file.txt    # write (overwrite)
echo "world" >> file.txt   # append
ls | grep ".py"            # pipe to grep
```
