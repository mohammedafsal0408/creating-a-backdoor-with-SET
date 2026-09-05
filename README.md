# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course


Developed : MOHAMMED AFSAL S

Reg no: 212225040247
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
## OUTPUT

<img width="797" height="883" alt="Screenshot 2026-09-05 001108" src="https://github.com/user-attachments/assets/39848d9f-19a7-48e5-b03e-2cde470895ee" />\

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="412" height="208" alt="image" src="https://github.com/user-attachments/assets/1bcc42fd-ed7a-42a4-8aa3-e75aa07aa7ef" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="471" height="283" alt="image" src="https://github.com/user-attachments/assets/8c57e526-0714-41c9-b954-39b2709fb02f" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1692" height="485" alt="image" src="https://github.com/user-attachments/assets/4801dce4-d05f-4441-a029-212af11b05a5" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT


<img width="783" height="481" alt="image" src="https://github.com/user-attachments/assets/42028d76-ae71-415a-9367-e339d78b6044" />


It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="802" height="872" alt="image" src="https://github.com/user-attachments/assets/d3f2aa8c-a49f-403d-8c03-0cde3f18e19f" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT


<img width="1180" height="185" alt="image" src="https://github.com/user-attachments/assets/59e1870c-6a61-4646-8833-e39ba1f3b979" />


In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT


<img width="1767" height="890" alt="image" src="https://github.com/user-attachments/assets/6ffb2794-6a88-49b5-a9b6-cb093d596fb7" />


SET logs the information regarding the Google credentials:
## OUTPUT

<img width="1674" height="450" alt="image" src="https://github.com/user-attachments/assets/247f8a12-fe35-4c13-b88b-2d22873504c7" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT



## COMMANDS


<img width="1845" height="727" alt="image" src="https://github.com/user-attachments/assets/cb575839-44be-4d51-9f00-03fa85942a80" />






## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
