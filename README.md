#JSetup(jse)-


JSetup is installer for installing plugin of java jar applications. JSetup used script file to install the jar file
You must need jsetup to install jsetup plugin i.e java jar applications. JSetup is only for linux based os.

#Installing:
Clone this repo to your desktop or download this
cd to the directory
open terminal type chmod +x install
then type sudo ./install
that's done to check type jse

#Installing Java Jar Application:
Make a file name anything let's take hello_world
so paste the following 

START
name = Hello World

run = hello_jse

author = LittlEvil

jar_path = hello.jar
END

edit as your view

then cd to the directory where you have made the hello_world
then open terminal type jse --install hello_world
that's done . To check is it installed or not
type hello_jse or jse --list

#Thank you
