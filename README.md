# 4Down
A tool for downloading threads from 4chan


///
Please read this before proceeding : 

This tool uses ``wget`` and thus you need to have it installed as a dependency. 

To install the needed dependencies you can use the following (depending on your distro)

 Arch/Derivatives :             ``sudo pacman -S wget``
 
 Debian/many family members :   ``sudo apt install wget``
 
 Fedora :                       ``sudo rpm install wget``

These are usually preinstalled or you have them installed from another package, but just incase, its up there ^^^ !

Once you have the prerequisites installed, you can downlaod the program, you can either download the entire .zip from this github, or just the script itself. Once you download the script, make it executable using ```chmod +x 4down``` in the correct directory , also make sure it is in your $PATH variable. So for example /$HOME/scripts/. You can then run it via the terminal.

///
Operation :

CD into the folder where you want the contents to download, this is mainly just to make sure you dont fill up your home folder with stuff (wget may have some issues and create folders, Im sure you can figure out where things get downloaded).

Run ``4down`` and make sure its in your path.
Copy and paste the thread URL
The thread shows off some neat seperation , but you can comment those lines out if you dont want it to show itself breaking down the link.

You then choose whether you want to download all of the contents to make an (almost, if not) perfect copy of the given thread, or if you want to download just content (images, videos, gifs). As a new feature implemented in update 2.0, You are able to do a mix of both, and download not only a copy of the thread that is effectively fully functional, but also all of the contents of the thread as well!

It'll go and download what you have requested.

Wait...

Congratulations ! You have downloaded a thread ! You have just one more step before you're done, you choose whether you want to delete the small preview versions of files (marked with an "s" at the end), or if you want to delete the preview versions. Typically there isn't really a point in downloading the preview versions too so I usually delete them.


Thank you for using 4Down! If you have any questions, please feel free to reach out.
