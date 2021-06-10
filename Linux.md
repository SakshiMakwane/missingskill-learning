

 

     

# LINUX
## HISTORY OF LINUX
<img src="images/Saved Pictures/linux.png">

## BASIC LINUX COMMAND

<ol type="1">
<li style="color:blue"><h3><b>Listing Commands</b></h3></li>
<p>ls stands for list. It is used to show the list of folder/files in the current directory/folder.Some of the listing command that are mostly used are shown below.</p>
<p><b>a]ls:-</b> Only used to show the list of folder/files in the current directory/folder. </p>
<p>Synatx: ls </p>
  <p>Execution:</p>
  
  
 <p><img src="images/Camera Roll/ls.png"  width="300px"></p>

<p><b>b]ls -l:-</b>It is used to show the list of folder/files with thier access permission</p>
<p>Synatx: ls -l </p>
<p>Execution:</p>
  
 <p><img src="images/Camera Roll/ls-l.png"  width="300px"></p>

<p><b>c]ls -h:- </b>It turns some of the details of file which can not be understand by human into human redable format. </p>
<p>Synatx: ls -l -h </p>
<p>Execution:</p>
  
 <p><img src="images/Camera Roll/ls-h.png"  width="300px"></p>

<p><b>d]ls -t:-</b> It is used to show the file which created first at the top of the list.</p>
<p>Synatx: ls -l -h -t </p>
<p>Execution:</p>
 <p><img src="images/Camera Roll/ls-t.png"  width="300px"></p>


<p><b>e]ls -r :-</b> It is used as same as ls -t the only difference is it shows first created file at bottom that means it show file in reverse order.</p>
<p>Synatx: ls -l -h -t -r </p>
<p>Execution:</p>
 <p><img src="images/Camera Roll/ls-r.png"  width="300px"></p>

