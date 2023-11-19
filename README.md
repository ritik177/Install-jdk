# Install-jdk for Ubuntu debian

<h1>1. Download Java</h1>

Open your web browser

Type URL: [https://www.oracle.com/java/technologies/downloads/](https://www.oracle.com/java/technologies/downloads/) to go to Oracle download page. This will lead you  JAVA JDK download page  

Click on button “ JDK download ” for Java SE update 4.  

Accept oracle license agreement

Find and click on the correct jdk  download link right for your operating system to download 

Save the file to disk 

<h3>Linux</h3>

x64 Debian Package  :    [](https://download.oracle.com/java/21/latest/jdk-21_linux-x64_bin.deb (sha256))https://download.oracle.com/java/21/latest/jdk-21_linux-x64_bin.deb(sha256)

<h1>2. Install Java </h1>

**$ sudo dpkg -i jdk-20_linux-x64_bin.deb**

**$ sudo update-alternatives --install /usr/bin/java java /usr/lib/jvm/jdk-20/bin/java 1**

**$ sudo update-alternatives --install /usr/bin/javac javac /usr/lib/jvm/jdk-20/bin/javac 1**


$ java --version

java 20 2023-07-17

Java(TM) SE Runtime Environment (build 20+36-1461)

Java HotSpot(TM) 64-Bit Server VM (build 20+36-1461, mixed mode, sharing)

$ javac --version

javac 20
