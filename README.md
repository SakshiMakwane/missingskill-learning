
 <h1>Missing-Skill-Learning Report</h1>
 <h3>Presented by Sakshi Makwane</h3>
<h1>SUMMARY</h1>
<p ><span style="color:DodgerBlue;">The missing-skill-learning session helps me to learn new skills in deep. In these sessions, I have learned about Linux, Git, and JavaScript. These sessions of Linux give me a detailed idea of Linux History and the commands. Increase my understanding of Javascript. I think the main part of javascript is the function which was very well described by taking many examples. How the computer contents with each other over the network was explained remarkably in the session of the basic building block of web development. 
 
Before learning things from missing skills I had some knowledge of Linux and javascript. But learning from missing-skills expand my skills. The most interesting and new part for me was learning Git Hub. but never used git hub it was amazing to see how the git hub helps the programmers to work with each other from different places on the same project simultaneously. By creating the repository, push-pull request, creating new branches to merging them. It was something new that I learned beautifully.

I hope to learn more things in the future from missing skills.
 
 #missingskill-learning.</p>


# CONTENT TABLE

- [LINUX](#linux)
  * [HISTORY OF LINUX](#history-of-linux)
  * [BASIC LINUX COMMAND](#basic-linux-command)
    + [SUMMARY TABLE](#summary-table)
  * [FILE SYSTEM AND DIRECTORY](#file-system-and-directory)
    + [SUMMARY TABLE](#summary-table-1)
- [GIT](#git)
  * [GIT BASIC](#git-basic)
    + [SUMMARY TABLE](#summary-table-2)
  * [BASIC BUILDING BLOCK OF WEB DEVELOPMENT](#basic-building-block-of-web-development)
    + [SUMMARY TABLE](#summary-table-3)
- [JAVASCRIPT](#javascript)
  * [JAVASCRIPT HISTORY AND BASIC](#javascript-history-and-basic)
    + [CONTROL STRUCTURE SUMMARY TABLE](#control-structure-summary-table)
    + [ARITHMETIC OPERATOR SUMMARY TABLE](#arithmetic-operator-summary-table)
    + [LOGICAL OPERATOR SUMMARY TABLE](#logical-operator-summary-table)
    + [CONDITIONAL OPERATOR SUMMARY TABLE](#conditional-operator-summary-table)
  * [VARIABLES](#variables)
    + [VARIABLES SUMMARY TABLE](#variables-summary-table)
  * [DATATYPES](#datatypes)
    + [DATATYPE SUMMARY TABLE](#datatype-summary-table)
  * [SCOPE](#scope)
    + [FUNCTIONAL SCOPE](#functional-scope)
    + [LEXICAL SCOPE](#lexical-scope)
  * [COPY BY VALUE COPY BY REFERENCE](#copy-by-value-or-copy-by-reference)
  * [FUNCTIONS](#functions)
  * [FUNCTION CONSTRUCTOR AND PROTOTYPE](#function-constructor-and-prototype)
     + [CONSTRUCTOR SUMMARY TABLE](#constructor-summary-table)
  * [ARRAY ,OBJECT AND STRING METHODS](#array--objects-prototype-methods)
  * [BUILT-IN-FUNCTION IN ES6](#built-in-function-in-es6)
    + [BUILT-IN-FUNCTION IN ES6 SUMMARY TABLE](#built-in-function-in-es6-summary-table)

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
  
  
 <p><img src="images/Saved Pictures/ls.png"  width="300px"></p>

<p><b>b]ls -l:-</b>It is used to show the list of folder/files with thier access permission</p>
<p>Synatx: ls -l </p>
<p>Execution:</p>
  
 <p><img src="images/Saved Pictures/ls- l.png"  width="300px"></p>

<p><b>c]ls -h:- </b>It turns some of the details of file which can not be understand by human into human redable format. </p>
<p>Synatx: ls -l -h </p>
<p>Execution:</p>
  
 <p><img src="images/Saved Pictures/ls-h.png"  width="300px"></p>

<p><b>d]ls -t:-</b> It is used to show the file which created first at the top of the list.</p>
<p>Synatx: ls -l -h -t </p>
<p>Execution:</p>
 <p><img src="images/Saved Pictures/ls -t.png"  width="300px"></p>


<p><b>e]ls -r :-</b> It is used as same as ls -t the only difference is it shows first created file at bottom that means it show file in reverse order.</p>
<p>Synatx: ls -l -h -t -r </p>
<p>Execution:</p>
 <p><img src="images/Saved Pictures/ls-r.png"  width="300px"></p>

<p><b>f]ls -F:- </b>If the list conatain directory then it will added **/** in front of directory</p>
<p>Synatx:  ls -l -h -t -r -F </p>
<p>Execution:</p>
 <p><img src="images/Saved Pictures/ls-F.png"  width="300px"></p>


<li style="color:blue"><h3><b>cd and it variants</b></h3></li>
<p><b>a]cd:-</b> cd stands for change directory.As the name stated it is used to jump from one directory to other.</p>
<p>Synatx: cd [fileName]OR[folderName]</p>
<p>Execution:</p>
 <p><img src="images/Saved Pictures/cd.png"  width="300px"></p>

<p><b>b]cd - :- </b>It is used to jump to home directory.</p>
<p>Synatx: cd -</p>
<p>Execution:</p>
 <p><img src="images/Saved Pictures/cd -.png" width="300px"></p>

<p><b>c]cd .. :-</b> Used to jump on previous directory/file</p>
<p>Synatx: cd .. </p>
<p>Execution:</p>
 <p> <img src="images/Saved Pictures/cddot.png"  width="300px"> </p>

<li style="color:blue"><h3><b>cp</b></h3></li>
<p><b>a]cp :-</b>stands for copy file.You can copy data to another file OR copy file to another loaction.</p>
<p>Synatx: cp [filename] [path/to/copy/] </p><p>Synatx: cp filename1 newfilename </p>
<p>Execuation:</p>
 <p><img src="images/Saved Pictures/cp.png"  width="300px"></p>
 
<p><b>b]cp-rf: copy one floder to another folder-</b>
 <p>Synatx: cp -rf [sourcefolder] [destinationfolder/] </p>
<p>Execution:</p>
 <p><img src="images/Saved Pictures/cp-rf.png"  width="300px"></p>


<li style="color:blue"><h3><b>mv</b></h3></li>
<p>mv stands for move. It is used to move file.</p>
<p>Synatx: mv [filename] [path/to/move/] </p>
<p>Execution:</p>
 <p><img src="images/Saved Pictures/mv.png"  width="300px"></p>

<li style="color:blue"><h3><b>mv using for renaming</b></h3></li>
<p>move command is also used to rename the file.</p>
<p>Synatx: mv [filename1] [newfilename] </p>
<p>Execution:</p>
 <p><img src="images/Saved Pictures/mv renaming.png"  width="300px"></p>


<li style="color:blue"><h3><b>rm</b></h3></li>
<p>rm stands for Remove.It will delete the file from folder/directory.</p>
<p>Synatx: rm [filename] </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/rm.png"  width="300px"></p>


<li style="color:blue"><h3><b>pwd</b></h3></li>
<p>pwd stands for Print Working Directory. It gives loaction of your current directory.</p>
<p>Synatx: pwd </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/pwd.png" width="300px"></p>


<li style="color:blue"><h3><b> who</b></h3></li>
<p>Who command gives us who is the owner/rootuser working currently.</p>
<p>Synatx: who </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/who.png"  width="300px"></p>

<li style="color:blue"><h3><b> whoami</b></h3></li>
<p>This command tell us who is the owner.</p>
<p>Synatx: whoami</p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/whoami.png"  width="300px"></p>

<li style="color:blue"><h3><b> history</b></h3></li>
<p>This command is used to tell all the previous command we have used untill now.</p>
<p>Synatx: history </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/history.png"  width="300px"></p>

<li style="color:blue"><h3><b> exit</b></h3></li>
<p>It is used to leave the terminal.</p>
<p>Synatx: exit </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/exit.png"  width="300px"></p>

<li style="color:blue"><h3><b>less</b></h3></li>
<p>less command show the content of file on a single page aslo give scroll bar .</p>
<p>Synatx: less [filename] </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/less.png" width="300px"></p>

<li style="color:blue"><h3><b>more</b></h3></li>
<p>more command gives content fixed to your terminal page.</p>
<p>Synatx: more [filename] </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/more.png"  width="300px"></p>

<li style="color:blue"><h3><b>echo</b></h3></li>
<p>This command is used to display message on terminal.</p>
<p>Synatx: echo [message]</p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/echo.png"  width="300px"></p>

<li style="color:blue"><h3><b>top</b></h3></li>
<p>This command is used toshow list of system information and processes.</p>
<p>Synatx: top</p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/top.png" width="300px"></p>

<li style="color:blue"><h3><b>ps-ef</b></h3></li>
<p>This command is used to display all the running application on the system.</p>
<p>Synatx: ps -ef</p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/ps -ef.png"  width="300px"></p>

<li style="color:blue"><h3><b>touch</b></h3></li>
<p>This command is used to create file.</p>
<p>Synatx: touch [newfilename] </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/touch.png"  width="300px"></p>

<li style="color:blue"><h3><b>ping</b></h3></li>
<p>This command is used to check the concetivity with outside world.</p>
<p>Synatx: ping [anyNetworkingSiteName] </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/ping.png"  width="300px"></p>

<li style="color:blue"><h3><b>ifconfig</b></h3></li>
<p>It gives you configuration of your system ,for example ip address etc .</p>
<p>Synatx: ifconfig </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/ifconfig.png"  width="300px"></p>

<li style="color:blue"><h3><b>ssh</b></h3></li>
<p>ssh is used to start communication between two hosts and share data with each other.</p>
<p>Synatx: ssh </p>
<p>Execution:</p>
 <p><img src="images/Saved Pictures/ssh.png"  width="300px"></p>

<li style="color:blue"><h3><b>which</b></h3></li>
<p>In linux everty thing is stored as file.Which command is used to show the path of any command.</p>
<p>Synatx: which commandName </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/whichls.png" width="300px"></p>

<li style="color:blue"><h3><b>wget</b></h3></li>
<p>This command is not specific part of linux but it is used to get ipaddress of your system.</p>
<p>Synatx: wget</p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/wget.png"  width="300px"></p>

<li style="color:blue"><h3><b>help</b></h3></li>
<p>As the name stated itself it helps us to find the infomation we needed about commond or system.</p>
<p>Synatx: --help OR help </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/help.png"  width="300px"></p>

<li style="color:blue"><h3><b>mkdir</b></h3></li>
<p>This command is used to make/create new directory in the system.</p>
<p>Synatx: mkdir [directoryName] </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/mkdir.png"  width="300px"></p>


<li style="color:blue"><h3><b>Command For Creating Directory With Subdirectory</b></h3></li>
<p><b>mkdir:-</b>This command is used to directory inside directory in the system.</p>
<p>Synatx: mkdir [directoryName1/directoryName2] -p </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/mkdir1.png"  width="300px"></p>

<li style="color:blue"><h3><b>Command For Creating Multiple Directory </b></h3></li>
<p>This command is used to multiple directory in the system.</p>
<p>Synatx: mkdir [directoryName1] [directoryName2] [directoryName3]  </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/mkdir2.png"  width="300px"></p>

<li style="color:blue"><h3><b>Command For Deleting Directory </b></h3></li>
<p><b>rmdir:- </b>This command is used to delete directory in the system.</p>
<p>Synatx: rmdir [directoryName]  </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/rmdir1.png"  width="300px"></p>

<li style="color:blue"><h3><b>Command For Deleting Multiple Directory </b></h3></li>
<p><b>rm-rf  :-</b>This command is used to delete  directory in the system along with all the file inside the directory.</p>
<p>Synatx: rm -rf [directoryName] </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/rm-rf.png"  width="300px"></p>


<li style="color:blue"><h3><b>Command For Deleting Multiple Directory </b></h3></li>
<p><b>rm-rf :-</b>This command is used to delete multiple directory in the system along with all the file inside the directory.</p>
<p>Synatx: rm -rf * </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/rm-rf2.png"  width="300px"></p>

<li style="color:blue"><h3><b>Cat Command and its variety </b></h3></li>
<p><b> cat:-</b>This command is used by varoius to display , modify , Or overwrite the data.</p>
<p><b>a] cat:-</b>This command is used by varoius to display content inside the file.</p>
<p>Synatx: cat [fileName] </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/cat filename.png"  width="300px"></p>

<p><b>b] cat:-</b>This command is used by varoius to modify the content inside the file.</p>
<p>Synatx: cat >> [fileName] </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/cat1.png"  width="300px"></p>

<p><b>c] cat:-</b>This command is used by varoius to overwrite the content of existing file.</p>
<p>Synatx: cat > [fileName] </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/cat2.png"  width="300px"></p>


<li style="color:blue"><h3><b>Command to Show Hidden Files</b></h3></li>
<p><b> ls-a:-</b>This command is usedto show all the hidden file inside the folder/directory.The hidden files are shown by using (.) symbol.</p>
<p>Synatx: ls -a </p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/ls-a.png"  width="300px"></p>


<li style="color:blue"><h3><b>Command to clear the screen</b></h3></li>
<p><b> clear:-</b>This command is used to clear the screen</p>
<p>Synatx: clear</p>
<p>Execution:</p>
<p><img src="images/Saved Pictures/clear.png" width="300px"></p>


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
  <td>wget [ipsiteName]</td>
  <td>gives the ip of system</td>
  </tr>
  <tr><td>31</td>
  <td>mkdir</td>
  <td>mkdir [directoryName]</td>
  <td>create new directory</td>
  </tr>
  <tr><td>32</td>
  <td>mkdir</td>
  <td>mkdir [folderName1/folderName2]</td>
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
|2|/bin|Bin contain binary files.|
|3|/sbin|The sbin file cannot be used by noraml user it can only be access by system admin.sbin represent system binary files.|
|4|/lib|System library is stored here.|
|5|/home|The directory is where new user is created|
|6|/root|The home folder for root user only admin can access this folder|
|7|/etc|System level configuration information is given|
|8|/dev|File contain external device information.|
|9|/opt|It will store user level software and aslo keep track of that software.|
|10|/tmp|It is used when system want to store something temporary.|
|11|/usr|User related resources are available here(user system resources)|
|12|/var|System level variables are stored here.|


# GIT

## GIT BASIC
<img src="images/Saved Pictures/git.png">

<p>After creating a file and commiting the file .
 we can used different command to see how our project is working.
 some important and regularly used command are shom below:-</p>
 
 <ol type="1">
 <li><b>Git Status</b> :- To see the status of our repository</li>
 <p>Synatx:<table>
  <tr><td>sakshi@sakshi-virtual-machine:~/Sasha_git$ git status</td></tr>
  </table></p>
 <li><b>Git Diff</b> :- Show difference between previous changes and new changes.</li>
 <p>Synatx:<table>
  <tr><td>sakshi@sakshi-virtual-machine:~/Sasha_git$ git diff</td></tr>
  </table></p>
 <li><b>Git Log</b> :- To view all the commits till yet we used log command</li>
 <p>Synatx:<table>
  <tr><td>sakshi@sakshi-virtual-machine:~/Sasha_git$ git log</td></tr>
  </table></p>
  <li><b>Git Push</b> :- push the file from local to remote server</li>
 <p>Synatx:<table>
  <tr><td>sakshi@sakshi-virtual-machine:~/Sasha_git$ git push origin branchName</td></tr>
  </table></p>
  <li><b>Git Add Multiple File</b> :- To add multiple file in staging area .</li>
 <p>Synatx:<table>
  <tr><td>sakshi@sakshi-virtual-machine:~/Sasha_git$ git add .</td></tr>
  </table></p>
  <li><b>Git Branch</b> :- Create new branch .</li>
 <p>Synatx:<table>
  <tr><td>sakshi@sakshi-virtual-machine:~/Sasha_git$ git branch NewBranchName</td></tr>
  </table></p> 
  
 <li><b>Git Checkout</b> :- It is used to switch the branch .</li>
 <p>Synatx:<table>
  <tr><td>sakshi@sakshi-virtual-machine:~/Sasha_git$ git checkout BranchName</td></tr>
  </table></p>  
  
  <li><b>Git Checkout --</b> :- It will revert all the file to last step .</li>
 <p>Synatx:<table>
  <tr><td>sakshi@sakshi-virtual-machine:~/Sasha_git$ git checkout -- BranchName</td></tr>
  </table></p>  
   <li><b>Git Fetch</b> :- To access files from remote server to local server.</li>
 <p>Synatx:<table>
  <tr><td>sakshi@sakshi-virtual-machine:~/Sasha_git$ git fetch origin branchName</td></tr>
  </table></p> 
  
  <li><b>Git Merge</b> :- It will merge new created branches into master/main branch .</li>
 <p>Synatx:<table>
  <tr><td>sakshi@sakshi-virtual-machine:~/Sasha_git$ git merge branchName</td></tr>
  </table></p> 
  <li><b>Git Clone</b> :- It will used if files get deleted from local server then it can be retrive from remote server .</li>
 <p>Synatx:<table>
  <tr><td>sakshi@sakshi-virtual-machine:~/Sasha_git$ git clone ssh/htmlpath</td></tr>
  </table></p> 
  <li><b>Git Delete Branch</b> :- It will used to delete the branch.</li>
 <p>Synatx:<table>
  <tr><td>sakshi@sakshi-virtual-machine:~/Sasha_git$ git branch branchName -d </td></tr>
  </table></p> 

  
 </ol>

### SUMMARY TABLE

<table>
 
 <tr><th>Sr No</th>
<th>Command</th>
 <th>Synatx</th>
 <th>Used For</th>
</tr>
<tr><td>1</td>
<td>Git Init</td>
 <td>git init .</td>
 <td>Create new depository</td>
</tr>
 <tr><td>2</td>
<td>Touch</td>
 <td>touch filename </td>
 <td>Create new file</td>
</tr>
<tr><td>3</td>
<td>Git Add</td>
 <td>git add filename </td>
 <td>Added untracked file into staging area.</td>
</tr>
<tr><td>4</td>
<td>Git Commit</td>
 <td>git commit -m "message you want to show"</td>
 <td>Adding file from staging to commited area.</td>
</tr>
<tr><td>5</td>
<td>Git Stauts</td>
 <td>git status</td>
 <td>Show status of repository.</td>
</tr>
<tr><td>6</td>
<td>Git Log</td>
 <td>git log</td>
 <td>Show all the commits untill now.</td>
</tr>
<tr><td>7</td>
<td>Git Diff</td>
 <td>git diff</td>
 <td>Show difference between previous chnages and new chnages.</td>
</tr> 
<tr><td>8</td>
<td>Git Push</td>
 <td>git push origin branchName</td>
 <td>push file from local to remote system.</td>
</tr>
<tr><td>9</td>
<td>Git Add Multiple File</td>
 <td>git add .</td>
 <td>Added multiple file to staging area.</td>
</tr>
<tr><td>10</td>
<td>Git Branch</td>
 <td>git branch NewBranchName</td>
 <td>Create new branch.</td>
</tr>
<tr><td>11</td>
<td>Git Checkout</td>
 <td>git checkout BranchName </td>
 <td>It is used to switch the branch.</td>
</tr>
<tr><td>12</td>
<td>Git Checkout --</td>
 <td>git checkout -- BranchName </td>
 <td>All the file will revert to last step.</td>
</tr>
<tr><td>13</td>
<td>Git fetch</td>
 <td>git fetch origin branchName </td>
 <td>Access file from remote to loacal server.</td>
</tr>
<tr><td>14</td>
<td>Git Merge</td>
 <td>git merge branchName </td>
 <td>To merge created brach with Main/Master branch.</td>
</tr>
<tr><td>15</td>
<td>Git Clone</td>
 <td>git clone ssh/htmlpath </td>
 <td>to recover the delete file from local using remote server.</td>
</tr>
<tr><td>16</td>
<td>Git Delete Branch</td>
 <td>git branch branchName -d</td>
 <td>to delete branch.</td>
</tr>



 </table>

## BASIC BUILDING BLOCK OF WEB DEVELOPMENT
<img src="images/Saved Pictures/basicbuilding.png">

### SUMMARY TABLE
<table>
 <tr><th>Software Languages</th>
  <th>IP/Port</th>
    <th>HTTP Verbs/Codes</th>
    <th>Database</th>
    <th>Licences</th>
    
 </tr>
 <tr><td><ul type="disc"><li>JavaScript</li>
  <li> Php</li>
  <li>Python</li>
  </td>
  <td><li>Class A:0-127{Reserved for local System}</li>
 <li> Class B:128-191{Internet}</li>
 <li> Class C:192-223{local network}</li>
<li>Class D:224-239{Reserved}</li>
   <li> Class E:240-255{Reserved}</li>
 <li>Ports:0-1023{Reserved for local System}</li>
 <li> 1024-49150{Application port }</li>
 <li> 49151-65535{Open Port}</li>
</td>
  <td><li>Verbs:Get</li>
 <li>Post</li>
 <li>Put</li>
 <li>Delete</li>
 <li> Option</li>
 <li>Head</li>
 <li>Codes:100{Informational}</li>
 <li>200:{Success}</li>
 <li>300:{Migrational fro one loaction to another}</li>
 <li>400:{User Side Error}</li>
 <li> 500:{Server Side Error}</li>
  </td>
  <td>Relational:
   <li>MySql</li>
   <li>PostGres</li>
   <li>MariaDB</li>
   Non-Relational:
   <li>MongoDB</li>
   <li>Redis</li>
   <li>Cassandra</li>
  </td>
  <td><li>Apache 2.0</li>
   <li>MIT</li>
   <li>GPL{Used by Linux}</li>
   <li>BSD</li>
   <li>Mozzila</li>
  </td>
 
 </table>
<table>
 <tr><th>Cloud</th>
    <th>Web Ports</th>
    <th>Code Repository</th>
    <th>Project Management</th>
    <th>Git Dev Workflow</th>
    <th>Infrastructure</th>
 </tr>
  <td>
   <li>AWS</li>
   <li>Google</li>
   <li>Azure</li>
   <li>Linode</li>
   <li>Vulture</li>
   <li>Digital Ocean</li>
  </td>
  <td>
   <li>80{HTTP}</li>
   <li>443{HTTPS}</li>
  </td>
  <td>
   <li>Git Hub</li>
   <li>Git Lab</li>
   <li>Bite Bucket</li>
  </td>
  <td><li>JIRA</li>
   <li>Google Sheet</li>
   <li>Doc/Asara</li>
  </td>
  <td><li>Fature Branch</li>
   <li>Develope Branch</li>
   <li>Stage Branch</li>
   <li>Master Branch</li>
   </td>
  <td><li>Development(Dev)</li>
   <li>UAT/Staging</li>
   <li>Production</li>
  </td>
 </tr>
 </table>



# JAVASCRIPT

## JAVASCRIPT HISTORY AND BASIC
<img src="images/Saved Pictures/js.png">

### CONTROL STRUCTURE SUMMARY TABLE 
|Control Structure|Description|Syntax|
|---------|----------|--------------|
|If-else|If the specific value is true then it will get execute otherwise else condition will execute|if(condition){//execute if condition is true}else{//execute this if  condition is false}|
|For loop|execute code number of times|for(intialization;Condition;Increment/decrement){}|
|While loop|code execute till specific condition is true|while(condition){//code to be execute}|
|Do-While|code execute once then if the condition is true it will execute again|do{//code to be execute}while(condition);|
|Switch|used to choose the option|switch(expression){case n: break}|

### ARITHMETIC OPERATOR SUMMARY TABLE
|Operator|Description|Syntax|
|---------|----------|--------------|
|+|Additon If both operands are number type| a+b|
|+|Concatination if one of the operand is string type|a + "b"|
|-|Substraction|a - b|
|* |Multiplaction|a * b|
|/ |Division | a/b|
| %| Modulus gives remainder as output| a% b |
|==|Equal to|a == b|
|===| first check type of varaiable and then value gives output as boolean value|a === b|
|!=|Not Equal| a != b|
|>|Greater than|a > b|
|<|Less than|a < b|
|>=|Greater than equal to|a >= b|
|<=|Less than equal to|a <= b|

###  LOGICAL OPERATOR SUMMARY TABLE
<table>
        <tr>
                <th>Operator</th>
                <th>Description</th>
                <th>Synatx</th>
        </tr>
          <tr>
                <td>&&</td>
                <td>AND</td>
                <td>(a < 5 && b > 3)</td>
        </tr>
          <tr>
                <td>||</td>
                <td>OR</td>
                <td>(a == 5 || b == 5)</td>
        </tr>
          <tr>
                <td>!</td>
                <td>NOT</td>
                <td>!(a==b)</td>
        </tr>
</table>

### CONDITIONAL OPERATOR SUMMARY TABLE
|Operator|Description|Synatx|
|---------|----------|--------|
|? : |Ternary Operator|a?b:c|

## VARIABLES

JavaScript **variables** are **containers** for storing data.
Their are **_three_** variables in JavaScript.

1.**Var**
This variable is declare in ES5 script.It has functional scope.You can re-declare var many times.You can update variable.

**_Syntax: var VariableName = Value;_**

``` JAVASCRIPT
var a = 10;
var b = "myName";
var c = "true";
```
2.**Let**
This variable is declare in ES6 due to drowback of _var_ Variable.It has lexical scope.You cannot redeclare _let_ varibale. You can update it.

**_Synatx: let VariableName = Value;_**

``` v
let a = 5; 
a = 7;
let a =7; //will throw error

```

3.**Const**
This variable is declare in ES6 due to drowback of _var_ Variable.It has lexical scope.You cannot redeclare _const_ varibale. You cannot update it.

**_Synatx: const VariableName = Value;_**

``` JAVASCRIPT
const val= "Hi"; 
val = "Welcome to JavaScript"; // throw error
const val = "Hello";          //will throw error

```
### VARIABLES SUMMARY TABLE

|Variables|Syntax|Function|
|---------|--------|-------|
|var|var name ="Padma";|Have both local and global scope,can be redeclare and reassigned|
|let|let lastname ="Shaha"|lexical scope,cannot redeclare,can assign new value|
|const|const middelname ="Lokesh"|lexical scope.cannot redeclare ,cannot assign new value|

## DATATYPES

Datatypes is used to tell us the which type of variable or value is used.
Their are two types of datatypes in JavaScript.

**1.Premitive**(You cannot Change)
- Number
Number can be write in deciaml or without decimal.
``` JAVASCRIPT
var x = 5;
var y= 3.10;

if you see typeof these variable you will following type.
typeof (x);
Number
typeof (y);
Number
```
- String
Every value you write inside **""** will consider as String in JavaScript.

``` JAVASCRIPT
var x = "Sasha";
var y = "10"

typeof (x);
String
typeof (y);
String
```
- Boolean
In JavaScript boolean uses one of the two value - ** true** Or **false**
``` JAVASCRIPT
var a = true;
typeof (a);
Boolean
```
- Undefined
Variable declare without value or given value as undefined will have the value undefined.
``` JAVASCRIPT
var a;
var a = undefined;
typeof (a);
undefined
```
- Null
by default the type of null falls under Non-premitive object type.Used to give null value as input.

- Symbol(ES6)

**2.Non-Premitive**(You can Change)
- Object
In JS object are define using {} 
``` JAVASCRIPT
var student = { rollNo:"1",Name:"Taniska"};
typeof (student);
object

**To access the element from objects**
Synatx: NameOFObject.keyName
student.rollNo;
1
**To add new element in objects**
Synatx: NameOFObject.keyName = Value
student.class = "Sixth";
student ={rollNo:"1",Name:"Taniska",class = "Sixth"}
```
- Array
Their is no such concept of array in JS.array are kind of objects.written in [].
``` JAVASCRIPT
var Arraynum=[1,2,3,4,5];
console.log(Arraynum.length);
5
**Can Access array using index**
Arraynum[3];
4
**Can change value using index**
Arraynum[3]=10;
Arraynum = [1,2,3,10,5]

```
### DATATYPE SUMMARY TABLE

|Datatypes|Syntax|Used For|
|---------|--------|-------|
|Number|var num = 10;|Number can be write in deciaml or without decimal.|
|String|var str ="Sasha"|Every value you write inside **""** will consider as String in JavaScript.|
|Boolean|var bool = true;|In JavaScript boolean uses one of the two value - ** true** Or **false**|
|Undefined|var a = undefined; |Variable declare without value or given value as undefined will have the value undefined.|
|Null|var a = ;|by default the type of null falls under Non-premitive object type.|
|Object|var student = { rollNo:"1",Name:"Taniska"};|In JS object are define using {} |
|Array|var Arraynum=[1,2,3,4,5];|Array are kind of objects.written in [].|

## SCOPE
### FUNCTIONAL SCOPE

1.**Local Scope**
variable declare within function can only access by function.
``` JAVASCRIPT
Function local(){
var a =3;
console.log(a);
}
local();

---------
Output: 3
```

2.**global Scope**
variable declare outside the function can  access by  any function.
``` JAVASCRIPT
var a = 3;
function global()
{
var b = 10;
console.log(a);
console.log(a);
}
global();
-------------
output: 3
        10
```

3. **Lexical Scope** 
when varibale define inside any {} it is known as lexical scope

A.**Let**

1.**Local Scope**
variable declare within function can only access by function.
``` JAVASCRIPT
{                                 
let x = 10;                               
console.log(x);     //lexical/block scope
}                            

---------
Output: 10

----------------------------------------------

function local(){           //Functional Scope      
let a = 5;                                           
if(a)                                                
{                                                    
console.log(x);             //lexical scope
}                                                    
else{                       //lexical scope
}                                                    
}                                 
```
2.**global Scope**
variable declare outside the function can  access by  any function.
``` JAVASCRIPT
let y = 15;
{
let x = 10;   
console.log(x);
console.log(y);
}

-------------
output: 10
        15
------------------------------------------------------------
let y = 15;
function local(){                     //Functional Scope      
let a = 5;                                           
if(a)                                                
{                                                    
console.log(x);                       //lexical scope
}                                                    
else{ console.log(y);                 //lexical scope
}                                                    
}                                  
```
B.**Const**

1.**Local Scope**

variable declare within function can only access by function.
``` JAVASCRIPT
{                                 
const x = 10;                               
console.log(x);     //lexical/block scope
}                            

---------
Output: 10

--------------------------------------------------

function local(){           //Functional Scope      
const a = 5;                                           
if(a)                                                
{                                                    
console.log(x);             //lexical scope
}                                                    
else{                       //lexical scope
}                                                    
}                                 
```
2.**global Scope**
variable declare outside the function can  access by  any function.
``` JAVASCRIPT
const y = 15;
{
const x = 10;   
console.log(x);
console.log(y);
}

-------------
output: 10
        15
--------------------------------------------------------------------
const y = 15;
function local(){                     //Functional Scope      
const a = 5;                                           
if(a)                                                
{                                                    
console.log(x);                       //lexical scope
}                                                    
else{ console.log(y);                 //lexical scope
}                                                    
}                                  
```
## COPY BY VALUE OR COPY BY REFERENCE

A.**Copy By Value**

value will store in the initialize variable.Primitive datatype used as copy by value.

``` JAVASCRIPT
function square(x)
{
x= x* x;                         //x =100 and y=10(y remain same)
return x;
}
var y =10;                      // declare y and initalize its value 10
var result = sqaure(y);         // x=y the value of y will be copy to x
console.log(y);               //10   ---> no change
console.log(result);          //100 
-------------
output:100
```
**_If it is done by using call by reference then the value of y will also changed._**



B.**Copy by Reference**

value will store in the pointed location by initialize variable.Non-Primitive datatype used as copy by value.
``` JAVASCRIPT
var student = { Name:Tanu,**rollno:10**,class=5th,subject:Maths}    //typeof student is object.object are non-premitive datatype,and non premitive are call by reference
var newStudent = student;                                       //newStudent is pointing to student
newStudent.rollno = 20;
console.log(student);
console.log(newStudent);

-------------
output:
{ Name:Tanu,**rollno:20**,class=5th,subject:Maths}
{Name:Tanu,**rollno:20**,class=5th,subject:Maths}
```
**_From output it means if you do any changes in one filed and pass it reference to another the changes will display in another field also._**

## FUNCTIONS
A function is a block of code design to perfrom specific task.We can pass function as _parameter_ also.Pure Function dont modify values outside the function,Pure function also return same values passed as input.High order Function that takes function as parameter and returns function. 

**Properties of Function**
- Hoisting
- Overwrite
- Scope
- Act as a container
- objects
- Normal declareation using function name
- Function can be assigned to a variable.
- function can be return from another function
- function retuns a function

Synatx:
``` JAVASCRIPT
Function FunctionName(){
//code to be execute
}
```
**Function Returns**
when code reach to _return_ statement the function will stop executing.
Synatx:
``` JAVASCRIPT
var a = add(4,5);
function add(){
retun a+b;
}
-------------------
output:9
```
**IIFE(Imediatedly invoked function expression)**

Self executing function expression(SEF)

Syntax:
``` JAVASCRIPT
 ;(function(){
 //code to be execcuted
})();    //calling function
----------------------------
Example:

(function () {                         //anonymous function
                    var a = 10;        //variable declare and initialized
                    var b = 12;
                    function add(a,b)        // function defination
                      {
                          console.log(a + b);
                      }
                      add();                  //function calling
             })();                           //function calling
```
             
## FUNCTION CONSTRUCTOR AND PROTOTYPE

**Constructor is the pointer to the function that created the object.**
``` JAVASCRIPT
Function Person(name,exp){
    this.name = name;                           //this kewyword refers to object of class
    this.exp = exp;
}

var sasha = new Person("Sasha",2);                //created constructor
console.log(sasha.name,sasha.exp);

--------------------------------------
Output:
Sasha 2

```
**Prototype is an object .Acts as a method.Prototype is used to add new property to constructor function.**

``` JAVASCRIPT
Function Person(name,exp){
    this.name = name;                           //this kewyword refers to object of class
    this.exp = exp;
}
Person.prototype.age = "25";                      //adding new value using prototype object
var sasha = new Person("Sasha",2,25);                //created constructor
console.log(sasha.name,sasha.exp,this.age);

--------------------------------------
Output:
Sasha 2 25

```

**Built in Constructors**

1. var car  = new Object();                                                    //A new Object    object  
  
2. var name = new string();                                                   //A new String object  
      _Shuld not used_ 
      _Can be created directly example: var name = "sasha";_

3. var num  = new Number();                                                  //A new Number object 
   _Shuld not used_ 
   _Can be created directly example: var num = 1;_  

4.var yes  = new Boolean();                                                //A new Boolean object  
   _ not used_ 
   _Can be created directly example: var yes = false;_  

5. var arr  = new Array();                                                  //A new Array object  
   _Can be created directly example: var arr = [];_
   
6. var exp  = new RregExp();                                              //A new RegExp object
   _Can be created directly example: var exp = /[]/;_ 

7. var fun  = new Function();                                               //A new Function object 
   _Can be created directly example: var fun = Function(){};_  

8. var val  = new Date();                                                //A new Date object  
   _Can be access as example: val.getDate();_

9. Math () object dont use _new_ keyword.
   _Can be access as example: math.floor();_
   _Can be access as example: math.celi();_
  
 ### CONSTRUCTOR SUMMARY TABLE 
  |Built-In-Constructor|Synatx|
  |--------|---------|
  |Object| var car  = new Object(); |
  |String|var name = new string();  |
  |Number|var num  = new Number();  |
  |Boolean|var yes  = new Boolean();   |
  |Array|var arr  = new Array();   |
  |RregExp|var exp  = new RregExp();|
  |Function|var fun  = new Function(); |
  |Date| var val  = new Date();    |
  |Math ()|Math.floor();|
  
  
 ## ARRAY , OBJECTS, STRING METHODS
 
 1.**Array**
 ``` JAVASCRIPT
 Var names = ["Neha","Manish","Prapti","Ashish","Arjun","Soumya"];
 ```
 |Built in  Methods  | Syntax |Used For|
|------------------|---------|--------|
|Length()|names.[names.length]="Anushka"|easy way to add element at end of array|
|Push()|names.push("NewName")|To add element at end of array|
|Pop()|names.pop("soumya")|To remove element at end of array|
|Shift()|names.shift("soumya")|To remove element at begining of array|
|Unshift()|names.unshift("soumya")|To add element at begining of array|
|Concat()|var CreateNewVariable = names.concat(surname)|joins two array|
|forEach()|names.forEach("PassFunction")|To remove element at end of array|
|Map()|names.map("passFunction")|To add values in array|
|Filter()|names.filter("soumya")|To check wether it will pass the test or not|
|IndexOf()|names.indexOf("soumya")|To find index of element|
|Includes()|names.includes("soumya")|To check wheter element is present in array or not|
|Jion()|names.join("Delemiter(Example-->:,;,\,|,$,@,)")|To convert array to string|
|Slice()|names.slice("Can Pass element/Index of element")|To split an array|
|Splice()|names.pop("soumya")|To remove elemnts from array|
|IsArray()|Array.isArray("VariableName")|To check whether its array or not|


2.**Object**
Creation of object can be done by various type as shown below:
``` JAVASCRIPT
new object
object.create
var car = {}
````

 |Built in  Methods  | Syntax |Used For|
|------------------|---------|--------|
|Console.log|console.log(ObjectName.key Or ObjectName.key[reference]);|To read value from object|
|Key|var VariableName = Object.key(Name of Object);|How to calculate manys keys we have in object ?|
|freeze|ObjectName.freeze()|To stop changing values of object used freeze method to the object so that the new changes will not added to object.|
|assign|ObjectName.assign()|How to copy values of object to another ? used assign method for making copy of object|
|toString|ObjectName.toString() |How to convert object to string? toString() used to convert into string|


3.**String**

 |Built in  Methods  | Syntax |Used For|
|------------------|---------|--------|
|ToUpperCase|variableName.toUpperCase| convert the string into upper case|
|ToLowerCase|variableName.toLowerCase| convert the string into lower case|
|Split|variableName.split(Delimiters)| slipt the string using delimiter|
|Rplace|variableName.replace("Value want to replace","New value")| replaces a specified value with another value in a string|
|Trim|variableName.trim()| remove whitespace from both sides|
|SubString|variableName.substr()| extract the part from string and crreate new string|

## BUILT-IN-FUNCTION IN ES6
1.**SetTimeOut**
The code will run after some time.
``` JAVASCRIPT
const timefn= function(){
console.log("Printing after 2 seconds");
}
setTimeout(timefn,2000);
----------------------------
setTimeout(function(){
console.log("Printing after 2 seconds");
},2000);

```

2.**SetInterval**
It will execute in continous loop.To solve the problem of continuation of loop the new method is used named as clearInterval
``` JAVASCRIPT
setInterval(function(){
console.log("Printing after 2 seconds");
},2000);
```
----------------------
```
lwt counter = 0;
const timer = setInterval(function(){
console.log("Printing after 5 seconds");
if(counter > 5){
clearInterval(timer);
}
counter++;
},3000);
```
3.**ParseInt**
It converts any thing into integer number.It is very risky never used it in mathematical operation.
``` JAVASCRIPT
const num = 10.18;

let intNum = parseInt(num);
console.log(intNum)
------------------------
Output:10
```
4.**ParseFloat**
It parse through string and return float value.It is very risky never used it in mathematical operation.
``` JAVASCRIPT
const num = Sak9.2;

let intNum = parseInt(num);
console.log(intNum)
------------------------
Output:9.2
```
5.**JSON**
JSON is often used to send data overnetwork.
JSON format is same as object the only difference it used "" to write key  .Write using {"Key":"Value"}.
Example:
``` JAVASCRIPT
var person ={"firstName"="Radhika","firstName"="Radhika","age"=25};
```

###  BUILT-IN-FUNCTION IN ES6 SUMMARY TABLE

|Functions|Used For|Syntax|
|---------|--------|------|
|SetTimeOut|The code will run after some time.|setTimeout(param1,time)|
|SetInterval|It will execute in continous loop.|setInterval(param1,time)|
|ParseInt|It converts any thing into integer number.|parseInt(param)|
|ParseFloat|It parse through string and return float value.|parseFloat(param)|
|JSON|JSON is often used to send data overnetwork.|{"key":"Value"}|




