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

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_24_47](https://github.com/MaheshS03/EH-Ex-7/assets/128498431/93bb3a7a-a757-4d89-a9e0-caa962825b7f)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_26_14](https://github.com/MaheshS03/EH-Ex-7/assets/128498431/a753f6ec-dfcd-4d6f-ad06-946ef457b99d)

It displays the following menu and select 2 for Website Attack Vectors:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_26_42](https://github.com/MaheshS03/EH-Ex-7/assets/128498431/63d49b40-8590-4624-b95e-cdc00c3df876)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_27_19](https://github.com/MaheshS03/EH-Ex-7/assets/128498431/f62f3605-7e3a-4ab4-86f6-eb00a8f2c817)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_27_55](https://github.com/MaheshS03/EH-Ex-7/assets/128498431/63be6b14-429e-4027-b0e5-65a9ecad1975)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_28_55](https://github.com/MaheshS03/EH-Ex-7/assets/128498431/372f27cb-5c83-49e1-ad89-fd16c59412ba)

It shows the following screen in which the option Google can be selected:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_30_00](https://github.com/MaheshS03/EH-Ex-7/assets/128498431/f8f1db76-a3e9-4afd-b80d-83481a4036d3)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_30_38](https://github.com/MaheshS03/EH-Ex-7/assets/128498431/b62514e4-f6b9-4e33-9446-4509d88839cd)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![VirtualBox_kali-linux-2023 4-virtualbox-amd64_17_04_2024_10_38_46](https://github.com/MaheshS03/EH-Ex-7/assets/128498431/978e50d4-91e2-4e5a-8c2c-129c17295f70)

SET logs the information regarding the Google credentials:

![VirtualBox_Windows 7_17_04_2024_10_56_06](https://github.com/MaheshS03/EH-Ex-7/assets/128498431/d1b1619c-8680-4316-bda7-7fcf332e1f9d)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/MaheshS03/EH-Ex-7/assets/128498431/ddc586b3-2c2d-45fd-8f38-37b64ca03860)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
