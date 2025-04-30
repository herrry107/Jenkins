# Jenkins install step
1) Git: Download->Install
2) Java: Download->Configure
3) Maven: Download->Configure
4) Jenkins: Download->Install->Configure

# Git

Download git from url or from google 
<pre><code>https://git-scm.com/downloads</code></pre>

after download and install
<pre><code>
git --version
git config --global user.name ""    #pass your name
git config --global user.email ""   #pass your mail id
git config --global --list          #show name and mail id
</code></pre>

# Java

Download JDK for all or from google 
<pre><code>https://www.oracle.com/in/java/technologies/downloads/</code></pre>

Download JDK24 for debian x64 or from google
<pre><code>
wget https://download.oracle.com/java/24/latest/jdk-24_linux-x64_bin.deb   #download from wget
sudo dpkg -i jdk-24_linux-x64_bin.deb      #package name
java --version
</code></pre>

**after download and install add to path in windows**

# Maven

**WINDOWS**
<pre><code>
https://maven.apache.org/  #Download binary zip archieve file
#extract files to C\Devtools
</code></pre>
Go to C:\Devtools\Apache-Maven and copy path and add to environment variables
Go to C:\Devtools\Apache-Maven\bin and copy path and add to environment variables

**Linux**
<pre><code>
sudo apt install maven
mvn --version
</code></pre>

# Jenkins

<pre><code>https://www.jenkins.io/download/    #download jenkins from official website</code></pre>

after installation 
<pre><code>systemctl start jenkins    #by default automatic start but sometime you have to do</code></pre>

open jenkins on any browser by localhost:8080 and it ask to generate new password 
<pre><code>localhost:8080  #jenkins default port 8080</code></pre>
