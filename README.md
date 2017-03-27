# Random Password Generator

### tl;dr
a simple random password Generator

### Installation
- Make sure you have Ruby installed. `ruby -v` to check (will tell you the version you're running). If Ruby is not installed, [download Ruby](https://www.ruby-lang.org/en/downloads/)
- Go to the folder you'd like the file to reside. Let's say the path to this folder is "Users/me/Documents/Folder"
- `git clone https://github.com/cmdrtorefresh/genpas.git`
- Edit `~/.bash_profile` for MacOS. Add the following line `export PATH=/Users/me/Documents/Folder:$PATH`. (Again, replace '/Users/me/Documents/Folder' with the directory of your local git repo. Save.

### Usage
- help : `genpas -h` or `genpas --help`
- Default string length = 10
- `genpas` to generate a string with random lowercase, uppercase, and numbers at default length (10).
- `genpas 20` to generate a string with random lowercase, uppercase, and numbers at length 20.
- `genpas 20 2` to generate 2 strings with random lowercase, uppercase, and numbers at length 20.
- `genpas 15 -luns 2` to generate 2 strings with random lowercase, uppercase, numbers and special characters at length 15.
- `genpas -luns` to generate 1 string with random lowercase, uppercase, and numbers at default length (10).
