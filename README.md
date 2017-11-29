# 430ChoreTracker

Welcome to the README file of the 430 Chore Tracker project! This project is run on the CS server provided by UMW. In order to run the project there are two primary methods. (One of them is a lot nicer than the other.)

## To Install

### Method One

While logged into cs.umw.edu

Clone the master repository, and then copy **ALL** of the files into the 'public\_html' directory in your home directory on the CS server. If you do not have a directory with this name, simply create it using mkdir.

### Method Two (and the one we used)

while logged into cs.umw.edu

rm -r public_html

(This command gets rid of your existing public\_html directory. Feel free to skip this step if you don't have it)

ln --symbolic -T /home/yourUserName/path/to/getTo/boostrap public\_html

(replace the path with the one to get to your git repository. Make sure you're still in your home directory when you run this command. You can the path to your git repository by navigating to it and using the command pwd)

This will create a symbolic link to boostrap called public\_html. The server will see this and think it's a file, go to it, get linked to the contents of boostrap, and voila, you're good to go.

## To Run

Simply go to www.cs.umw.edu/~yourUserName

(In case it wasn't obvious, please replace 'yourUserName' with your actual username while logged into the server.)