<p><b>f]ls -F:- </b>If the list conatain directory then it will added **/** in front of directory</p>
<p>Synatx:  ls -l -h -t -r -F </p>
<p>Execution:</p>
 <p><img src="images/Camera Roll/ls-f.png"  width="300px"></p>


<li style="color:blue"><h3><b>cd and it variants</b></h3></li>
<p><b>a]cd:-</b> cd stands for change directory.As the name stated it is used to jump from one directory to other.</p>
<p>Synatx: cd [fileName]OR[folderName]</p>
<p>Execution:</p>
 <p><img src="images/Camera Roll/cd.png"  width="300px"></p>

<p><b>b]cd - :- </b>It is used to jump to home directory.</p>
<p>Synatx: cd -</p>
<p>Execution:</p>
 <p><img src="images/Camera Roll/cd-.png" width="300px"></p>

<p><b>c]cd .. :-</b> Used to jump on previous directory/file</p>
<p>Synatx: cd .. </p>
<p>Execution:</p>
 <p> <img src="images/Camera Roll/cddot.png"  width="300px"> </p>

<li style="color:blue"><h3><b>cp</b></h3></li>
<p><b>a]cp :-</b>stands for copy file.You can copy data to another file OR copy file to another loaction.</p>
<p>Synatx: cp [filename] [path/to/copy/] </p><p>Synatx: cp filename1 newfilename </p>
<p>Execuation:</p>
 <p><img src="images/Camera Roll/cp.png"  width="300px"></p>
 
<p><b>b]cp-rf: copy one floder to another folder-</b>
 <p>Synatx: cp -rf [sourcefolder] [destinationfolder/] </p>
<p>Execution:</p>
 <p><img src="images/Camera Roll/cp1.png"  width="300px"></p>


<li style="color:blue"><h3><b>mv</b></h3></li>
<p>mv stands for move. It is used to move file.</p>
<p>Synatx: mv [filename] [path/to/move/] </p>
<p>Execution:</p>
 <p><img src="images/Camera Roll/mv.png"  width="300px"></p>

<li style="color:blue"><h3><b>mv using for renaming</b></h3></li>
<p>move command is also used to rename the file.</p>
<p>Synatx: mv [filename1] [newfilename] </p>
<p>Execution:</p>
 <p><img src="images/Camera Roll/mv1.png"  width="300px"></p>


<li style="color:blue"><h3><b>rm</b></h3></li>
<p>rm stands for Remove.It will delete the file from folder/directory.</p>
<p>Synatx: rm [filename] </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/rm.png"  width="300px"></p>


<li style="color:blue"><h3><b>pwd</b></h3></li>
<p>pwd stands for Print Working Directory. It gives loaction of your current directory.</p>
<p>Synatx: pwd </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/pwd.png" width="300px"></p>


<li style="color:blue"><h3><b> who</b></h3></li>
<p>Who command gives us who is the owner/rootuser working currently.</p>
<p>Synatx: who </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/who.png"  width="300px"></p>

<li style="color:blue"><h3><b> whoami</b></h3></li>
<p>This command tell us who is the owner.</p>
<p>Synatx: whoami</p>
<p>Execution:</p>
<p><img src="images/Camera Roll/whoami.png"  width="300px"></p>

<li style="color:blue"><h3><b> history</b></h3></li>
<p>This command is used to tell all the previous command we have used untill now.</p>
<p>Synatx: history </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/history.png"  width="300px"></p>

<li style="color:blue"><h3><b> exit</b></h3></li>
<p>It is used to leave the terminal.</p>
<p>Synatx: exit </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/exit.png"  width="300px"></p>

<li style="color:blue"><h3><b>less</b></h3></li>
<p>less command show the content of file on a single page aslo give scroll bar .</p>
<p>Synatx: less [filename] </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/less.png" width="300px"></p>
 <p><img src="images/Camera Roll/less1.png" width="300px"></p>

<li style="color:blue"><h3><b>more</b></h3></li>
<p>more command gives content fixed to your terminal page.</p>
<p>Synatx: more [filename] </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/more.png"  width="300px"></p>

<li style="color:blue"><h3><b>echo</b></h3></li>
<p>This command is used to display message on terminal.</p>
<p>Synatx: echo [message]</p>
<p>Execution:</p>
<p><img src="images/Camera Roll/echo.png"  width="300px"></p>

<li style="color:blue"><h3><b>top</b></h3></li>
<p>This command is used toshow list of system information and processes.</p>
<p>Synatx: top</p>
<p>Execution:</p>
<p><img src="images/Camera Roll/top.png" width="300px"></p>

<li style="color:blue"><h3><b>ps-ef</b></h3></li>
<p>This command is used to display all the running application on the system.</p>
<p>Synatx: ps -ef</p>
<p>Execution:</p>
<p><img src="images/Camera Roll/ps-ef.png"  width="300px"></p>

<li style="color:blue"><h3><b>touch</b></h3></li>
<p>This command is used to create file.</p>
<p>Synatx: touch [newfilename] </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/touch.png"  width="300px"></p>

<li style="color:blue"><h3><b>ping</b></h3></li>
<p>This command is used to check the concetivity with outside world.</p>
<p>Synatx: ping [anyNetworkingSiteName] </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/ping.png"  width="300px"></p>

<li style="color:blue"><h3><b>ifconfig</b></h3></li>
<p>It gives you configuration of your system ,for example ip address etc .</p>
<p>Synatx: ifconfig </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/ifconfig.png"  width="300px"></p>

<li style="color:blue"><h3><b>ssh</b></h3></li>
<p>ssh is used to start communication between two hosts and share data with each other.</p>
<p>Synatx: ssh </p>
<p>Execution:</p>
 <p><img src="images/Camera Roll/ssh.png"  width="300px"></p>

<li style="color:blue"><h3><b>which</b></h3></li>
<p>In linux everty thing is stored as file.Which command is used to show the path of any command.</p>
<p>Synatx: which commandName </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/which.png" width="300px"></p>

<li style="color:blue"><h3><b>wget</b></h3></li>
<p>This command is not specific part of linux but it is used to get ipaddress of your system.</p>
<p>Synatx: wget [URL]</p>
<p>Execution:</p>
<p><img src="images/Camera Roll/wget.png"  width="300px"></p>

<li style="color:blue"><h3><b>help</b></h3></li>
<p>As the name stated itself it helps us to find the infomation we needed about commond or system.</p>
<p>Synatx: --help OR help </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/help.png"  width="300px"></p>

<li style="color:blue"><h3><b>mkdir</b></h3></li>
<p>This command is used to make/create new directory in the system.</p>
<p>Synatx: mkdir [directoryName] </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/mkdir.png"  width="300px"></p>


<li style="color:blue"><h3><b>Command For Creating Directory With Subdirectory</b></h3></li>
<p><b>mkdir:-</b>This command is used to directory inside directory in the system.</p>
<p>Synatx: mkdir [directoryName1/directoryName2] -p </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/mkdir-p.png"  width="300px"></p>

<li style="color:blue"><h3><b>Command For Creating Multiple Directory </b></h3></li>
<p>This command is used to multiple directory in the system.</p>
<p>Synatx: mkdir [directoryName1] [directoryName2] [directoryName3]  </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/multiplemkdir.png"  width="300px"></p>

<li style="color:blue"><h3><b>Command For Deleting Directory </b></h3></li>
<p><b>rmdir:- </b>This command is used to delete directory in the system.</p>
<p>Synatx: rmdir [directoryName]  </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/rmdir.png"  width="300px"></p>

<li style="color:blue"><h3><b>Command For Deleting Directory as well as File Inside It </b></h3></li>
<p><b>rm-rf  :-</b>This command is used to delete  directory in the system along with all the file inside the directory.</p>
<p>Synatx: rm -rf [directoryName] </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/rm-rf.png"  width="300px"></p>


<li style="color:blue"><h3><b>Command For Deleting Multiple Directory </b></h3></li>
<p><b>rm-rf :-</b>This command is used to delete multiple directory in the system along with all the file inside the directory.</p>
<p>Synatx: rm -rf * </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/rm-rf1.png"  width="300px"></p>

<li style="color:blue"><h3><b>Cat Command and its variety </b></h3></li>
<p><b> cat:-</b>This command is used by varoius to display , modify , Or overwrite the data.</p>
<p><b>a] cat:-</b>This command is used by varoius to display content inside the file.</p>
<p>Synatx: cat [fileName] </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/catfile.png"  width="300px"></p>

<p><b>b] cat:-</b>This command is used by varoius to modify the content inside the file.</p>
<p>Synatx: cat >> [fileName] </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/catwrite.png"  width="300px"></p>
 <p><img src="images/Camera Roll/catfile.png"  width="300px"></p>

<p><b>c] cat:-</b>This command is used by varoius to overwrite the content of existing file.</p>
<p>Synatx: cat > [fileName] </p>
<p>Execution:</p>
 <p><img src="images/Camera Roll/catfile.png"  width="300px"></p>
<p><img src="images/Camera Roll/catoverwrite.png"  width="300px"></p>


<li style="color:blue"><h3><b>Command to Show Hidden Files</b></h3></li>
<p><b> ls-a:-</b>This command is usedto show all the hidden file inside the folder/directory.The hidden files are shown by using (.) symbol.</p>
<p>Synatx: ls -a </p>
<p>Execution:</p>
<p><img src="images/Camera Roll/ls-a.png"  width="300px"></p>


<li style="color:blue"><h3><b>Command to clear the screen</b></h3></li>
<p><b> clear:-</b>This command is used to clear the screen</p>
<p>Synatx: clear</p>
<p>Execution:</p>
<p><img src="images/Camera Roll/clear.png" width="300px"></p>


</ol>

### SUMMARY TABLE 
<table style="border:1px solid black">


  <tr><th>Sr.No</th>
  <th>Commanad</th>
  <th>Synatx</th>
  <th>Used For</th>
  </tr>
  <tr><td>1</td>
  <td>ls</td> 
  <td>ls</td> 
  <td>list the folders/files</td>
  </tr>
  <tr><td>2</td>
  <td>ls-l</td>
  <td>ls -l</td>
  <td>list the file with its detailed information</td>
  </tr>
  <tr><td>3</td>
  <td>ls-h</td>
  <td>ls -l -h</td>
  <td>To convert the dtail infomation in human readable form</td>
  </tr>
  <tr><td>4</td>
  <td>ls-t</td>
  <td>ls -l -h -t</td>
  <td>To show files which created first at top in the list</td>
  </tr>
  <tr><td>5</td>
  <td>ls-r</td>
  <td>ls -l -h -t -r</td>
  <td>To show the reverse list</td>
  </tr>
  <tr><td>6</td>
  <td>ls-F</td>
  <td>ls -l -h -t -r -F</td>
  <td>To add **/** after the folder</td>
  </tr>
  <tr><td>7</td>
  <td>cd</td>
  <td>cd [fileName/folderName]</td>
  <td>jump from one loaction to another loaction</td>
  </tr>
  <tr><td>8</td>
  <td>cd-</td>
  <td> cd -</td>
  <td>jump to home directory</td>
  </tr>
  <tr><td>9</td>
  <td>cd..</td>
  <td>cd ..</td>
  <td>jump to previous location</td>
  </tr>
  <tr><td>10</td>
  <td>cp</td>
  <td> Synatx1:cp [filename] [path/to/copy/]
    Syntax2: cp [filename1] [newfilename]</td>
  <td>copy data from one file to another file OR to other loaction</td>
  </tr>
  <tr><td>11</td>
  <td>cp-rf</td>
  <td>cp -rf [source] [destination]</td>
  <td>copy folder to another folder</td>
  </tr>
  <tr><td>12</td>
  <td>mv</td>
  <td>mv [filename] [path/to/move/] </td>
  <td>move file from one location to another loaction</td>
  </tr>
  <tr><td>13</td>
  <td>mv as renaming</td>
  <td>mv [filename1] [newfilename]</td>
  <td>it will rename the existing file</td>
  </tr>
  <tr><td>14</td>
  <td>rm</td>
  <td>rm [fileName]</td>
  <td>delete the file</td>
  </tr>
  <tr><td>15</td>
  <td>pwd</td>
  <td>pwd</td>
  <td>show the path of current working directory</td>
  </tr>
  <tr><td>16</td>
  <td>who</td>
  <td>who</td>
  <td>give users name which is currently working</td>
  </tr>
  <tr><td>17</td>
  <td>whoami</td>
  <td>whoami</td>
  <td>return value of main user of system</td>
  </tr>
  <tr><td>18</td>
  <td>history</td>
  <td>history</td>
  <td>gives commands which was previously used  by user</td>
  </tr>
  <tr><td>19</td>
  <td>exit</td>
  <td>exit</td>
  <td>exit the terminal</td>
  </tr>
  <tr><td>20</td>
  <td>less</td>
  <td>less [filename]</td>
  <td>open file content in one page</td>
  </tr>
  
  <tr><td>21</td>
  <td>more</td>
  <td>more [filename]</td>
  <td>show content of file inside the terminal</td>
  </tr>
  <tr><td>22</td>
  <td>echo</td>
  <td>echo ["message"]</td>
  <td>print message on terminal</td>
  </tr>
  <tr><td>23</td>
  <td>top</td>
  <td>top</td>
  <td>show list of processes and system info</td>
  </tr>
  <tr><td>24</td>
  <td>ps-ef</td>
  <td>ps -ef</td>
  <td>display all running application</td>
  </tr>
  <tr><td>25</td>
  <td>touch</td>
  <td>touch [fileName]</td>
  <td>Create new file</td>
  </tr>
  <tr><td>26</td>
  <td>ping</td>
  <td>ping [networkingSiteName]</td>
  <td>to check conectivity with outside world </td>
  </tr>
  <tr><td>27</td>
  <td>ifconfig</td>
  <td>ifconfig</td>
  <td>gives configuration of system</td>
  </tr>
  <tr><td>28</td>
  <td>ssh</td>
  <td>ssh key</td>
  <td>Used to start communication over hosts</td>
  </tr>
  <tr><td>29</td>
  <td>which</td>
  <td>which [commandName]</td>
  <td>give path where command is stored </td>
  </tr>
  <tr><td>30</td>
  <td>wget</td>
  <td>wget [URL]</td>
  <td>gives the ip of system</td>
  </tr>
  <tr><td>31</td>
  <td>mkdir</td>
  <td>mkdir [directoryName]</td>
  <td>create new directory</td>
  </tr>
  <tr><td>32</td>
  <td>mkdir</td>
  <td>mkdir [folderName1/folderName2] -p</td>
  <td>create folder inside folder</td>
  </tr>
  <tr><td>33</td>
  <td>mkdir</td>
  <td>mkdir [directoryName1] [directoryName2] [directoryName3] </td>
  <td>create multiple folder  in current directory</td>
  </tr>
  <tr><td>34</td>
  <td>rmdir</td>
  <td>rmdir [directoryName]</td>
  <td>delete directory </td>
  </tr>
  <tr><td>35</td>
  <td>rm-rf</td>
  <td>rm -rf *</td>
  <td>delete all directory along with files</td>
  </tr>
  <tr><td>36</td>
  <td>cat</td>
  <td>cat [filename]</td>
  <td>display content in the file</td>
  </tr>
  <tr><td>37</td>
  <td>cat>></td>
  <td>cat >> [filename] </td>
  <td>modify the content of file</td>
  </tr>
  <tr><td>38</td>
  <td>cat></td>
  <td>cat > [filename]</td>
  <td>overwrite the content</td>
  </tr>
  <tr><td>39</td>
  <td>ls-a</td>
  <td>ls -a</td>
  <td>show hidden file using (.)symbol</td>
  </tr>
  <tr><td>40</td>
  <td>help</td>
  <td>help</td>
  <td>gives information about all commands</td>
  </tr>
  <tr><td>41</td>
  <td>man</td>
  <td>man [commandName]</td>
  <td>gives information about specific command</td>
  </tr>
  <tr><td>42</td>
  <td>clear</td>
  <td>clear</td>
  <td>clear the screen</td>
  </tr>
  
 </table>

