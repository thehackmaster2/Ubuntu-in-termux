# Ubuntu-in-termux
What's This?
This is a script that allows you to install Ubuntu in your termux application without a rooted device

Updates
• Updated to ubuntu 22.04

Important
• If you have to use ubuntu in termux with a x86/i*86 architecture or prefer ubuntu 19.10 you can use this branch -> https://github.com/MFDGaming/ubuntu-in-termux/tree/ubuntu19.10

• If you get an error message that says "Fatal Kernel too old" you have to uncomment the line that reads "command+=" -k 4.14.81"" (remove the # that is located in front of the line) in the "startubuntu.sh" file

Installation steps
Update termux: apt-get update && apt-get upgrade -y
Install wget: apt-get install wget -y
Install proot: apt-get install proot -y
Install git: apt-get install git -y
Go to HOME folder: cd ~
Download script: git clone https://github.com/MFDGaming/ubuntu-in-termux.git
Go to script folder: cd ubuntu-in-termux
Give execution permission: chmod +x ubuntu.sh
Run the script: ./ubuntu.sh -y
Now just start ubuntu: ./startubuntu.sh
