# Week 1 Lab Report
## Tutorial for incoming 15L students and my future self
---
## Installing VScode
Go to https://code.visualstudio.com/ to download for Windows or whatever operating system you run on. After installing the package, open VScode and it should look like this:
![VScode Startup](https://user-images.githubusercontent.com/110417453/212200666-ec6b3fd4-fea4-4176-ad41-647a5a2b565a.png)

## Remotely Connecting
After installing VScode, open the terminal by doing `` Ctrl + ` `` or going to the top and choosing `New Terminal` under `Terminal`. A terminal should pop up at the bottom.
![Terminal](https://user-images.githubusercontent.com/110417453/212201723-d9a2fc45-b67d-4666-8191-881aae19a41a.png)

Now we have to change the terminal from powershell to bash.
Follow the directions at https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994.
If you have bash active, your terminal should automatically start with `$`

From here, type `ssh cs15lwi23atl@ieng6.ucsd.edu` or replace the atl to your specific account. If this is your first time connecting, and it asks `Are you sure you want to continue connecting (yes/no/[fingerprint])?`, type `yes` and press enter.
Now enter your password and you will be logged into the remote server.
![Connected to Remove Server](https://user-images.githubusercontent.com/110417453/212202565-f4f3679e-2a82-461d-8e6e-adfb85d6f4e0.png)

## Trying Some Commands
Now we can run some commands:
* ` cd ~ ` or ` cd ` changes your directory to the home
* ` pwd ` prints your working directory
* ` ls ` prints the list of files you have
* ` ls <directory> ` prints the list of files at that directory
* ` cp <directory> <destination>` copies the files at that directory to the destination
* ` cat <directory> ` concatanates (prints) the files at that directory
* ` exit ` logs your out of the remote server
![Commands](https://user-images.githubusercontent.com/110417453/212203538-3cdd0f05-2e21-4df8-81f9-a9247ac8e085.png)