## FILE SYSTEM AND DIRECTORY
<p>Everything is linux is stored as file.Some of the main files which let the system work are shown below.
If you want to see files/directory inside your root folder used the given command.</p>
<p>If you see the second command that means you are now in your root directory.</p>
<p>After entering root directory you can see all the files/directory inside root by using third command.</p>
<table>
  <tr><td>sakshi@sakshi-virtual-machine:~$ cd /</td></tr>
  <tr><td>sakshi@sakshi-virtual-machine:/$</td></tr>
<tr><td>sakshi@sakshi-virtual-machine:/$ ls -l</td></tr>
</table>
<ol type="1">
<li><b>/boot</b></li>
<p>In boot folder kernel is located/stored.Basic directory inside the root directory is boot.
    If you go inside the boot folder you can see another directory named as grub,
    which is a boot lodder directory it pickup file system and loaction </p>
<li><b>/bin</b></li>
  <p>Bin contain binary files.These binary files conatin userlevel applictaion.All the command we used in linux is stored here </p>
  <table>
  <tr><td>sakshi@sakshi-virtual-machine:/$ cd bin/</td></tr>
  </table>
<li><b>/sbin</b></li>
  <p>The sbin file cannot be used by noraml user it can only be access by system admin.sbin represent system binary files. </p>
  <table>
  <tr><td>sakshi@sakshi-virtual-machine:/$ cd sbin/</td></tr>
  </table>
