# Project: Linux Commands DeepDive
> Linux Distrbution: Amazon Linux based on Red hat Enterprise  Linux. 
> Terminal: Window Powershell.

## Task One: Creating folder with sudo

### a. Open terminal and Connect to linux server using ssh
![ssh -i command to connect to remote linux server](./images/1.%20connecting%20to%20linux%20server.png)

### b. Creating folder in the restricted directory such as root directory using mkdir (without sudo) to see the permission denied error
![mkdir /root/example](./images/2.%20Creating%20folder%20in%20the%20root%20directory%20with%20sudo.png)

### c.  Creating folder in the restricted directory such as root directory using mkdir (with sudo) 
![sudo mkdir /root/example](./images/3.%20creating%20folder%20in%20the%20root%20directory%20using%20sudo.png)

### d. Verify the folder creation using ls /root.
![sudo ls /root](./images/4.%20confirmng%20the%20directory%20creatin%20using%20ls%20command.png)

## Task Two: Demostrate pwd (Print Working Directory) command
### a. Display full path of your current working directory using pwd
![pwd](./images/4.%20pwd%20for%20current%20working%20directory.png)

## Task Three: cd (Change Directory) Command
### a. Navigate to the root directory using sudo cd /
![sudo cd /](./images/8.%20sudo%20cd%20root.png)
### b. Run pwd to confirm your current directory
![pwd](./images/4.%20pwd%20for%20current%20working%20directory.png)

### c. Run sudo ls -l to list files and directory in the root filesystem
NB append sudo because it is root directory

![sudo ls -l](./images/9.%20sudo%20ls%20-l.png)

### c. Navigate to /usr using sudo cd /usr
![sudo cd /usr](./images/7.%20ls%20usr.png)

## Hustle Task One: 
### a. Creating photos directory in /usr using sudo mkdir /usr/photos.
![sudo mkdir /usr/photos](./images/11.%20mkdir%20photos.png)

### b. Navigate to the photos directory using cd photos command
![cd photos](./images/12.%20navigate%20to%20photos%20directory.png)

### c. Create 3 more directory (photo1, photo2, photo3) in the photos directory using sudo mkdir photo1 photo2 photo3
![sudo mkdir photo1 photo2 photo3](./images/13.%20Three%20more%20photos%20directory.png)

### d. List the newly created directory in the terminal using ls -l
![ls -l](./images/14.%20show%20the%20created%20directory%20using%20ls.png)

### e. Navigate into one of them (photo1)
![cd photo1](./images/15.%20navigating%20to%20photo1.png)

### f. Show full path of your current directory usinf pwd
![pwd](./images/16.%20full%20path%20of%20the%20photo1%20directory.png)

## Task Four: ls (list) Command - To list content of a directory using different flags
### a. Run ls to list name of files and directories in the directory we are currently are
![ls](./images/17.%20ls.png)

### b. Run ls -R Command - To list all files in the subdirectories
![ls -R](./images/18-ls%20-R.png)

### c. Run ls -lh to show file size in readable format
![ls -lh](./images/19%20ls%20-lh.png)

## Task Five: cat (concatenate) Command
### a. Run cat /etc/os-release to show content of os-release in /etc directory. os-release directory display detail of Operating System.
 ![cat /etc/os-release](./images/20.%20cat%20os-release.png)

 ## Task Six: cp (Copy) Command
 ### a. Copy filename.txt to /home/ubuntu/Documents directory using sudo cp filename.txt /home/ubuntu/Documents
 ![sudo cp filename.txt /home/ubuntu/Documents](./images/21.%20cp%20filename%20to%20documents%20directory.png)

 ### b. Copy content of filename.txt to filename1.txt using sudo cp filename.txt filename1.txt

 ![sudo cp filename.txt filename1.txt](./images/22%20cp%20filename%20to%20filename1.png)

 ### c. Copy content of a directory to another directory using cp -R /home/ubuntu/Documents /home/ubuntu/document_backup
 ![cp -R /home/ubuntu/Documents /home/ubuntu/document_backup](./images/23.%20cp%20document%20to%20document_backup.png)

 ### d. Copy multiple files into directory using cp filename1 filename2 /home/ubuntu//Documents
 ![sudo cp filename1 filename2 /home/ubuntu//Documents](./images/cp%20filename1%20filename2%20to%20Document%20directory.png)

## Task Seven: mv (Move) Command
### a. Move filename to /home/ubuntu/Documents directory using mv filename.txt /home/ubuntu/Documents
![mv filename.txt /home/ubuntu/Documents](./images/24.%20mv%20newfile%20to%20Documents%20direcotry.png)

### b. Rename newfile to oldfile using mv newfile.txt oldfile.txt
![mv newfile.txt oldfile.txt](./images/25.%20mv%20to%20rename%20newfile%20to%20oldfile.png)

## Task Eight: rm (remove) command
### a. Remove oldfile.txt using rm oldfile.txt
![rm oldfile.txt](./images/26.%20rm%20oldfile.png)

### b. Remove multiple files using rm filename.txt filename1.txt
![rm filename.txt filename1.txt](./images/rm%20filename%20filename1.png)

## Task Nine: touch Command
### a. Create web.html using touch /home/ubuntu/Documents/web.html
![touch /home/ubuntu/Documents/web.html](./images/28.%20touch%20web.html%20file.png)

## Task Ten: find Command
### a. find web.html in home directory and subdirectories using find /home -name web.html
![find /home -name web.html](./images/29.%20find%20webhtmlin%20home%20directory%20and%20subdirecotry.png)
