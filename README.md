# How to set up a Minecraft Forge Server
## Download a forge installer file. 
Use the following link. [forge file](http://files.minecraftforge.net/)
In the left it will be versions of minecraft.And to the right it should be a install button. and the title is Download Recomended.
Then make a new folder. you can name it whatever you want. copy the forge file and place it in your folder(thats going to be your server)
## Run the forge installer
Start the command prompt by pressing Windows key and type cmd and enter.
Go to your folder
```
cd c:\(Your folder name)
``` 
Run the forge installer file.
```
java -jar "file name"
```
Choose your folder when you see dialog. Choose "diinstall server" option during the installation.
when you are done installing the server write
```
rename (the server filer) Server.jar
```
open eula.txt and change false to TRUE
## Start server
```
java -jar server.jar
```
then your done...

Extra : if you want to make a launcher file then open notepad and type following,

java -jar server.jar

and save the file as "start_server.bat" and save. 