<li><b>/home</b></li>
  <p>The directory is where new user is created.Whenever we add a new user it will create that folder inside /home folder </p>
  <table>
  <tr><td>sakshi@sakshi-virtual-machine:/$ cd home/</td></tr>
  </table>
<li><b>/var</b></li>
  <p>System level variables are stored here. </p>
  <table>
  <tr><td>sakshi@sakshi-virtual-machine:/$ cd var/</td></tr>
  </table>
<li><b>/usr</b></li>
  <p>User related resources are available here(user system resources).If you install any software then information related to is store ih this folder </p>
  <table>
  <tr><td>sakshi@sakshi-virtual-machine:/$ cd usr/</td></tr>
  </table>
<li><b>/root</b></li>
  <p>In /root folder is the home folder for root user only admin can access this folder.Root user always denoted by # and normal user is denoted by $.Root user have all the premissions in the system. </p>
  <table>
  <tr><td>sakshi@sakshi-virtual-machine:/$ cd root/</td></tr>
  </table>
<li><b>/tmp</b></li>
  <p>This folder is known as temporary folder.It is used when system want to store something temporary. </p>
  <table>
  <tr><td>sakshi@sakshi-virtual-machine:/$ cd tmp/</td></tr>
  </table>
<li><b>/etc</b></li>
  <p>In etc folder system level configuration information is given . </p>
  <table>
  <tr><td>sakshi@sakshi-virtual-machine:/$ cd etc/</td></tr>
  </table>
