```
NAME : THIRUMALAI K
REG NO : 212224240176
DEPT : AIML

```


# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

## OUTPUT :


![01](img/og1.png)

### The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT :

![02](img/02.png)

### It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT :


![03](img/03.png)

### The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT :

![04](img/04.png)

### The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT :

![05](img/05.png)

### It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT :

![06](img/06.png)

### It shows the following screen in which the option Google can be selected:

## OUTPUT :

![07](img/07.png)

### SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT :

![08](img/09.png)

### In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT :

![Screenshot 2025-05-09 185233](https://github.com/user-attachments/assets/3961ec97-c9a2-49e9-9ec8-099355564d38)



### SET logs the information regarding the Google credentials:
## OUTPUT :
![Alt text](img/10.png)

### SET logs the information in the xml file under /root/.set directory:

![Alt text](img/11.png)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
