# Linux-Terminal-Modification
Unlock the Full Potential of Your Linux Terminal: Your Step-by-Step Guide to Mastering Terminal Customization!

Step 1: Open Your Terminal

  Launch your Linux terminal.

Step 2: Choose a Terminal Emulator

  Ensure you're using a compatible terminal emulator like GNOME Terminal, Konsole, or another that supports custom scripts and configurations.

Step 3: Install "nanofetch"

  "nanofetch" is a simple and lightweight system information tool that you can add to your terminal for a bit of flair. To install it, you need to follow these steps:

  First, ensure that you have "git" installed on your system. If not, you can install it using your distribution's package manager. For example, on Debian-based systems, you can use:

        sudo apt-get install git
Step 4: Next, clone the "nanofetch" repository from GitHub. You can do this with the following command:
  
        git clone https://github.com/Anmol-Singh-Jaggi/nanofetch.git

Step 5: After Insatalltion of nanofetch now we need to modify the shell file.
In modern distro the default is ZSH, if you want to know what shell does your distro has just type the below command
        
        echo $SHELL



Step 6: Open the Shell file 

    nano  ~/.zshsrc
    
    
    nano  ~/.bashrc
  (According to your Terminal Shell)
  
Step 7: Now let's modify the shell file 
  Scroll to the bottom of the file 
   
   
   ( "Make sure you don't mess up anything else in the file, it's always adviced to make a copy of original file before making any changes to the original file.")
    
 And Now type

     nanofetch
     
Step 8: If you further want to make changes like adding custom text you can add

    echo
Follwed by 

    echo "Anything You want to add goes here"
  Which will be displayed on the top.

(You can further add "uptime" at the end which will display system uptime )


"AND HERE WE HAVE A MODIFIED TERMINAL"
Happy Hacking
  
