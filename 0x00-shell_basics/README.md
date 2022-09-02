#!/bin/bash
pwd is the script that prints the absolute path name of the current working directory.
ls is the script that Display the contents list of your current directory.
cd is the script that changes the working directory to the user’s home directory.

ls -l is the script that Display current directory contents in a long format.
ls -la is the script that Display current directory contents, including hidden files (starting with .). Use the long format.
ls -lna is the script that Display current directory contents in a Long format, with user and group IDs displayed numerically And hidden files (starting with .)
.
mkdir /tmp/my_first_directory is the script that creates a directory named my_first_directory in the /tmp/ directory.
mv /tmp/betty /tmp/my_first_directory/ is the script that Move the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory/betty is the script that Delete The file betty in /tmp/my_first_directory.
rm -r /tmp/my_first_directory is the script that Delete the directory my_first_directory that is in the /tmp directory.
cd - is the script that changes the working directory to the previous one.
ls -la . .. /boot is the script that  lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile is the script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
ln -s /bin/ls __ls__ is the script that Create a symbolic link to /bin/ls, named __ls__. 
cp -nu *.html .. is the script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
mv [:upper:]]* /tmp/u is the script that moves all files beginning with an uppercase letter to the directory /tmp/u.
rm *~ is the script that deletes all files in the current working directory that end with the character ~.
mkdir -p welcome/to/school is the script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
