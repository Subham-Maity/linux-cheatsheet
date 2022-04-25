
# linux Cheat Sheet For Beginners

# Writer Intro
I am **Subham Maity.**

I love Programming. One of the aims I had when I started ```CodeXam``` was to make learning programming easy.**

**At ```CodeXam```, we ask ourselves one question every day: "How do we create awesome learning experiences?"**

### Help us improve this guide - Fork, Pull Requests, Shares and Likes are recommended!
## linux Chapters
*******
* [Basic Linux commands](#basic-linux-commands)
* [File Permission commands](#file-permission-commands)
* [Environment Variables command](#environment-variables-command)
* [User management commands of linux](#user-management-commands-of-linux)
* [Networking command](#networking-command)
* [Process command](#process-command)
* [VI Editing Commands](#vi-editing-commands)


# Basic Linux commands
<table class="table table-striped">****
<thead>
<tr>
<th>Command</th>
<th>Description</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td><code>ls</code></td>
<td>Lists all files and directories in the present working directory</td>
</tr>
<tr>
<td><code>ls -R</code></td>
<td>Lists files in sub-directories as well</td>
</tr>
<tr>
<td><code>ls -a</code></td>
<td>Lists hidden files as well</td>
</tr>
<tr>
<td><code>ls -al</code></td>
<td>Lists files and directories with detailed information like permissions,size, owner, etc.</td>
</tr>
<tr>
<td><code>cd or cd ~</code></td>
<td>Navigate to HOME directory</td>
</tr>
<tr>
<td><code>cd ..</code></td>
<td>Move one level up</td>
</tr>
<tr>
<td><code>cd</code></td>
<td>To change to a particular directory</td>
</tr>
<tr>
<td><code>cd /</code></td>
<td>Move to the root directory</td>
</tr>
<tr>
<td><code>cat &gt; filename</code></td>
<td>Creates a new file</td>
</tr>
<tr>
<td><code>cat filename</code></td>
<td>Displays the file content</td>
</tr>
<tr>
<td><code>cat file1 file2 &gt; file3</code></td>
<td>Joins two files (file1, file2) and stores the output in a new file (file3)</td>
</tr>
<tr>
<td><code>mv  file "new file path"</code></td>
<td>Moves the files to the new location</td>
</tr>
<tr>
<td><code>mv filename new_file_name</code></td>
<td>Renames the file to a new filename</td>
</tr>
<tr>
<td><code>sudo</code></td>
<td>Allows regular users to run programs with the security privileges of the superuser or root</td>
</tr>
<tr>
<td><code>rm filename</code></td>
<td>Deletes a file</td>
</tr>
<tr>
<td><code>man</code></td>
<td>Gives help information on a command</td>
</tr>
<tr>
<td><code>history</code></td>
<td>Gives a list of all past commands typed in the current terminal session</td>
</tr>
<tr>
<td><code>clear</code></td>
<td>Clears the terminal</td>
</tr>
<tr>
<td><code>mkdir directoryname</code></td>
<td>Creates a new directory in the present working directory or a at the specified path</td>
</tr>
<tr>
<td><code>rmdir</code></td>
<td>Deletes a directory</td>
</tr>
<tr>
<td><code>mv</code></td>
<td>Renames a directory</td>
</tr>
<tr>
<td><code>pr -x</code></td>
<td>Divides the file into x columns</td>
</tr>
<tr>
<td><code>pr -h</code></td>
<td>Assigns a header to the file</td>
</tr>
<tr>
<td><code>pr -n</code></td>
<td>Denotes the file with Line Numbers</td>
</tr>
<tr>
<td><code>lp -nc , lpr c</code></td>
<td>Prints &#8220;c&#8221; copies of the File</td>
</tr>
<tr>
<td><code>&nbsp;lp-d lp-P<br />
</code></td>
<td>Specifies name of the printer</td>
</tr>
<tr>
<td><code>apt-get<br />
</code></td>
<td>Command used to install and update packages</td>
</tr>
<tr>
<td><code>mail -s 'subject'<br />
-c 'cc-address' </code><br />
<code> -b 'bcc-address'<br />
'to-address'<br />
</code></td>
<td>Command to send email</td>
</tr>
<tr>
<td><code>mail -s "Subject"<br />
to-address &lt; Filename<br />
</code></td>
<td>Command to send email with attachment</td>
</tr>
</tbody>
</table>
<div class='code-block code-block-2' style='margin: 8px 0; clear: both;'>
<!-- Async AdSlot 1 for Ad unit 'guru99.com_728x90' ### Size: [[728,90],[468,60],[300,250]] -->
<!-- Adslot's refresh function: googletag.pubads().refresh([gptadslots[0]]) -->
<style>
@media(max-width: 499px) { .videocontentmobile {min-height: 280px; } }
@media only screen and (min-width: 500px) and (max-width: 1023px){.videocontentmobile {min-height: 100px;}}
@media(min-width: 1024px) { .videocontentmobile {min-height: 250px; } }
</style>
<div class="videocontentmobile">
<div id='div-gpt-ad-9092914-1'>
  <script type='text/javascript'>              
    if (typeof(pubwise) != 'undefined' && pubwise.enabled === true) {
      pubwise.que.push(function() {              
          pubwise.renderAd('div-gpt-ad-9092914-1');
      });
    }else{
      googletag.cmd.push(function () {                    
        googletag.display('div-gpt-ad-9092914-1');
        googletag.pubads().refresh([gptadslots['div-gpt-ad-9092914-1']]);          
      });
    }
  </script>
</div>

</div>
<!-- End AdSlot 1 -->
</div>

# File Permission commands
<table class="table table-striped">
<thead>
<tr>
<th>Command</th>
<th>Description</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td><code>ls -l</code></td>
<td>to show file type and access permission</td>
</tr>
<tr>
<td><code>r</code></td>
<td>read permission</td>
</tr>
<tr>
<td><code>w</code></td>
<td>write permission</td>
</tr>
<tr>
<td><code>x</code></td>
<td>execute permission</td>
</tr>
<tr>
<td><code>-=</code></td>
<td>no permission</td>
</tr>
<tr>
<td><code>Chown user</code></td>
<td>For changing the ownership of a file/directory</td>
</tr>
<tr>
<td><code>Chown user:group filename</code></td>
<td>change the user as well as group for a file or directory</td>
</tr>
</tbody>
</table>

# Environment Variables command

<table class="table table-striped">
<thead>
<tr>
<th>Command</th>
<th>Description</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td><code>echo $VARIABLE</code></td>
<td>To display value of a variable</td>
</tr>
<tr>
<td><code>env</code></td>
<td>Displays all environment variables</td>
</tr>
<tr>
<td><code>VARIABLE_NAME= variable_value</code></td>
<td>Create a new variable</td>
</tr>
<tr>
<td><code>Unset</code></td>
<td>Remove a variable</td>
</tr>
<tr>
<td><code>export Variable=value</code></td>
<td>To set value of an environment variable</td>
</tr>
</tbody>
</table>

# User management commands of linux

<table class="table table-striped">
<thead>
<tr>
<th>Command</th>
<th>Description</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td><code>sudo adduser username</code></td>
<td>To add a new user</td>
</tr>
<tr>
<td><code>sudo passwd -l 'username'</code></td>
<td>To change the password of a user</td>
</tr>
<tr>
<td><code>sudo userdel -r 'username'</code></td>
<td>To remove a newly created user</td>
</tr>
<tr>
<td><code>sudo usermod -a -G GROUPNAME USERNAME</code></td>
<td>To add a user to a group</td>
</tr>
<tr>
<td><code>sudo deluser USER GROUPNAME</code></td>
<td>To remove a user from a group</td>
</tr>
<tr>
<td><code>finger</code></td>
<td>Shows information of all the users logged in</td>
</tr>
<tr>
<td><code>finger username</code></td>
<td>Gives information of a particular user</td>
</tr>
</tbody>
</table>
<div class='code-block code-block-3' style='margin: 8px 0; clear: both;'>
<!-- Async AdSlot 2 for Ad unit 'guru99.com_728x90' ### Size: [[728,90],[468,60],[300,250]] -->
<!-- Adslot's refresh function: googletag.pubads().refresh([gptadslots[1]]) -->

<style>
@media(max-width: 499px) { .content2 {min-height: 100px !important; }}
@media(min-width: 500px) { .content2 {min-height: 91px !important; } }
</style>
<div class="content2">
<div id='div-gpt-ad-9092914-2' >
  <script type='text/javascript'>              
    if (typeof(pubwise) != 'undefined' && pubwise.enabled === true) {
      pubwise.que.push(function() {              
          pubwise.renderAd('div-gpt-ad-9092914-2');
      });
    }else{
      googletag.cmd.push(function () {                    
        googletag.display('div-gpt-ad-9092914-2');
        googletag.pubads().refresh([gptadslots['div-gpt-ad-9092914-2']]);          
      });
    }
  </script>
</div>
</div>
<!-- End AdSlot 2 -->
</div>

# Networking command

<table class="table table-striped">
<thead>
<tr>
<th>Command</th>
<th>Description</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td><code>SSH username@ip-address or hostname</code></td>
<td>login into a remote Linux machine using SSH</td>
</tr>
<tr>
<td><code>Ping hostname="" or =""</code></td>
<td>To ping and Analyzing network and host connections</td>
</tr>
<tr>
<td><code>dir</code></td>
<td>Display files in the current directory of a remote computer</td>
</tr>
<tr>
<td><code>cd "dirname"</code></td>
<td>change directory to &#8220;dirname&#8221; on a remote computer</td>
</tr>
<tr>
<td><code>put file</code></td>
<td>upload &#8216;file&#8217; from local to remote computer</td>
</tr>
<tr>
<td><code>get file</code></td>
<td>Download &#8216;file&#8217; from remote to local computer</td>
</tr>
<tr>
<td><code>quit</code></td>
<td>Logout</td>
</tr>
</tbody>
</table>

# Process command

<table class="table table-striped">
<thead>
<tr>
<th>Command</th>
<th>Description</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td><code>bg</code></td>
<td>To send a process to the background</td>
</tr>
<tr>
<td><code>fg</code></td>
<td>To run a stopped process in the foreground</td>
</tr>
<tr>
<td><code>top</code></td>
<td>Details on all Active Processes</td>
</tr>
<tr>
<td><code>ps</code></td>
<td>Give the status of processes running for a user</td>
</tr>
<tr>
<td><code>ps PID</code></td>
<td>Gives the status of a particular process</td>
</tr>
<tr>
<td><code>pidof</code></td>
<td>Gives the Process ID (PID) of a process</td>
</tr>
<tr>
<td><code>kill PID</code></td>
<td>Kills a process</td>
</tr>
<tr>
<td><code>nice</code></td>
<td>Starts a process with a given priority</td>
</tr>
<tr>
<td><code>renice</code></td>
<td>Changes priority of an already running process</td>
</tr>
<tr>
<td><code>df</code></td>
<td>Gives free hard disk space on your system</td>
</tr>
<tr>
<td><code>free</code></td>
<td>Gives free RAM on your system</td>
</tr>
</tbody>
</table>
<div class='code-block code-block-4' style='margin: 8px 0; clear: both;'>
<style>
@media(max-width: 1023px) {.content61 {min-height: 91px !important; }}
@media(min-width: 1024px) {.content61 {min-height: 280px !important; }}
</style>
<div class='content61'>
<div id='div-gpt-ad-9092914-6'>
    <script type='text/javascript'>              
      if (typeof(pubwise) != 'undefined' && pubwise.enabled === true) {
        pubwise.que.push(function() {              
            pubwise.renderAd('div-gpt-ad-9092914-6');
        });
      }else{
        googletag.cmd.push(function () {                    
          googletag.display('div-gpt-ad-9092914-6');
          googletag.pubads().refresh([gptadslots['div-gpt-ad-9092914-6']]);          
        });
      }
    </script>
  </div>
</div>
</div>

# VI Editing Commands
<table class="table table-striped">
<thead>
<tr>
<th>Command</th>
<th>Description</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td><code>i</code></td>
<td>Insert at cursor (goes into insert mode)</td>
</tr>
<tr>
<td><code>a</code></td>
<td>Write after cursor (goes into insert mode)</td>
</tr>
<tr>
<td><code>A</code></td>
<td>Write at the end of line (goes into insert mode)</td>
</tr>
<tr>
<td><code>ESC</code></td>
<td>Terminate insert mode</td>
</tr>
<tr>
<td><code>u</code></td>
<td>Undo last change</td>
</tr>
<tr>
<td><code>U</code></td>
<td>Undo all changes to the entire line</td>
</tr>
<tr>
<td><code>o</code></td>
<td>Open a new line (goes into insert mode)</td>
</tr>
<tr>
<td><code>dd</code></td>
<td>Delete line</td>
</tr>
<tr>
<td><code>3dd</code></td>
<td>Delete 3 lines</td>
</tr>
<tr>
<td><code>D</code></td>
<td>Delete contents of line after the cursor</td>
</tr>
<tr>
<td><code>C</code></td>
<td>Delete contents of a line after the cursor and insert new text. Press ESC key to end insertion.</td>
</tr>
<tr>
<td><code>dw</code></td>
<td>Delete word</td>
</tr>
<tr>
<td><code>4dw</code></td>
<td>Delete 4 words</td>
</tr>
<tr>
<td><code>cw</code></td>
<td>Change word</td>
</tr>
<tr>
<td><code>x</code></td>
<td>Delete character at the cursor</td>
</tr>
<tr>
<td><code>r</code></td>
<td>Replace character</td>
</tr>
<tr>
<td><code>R</code></td>
<td>Overwrite characters from cursor onward</td>
</tr>
<tr>
<td><code>s</code></td>
<td>Substitute one character under cursor continue to insert</td>
</tr>
<tr>
<td><code>S</code></td>
<td>Substitute entire line and begin to insert at the beginning of the line</td>
</tr>
<tr>
<td><code>~</code></td>
<td>Change case of individual character</td>
</tr>
</tbody>
