# Linux Commands 

## File Commands

- `ls` – Directory listing  
- `ls -al` – Formatted listing with hidden files  
- `cd dir` – Change directory to `dir`  
- `cd` – Change to home directory  
- `pwd` – Show current directory  
- `mkdir dir` – Create a directory `dir`  
- `rm file` – Delete file  
- `rm -r dir` – Delete directory `dir`  
- `rm -f file` – Force remove file  
- `rm -rf dir` – Force remove directory `dir`  
- `cp file1 file2` – Copy `file1` to `file2`  
- `cp -r dir1 dir2` – Copy `dir1` to `dir2`; create `dir2` if it doesn't exist  
- `mv file1 file2` – Rename or move `file1` to `file2`; if `file2` is a directory, moves `file1` into `file2`  
- `ln -s file link` – Create symbolic link `link` to `file`  
- `touch file` – Create or update `file`  
- `cat > file` – Places standard input into `file`  
- `more file` – Output the contents of `file`  
- `head file` – Output the first 10 lines of `file`  
- `tail file` – Output the last 10 lines of `file`  
- `tail -f file` – Output the contents of `file` as it grows, starting with the last 10 lines  

## Process Management

- `ps` – Display your currently active processes  
- `top` – Display all running processes  
- `kill pid` – Kill process with ID `pid`  
- `killall proc` – Kill all processes named `proc`  
- `bg` – Lists stopped or background jobs; resume a stopped job in the background  
- `fg` – Brings the most recent job to foreground  
- `fg n` – Brings job `n` to the foreground  

## SSH

- `ssh user@host` – Connect to `host` as `user`  
- `ssh -p port user@host` – Connect to `host` on port `port` as `user`  
- `ssh-copy-id user@host` – Add your key to `host` for `user` to enable a keyed or passwordless login  

## Searching

- `grep pattern files` – Search for `pattern` in `files`  
- `grep -r pattern dir` – Search recursively for `pattern` in `dir`  
- `command | grep pattern` – Search for `pattern` in the output of `command`  
- `locate file` – Find all instances of `file`  

## System Info

- `date` – Show the current date and time  
- `cal` – Show this month's calendar  
- `uptime` – Show current uptime  
- `w` – Display who is online  
- `whoami` – Show who you are logged in as  
- `finger user` – Display information about `user`  
- `uname -a` – Show kernel information  
- `cat /proc/cpuinfo` – CPU information  
- `cat /proc/meminfo` – Memory information  
- `man command` – Show the manual for `command`  
- `df` – Show disk usage  
- `du` – Show directory space usage  
- `free` – Show memory and swap usage  
- `whereis app` – Show possible locations of `app`  
- `which app` – Show which `app` will be run by default  

## Shortcuts

- `Ctrl+C` – Halts the current command  
- `Ctrl+Z` – Stops the current command; resume with `fg` in the foreground or `bg` in the background  
- `Ctrl+D` – Log out of current session, similar to `exit`  
- `Ctrl+W` – Erases one word in the current line  
- `Ctrl+U` – Erases the whole line  
- `Ctrl+R` – Type to bring up a recent command  
