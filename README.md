![image](https://github.com/user-attachments/assets/46150d51-795e-444b-a58c-1896317c0b06) <br>
A tool for downloading threads and their content from 4chan


## Prerequisites

This tool uses `wget` and `lolcat` (lolcat is optional, you can modify your script if you wish to use it black & white (boooring)).
To install the needed dependencies, you can use the following (depending on your distro):

Arch and derivatives: `# pacman -S wget lolcat`<br/>
Debian and derivatives: `# apt install wget lolcat`<br/>
RHEL and derivatives: `# rpm install wget lolcat`

Once you have the dependencies installed, you can download the program. You can either download the repository using `git clone https://github.com/Cipher66hz/4Down.git`, or just the script itself. Once you download the script, make it executable using `chmod +x 4down` in the correct directory and make sure it is in your $PATH variable. You can then run it via the terminal.

## Usage

`cd` into the directory where you want the contents to download, this is mainly just to make sure you dont fill up your home folder with stuff (wget may have some issues and create folders, Im sure you can figure out where things get downloaded). To make a folder you can use "mkdir (foldername)" then "cd (foldername)" , or you can make it in your GUI file manager.

1. Run `4down`.<br/>
2. Copy and paste the thread URL.<br/> 
3. Choose what amount of contents you want downloaded (thread mirror, just content, or both)

Congratulations, you have downloaded a thread! Y

As a note, some users may opt to modify their configuration for 4down. Since 4down is simply a script and does not rely on a config file, it is all able to be modified directly. For example, I have my `echo` and `printf` statements use `lolcat`/`lolcrab` for rainbow colors! For now, this is not going to be a feature but may be an opt-in feature in the future. There are also some unncessary echo commands which you may choose to comment out, I keep them in for troubleshooting/experimentation. 

Thank you for using 4Down! If you have any questions, please feel free to reach out.