<li><b>/lib</b></li>
  <p>System library is stored here. </p>
  <table>
  <tr><td>sakshi@sakshi-virtual-machine:/$ cd lib/</td></tr>
  </table>
<li><b>/dev</b></li>
  <p>dev file contain external device information.It is kind of memory file. </p>
  <table>
  <tr><td>sakshi@sakshi-virtual-machine:/$ cd dev/</td></tr>
  </table>  
<li><b>/opt</b></li>
  <p>It will store user level software and aslo keep track of that software. </p>
  <table>
  <tr><td>sakshi@sakshi-virtual-machine:/$ cd opt/</td></tr>
  </table>

</ol>

### SUMMARY TABLE
|Sr.No|File System|Used For|
|------|-----------|--------|
|1|/boot|In boot folder kernel is located/stored|
|2|/bin|Bin contains binary files.|
|3|/sbin|The sbin file cannot be used by the normal user it can only be accessed by the system admin. sbin represents system binary files.|
|4|/lib|System library is stored here.|
|5|/home|The directory is where a new user is created|
|6|/root|The home folder for root user only admin can access this folder|
|7|/etc|System level configuration information is given|
|8|/dev|File contains external device information.|
|9|/opt|It will store user-level software and also keep track of that software.|
|10|/tmp|It is used when the system wants to store something temporary.|
|11|/usr|User related resources are available here(user system resources)|
|12|/var|System level variables are stored here.|


