# 4Down
A tool for downloading threads from 4chan

## Prerequisites

This tool uses `wget` and thus you must have it installed.<br/>
To install the needed dependencies, you can use the following (depending on your distro):

Arch and derivatives: `# pacman -S wget`<br/>
Debian and derivatives: `# apt install wget`<br/>
RHEL and derivatives: `# rpm install wget`

These are usually preinstalled, or you have them installed from another package. But just in case, it's there! ^^

Once you have the dependencies installed, you can downlaod the program. You can either download the repository using `git clone https://github.com/Cipher66hz/4Down.git`, or just the script itself. Once you download the script, make it executable using `chmod +x 4down` in the correct directory and make sure it is in your $PATH variable. You can then run it via the terminal.

## Usage

`cd` into the directory where you want the contents to download, this is mainly just to make sure you dont fill up your home folder with stuff (wget may have some issues and create folders, Im sure you can figure out where things get downloaded).

Run `4down`.<br/>
Copy and paste the thread URL.<br/>
The thread shows off some neat separation, but you can comment those lines out if you dont want it to show itself breaking down the link.

You then choose whether you want to download all of the contents to make a copy of the given thread, or if you want to download just the file content (images, videos, GIFs, etc.). As a new feature implemented in update 2.0, You are able to do a mix of both, and download not only a copy of the thread that is effectively fully functional, but also all of the contents of the thread as well!

Congratulations, you have downloaded a thread! You have just one more step before you're done: you must choose whether you want to delete the small preview versions of files (marked with an "s" at the end), or if you want to delete the preview versions. Typically there isn't really a point in downloading the preview versions as well, so I usually delete them.

As a note, some users may opt to modify their configuration for 4down. Since 4down is simply a script and does not rely on multiple files, it is all able to be modified directly without a config file. For example, I have my `echo` and `printf` statements use `lolcat`/`lolcrab` for rainbow colors! For now, this is not going to be a feature but may be an opt-in feature in the future.

Thank you for using 4Down! If you have any questions, please feel free to reach out.