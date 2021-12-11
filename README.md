<h1>CONQUEROR 1.0</h1>

<p><b>Project Title: </b>CONQUEROR</p>
<p><b>Project Type : </b>Operating System</p>
<p><b>Languages    : </b>C, x86_64 Assembly, Makefile, Shell Scripting</p>

<p><b>Features:</b></p>
<ul>
  <li>High Graphical User Interface</li>
  <li>Virtual Mouse Control</li>
  <li>Inbuilt App Store</li>
  <li>Complete Access of all Language Compilers</li>
  <li>Advance Voice Assistant with AI</li>
  <li>Next level AI Guide for individual User</li>
</ul>

<p><b>Layers:</b></p>
<ul>
  <li>User Space</li>
  <li>Kernel Space</li>
</ul>

<p><b>Architecture:</b></p>
<img src="https://github.com/mahendrasaikumargandham/conqueror-source-doc/blob/main/mahendra.jpg" width="500px" alt="" />

<details>
  <summary>Utility:</summary>
  <pre>
    Utility layer is nothing but the top of the user space (or) Operating System. It will display all the functionalities and operations performed in the pc.
  </pre>
</details>
<details>
  <summary>Shell:</summary>
  <pre>
    Shell is the software used to send the requests from Utility layer to Kernel space. All the commands entered into the shell will be sent to Hardware through kernel.
  </pre>
</details>
<details>
  <summary>Kernel:</summary>
  <pre>
    The main part of the OS which is the interface between Userspace and Hardware. It performs all the validations sent to hardware and resend the output to the userspace through shell.
  </pre>
</details>

<p><b>File System:</b></p>
<p>Similar to Linux File System</p>
<img src="https://github.com/mahendrasaikumargandham/conqueror-source-doc/blob/main/filesystem.png" width="800px" alt="" />
<p><b>Main directories:</b></p>
<ul>
  <li><b><p>/root</p></b></li>
  <li><b><p>/home</p></b></li>
  <li><b><p>/bin</p></b></li>
  <li><b><p>/sbin</p></b></li>
  <li><b><p>/mnt</p></b></li>
  <li><b><p>/etc</p></b></li>
<!--   <li><b><p>/lib</p></b></li> -->
  <li><b><p>/src</p></b></li>
</ul>

<details>
  <summary><b>1. /root</b></summary>
  <pre>
    /root is the home directory for root (administrator) users. There are 3 types of users basically. 
    <ul>
      <li>1. Root User (who has admin rights all over the pc)</li>
      <li>2. System User (who is permitted for specific tasks after the root user)</li>
      <li>3. Normal User (Third party users used to test and work in a virtual environment)</li>
    </ul>
  </pre>
</details>
<details>
  <summary><b>2. /home</b></summary>
  <pre>
    /home is the home directory for system users. /home contains all the system users data and directories. It has a seperate space in the operating system. It is the index page of the operating system.
  </pre>
</details>
<details>
  <summary><b>3. /bin</b></summary>
  <pre>
    /bin contains all the executable commands of the system user. 
  </pre>
</details>
<details>
  <summary><b>4. /sbin</b></summary>
  <pre>
    /sbin is the directory which contains all the executable commands of root user. /sbin contains all the executable commands including /bin.
  </pre>
</details>
<details>
  <summary><b>5. /mnt</b></summary>
  <pre>
    /mnt directory contains all the partitions of the hard disk information. we can later edit the partition for futher use.
  </pre>
</details>
<details>
  <summary><b>6. /etc</b></summary>
  <pre>
    /etc is the directory which contains all the executable commands and sensitive information like passwords, DNS configurations etc.., If we delete the /etc directory operting system will delete soon.
  </pre>
</details>
<details>
  <summary><b>7. /src</b></summary>
  <pre>
    /src is the directory which contains all the source code of the operating system. the user space is designed completely in this directory.
  </pre>
</details>


