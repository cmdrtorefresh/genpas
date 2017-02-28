# Random Password Generator

### tl;dr
a simple random password Generator

### Installation
- Make sure you have Ruby installed. `ruby -v` to check (will tell you the version you're running). If Ruby is not installed, [download Ruby](https://www.ruby-lang.org/en/downloads/)
- Go to the folder you'd like the file to reside. Let's say the path to this folder is "Users/me/Documents/Folder"
- `git clone https://github.com/cmdrtorefresh/genpas.git`
- Edit `~/.bash_profile` for MacOS. Add the following line `export PATH=/Users/me/Documents/Folder/password:$PATH`. Save.

### Usage
- help : `genpas -h`
- `genpas 15 -luns 2` to generate 2 strings with random lowercase, uppercase, numbers and special characters with length 15.
- `genpas -lun` to generate 1 string with random lowercase, uppercase, and numbers with length 10 (default).
