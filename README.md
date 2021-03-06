# Analysis-Ips-and-Hops
A short analysis of interact between ips and hops

![Alt Text](https://user-images.githubusercontent.com/62123056/80319593-911ccb80-87e7-11ea-8388-bc3e85616484.gif)
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

  #### Preparing the information
  
  before use the Gephi, you need to prepare the information for it, in execel, create a colum named id<br/>
  this colum need to has a crescent number begins by zero until the number of site's ips and after this collum<br/>
  create a collun named table who has all the ips one by one, one for line and save with the extension ".csv"<br/>
  
  now you can open the Gephi, create new project and import this archive with the nodes.<br/>
  
  create other archive for the edges by analysis the content build by the code and in one collum named source<br/>
  this collum will be content for the node who the ip is jumping, and another collum named target with the content<br/>
  of the node who is the target of the jumping.<br/>
  
  #### Exemple 
  
  Node.csv<br/>
  Edges.csv<br/>
  
  #### Applying
  
  Now on the Gephi you can import all this information and based in these files we can filter by a lot of<br/>
  things, but in this program we will filter by the quantity of nodes who has the quantity of interacts<br/>
  with other nodes more than two.<br/>
  
 
  
  the result is:
  
  

  ![Alt Text](https://user-images.githubusercontent.com/62123056/80319703-43ed2980-87e8-11ea-9b68-586545bfb28b.gif)

  the content in this grafo is aboute all the nodes and edges collected 
  
  
 
  
  
   ![Alt Text](https://user-images.githubusercontent.com/62123056/80380845-7f363980-8876-11ea-9b64-8fd3ffb1ca1a.gif)
  
  the content in this grafo is aboute the grafo after been filtred for only nodes who has more than two jumps
  
  
  
  ## Conclusion
  
  This project can be used to find the path from your computer, or any other ip, to any other.<br/>
    
  Although it was not used for this, other applications for this project:<br/>
  
  #### TTL
  
  The project can be use to find a location on a network that has most often been ttl, using it<br/>
  the company can save money and time by finding the problem, especially on ttl, and solving it<br/>
  before it reaches customers.<br/>
  
  #### Change route
  
  By changin a simples line of the code, ListClonnedIps, we can has a return of the valocity by one hop<br/>
  for another, considering it, it can be used for change the route for the ip, by find a route who has a higher<br/>
  velocity of response.
