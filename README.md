# Analysis-Ips-and-Hops
A short analysis of interact between ips and hops

## Prerequisites

For this project, you need a version of jre and jdk installed on your machine and the gephi, the graphos tool

Jdk - [Getting Jdk](https://www.oracle.com/java/technologies/javase-downloads.html)<br/>
Jre - [Getting Jre](https://www.java.com/pt_BR/download/)<br/>
Gephi - [Getting Gephi](https://gephi.org/)<br/>

## Using
### Using the java's code

After your has been install jdk and jre you need to follow this step to continue:<br/>

#### On windows:<br/>

  you need to add 3 variables of ambient:<br/>
  
    one named: "ClassPath" and on varible value you need to put the way for you folder, lib, inside java\jdk
    one named: "Path" and on varible value you need to put the way for you folder, bin, inside java\jdk
    one named: "Java_Home" and on varible value you need to put the way for you folder, jdk, inside java
    
  If these variables has been created yet you can jump this step<br/>    

  The next step will use for the two java's code.<br/>

  Now, after you download the code, compile it  by open your terminal, change the folder until becomes the <br/>
  code's folder use the comand "javac" and the name of the code with ".java" and one withe space between<br/>
  the command and the code's name.<br/>
  
  After does it, execute using the command "java" and the code's name without any extension, and the way for<br/>
  the archive with the ips from websites and the way for the new archive that this code will create and one<br/>
  with one space between all the parts of these instruction.<br/>
  
#### On Linux:<br/>

  Compile the code by open your terminal, change the folder until becomes the code's folder use the comand<br/>
  "javac" and the name of the code with ".java" and one withe space between the command and the code's name.<br/>
  
  After does it, execute using the command "java" and the code's name without any extension, and the way for<br/>
  the archive with the ips from websites and the way for the new archive that this code will create and one<br/>
  with one space between all the parts of these instruction.<br/>
  
#### Exemple of use:<br/>

##### For the GettingIps code<br/>

  javac GettingIps.java<br/>
  java GettingIps "D:\Pc\Documents\AllIps.txt" "D:\Pc\Documents\return.txt"<br/>
  
  use these commands but remenber change the name of the archives<br/>
  
##### For the ListClonnedIps code<br/>

  javac ListCloneIps.java<br/>
  java ListCloneIps "D:\Pc\Documents\ClonnedIps.txt"<br/>
  
  use these commands but remenber change the name of the archives<br/>
  
  
### Using Gephi tool

  before use the Gephi, you need to prepare the information for it, in execel, create a colum named id<br/>
  this colum need to has a crescent number begins by zero until the number of site's ips and after this collum<br/>
  create a collun named table who has all the ips one by one, one for line and save with the extension ".csv"<br/>
  
  now you can open the Gephi, create new project and import this archive with the nodes.<br/>
  
  create other archive for the edges by analysis the content build by the code and in one collum named source<br/>
  this collum will be content for the node who the ip is jumping, and another collum named target with the content<br/>
  of the node who is the target of the jumping.<br/>
  
  #### Exemple 
  
  Node.csv
  Edges.csv
  
  
  

  
