# Ubuntu-Termux
This is a script by which you can install Ubuntu in your termux application without rooted phone

# FULLY UPDATED TO UBUNTU 19.04 DISCO

Steps
<ol>
<li>Update termux: <code>apt-get update && apt-get upgrade -y</code></li>
<li>Install wget: <code>apt-get install wget -y</code></li>
<li>Install proot: <code>apt-get install proot -y</code></li>
<li>Install git: <code>apt-get install git -y</code></li>
<li>Go to HOME folder: <code>cd ~</code></li>
<li>Download script: <code>git clone https://github.com/JeelsBoobz/ubuntu-termux.git</code></li>
<li>Go to script folder: <code>cd ubuntu-termux</code></li>
<li>Give execution permission: <code>chmod +x installer</code></li>
<li>Run script: <code>./ubuntu.sh</code></li>
<li>Fix resolv.conf: <code>cp ~/ubuntu-termux/resolv.conf ~/ubuntu-termux/ubuntu-fs/etc/</code></li>
<li>Now just start ubuntu: <code>./start.sh</code></li>
</ol>
