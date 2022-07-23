# How to insatll java on Linux
 
check if Java is already installed:
```
java -version
```
    

If Java is not currently installed, you’ll see the following output:
```
Output
Command 'java' not found
```

Execute the following command to install the default Java Runtime Environment (JRE), which will install the JRE from OpenJDK 11:

```
sudo apt install default-jre
```
    
The JRE will allow you to run almost all Java software.

Verify the installation with:
```
java -version
```
    
You’ll see output similar to the following:
```
openjdk version "11.0.15" 2022-04-19
OpenJDK Runtime Environment (build 11.0.15+10-Ubuntu-0ubuntu0.20.04.1)
OpenJDK 64-Bit Server VM (build 11.0.15+10-Ubuntu-0ubuntu0.20.04.1, mixed mode, sharing)
```

You may need the Java Development Kit (JDK) in addition to the JRE in order to compile and run some specific Java-based software. To install the JDK, execute the following command, which will also install the JRE:
```
sudo apt install default-jdk
```


Verify that the JDK is installed by checking the version of javac, the Java compiler:

```
javac -version
```

