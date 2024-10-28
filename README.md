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
![325268042-4d239d3f-f118-41a1-afa4-03710ba9a087](https://github.com/pradeepasri26/creating-a-backdoor-with-SET/assets/131433142/1ca49026-9435-470e-a42d-1434087f897a)
The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
![325268153-2ecd192b-7fbc-49e7-bed0-0ff6b7c5535f](https://github.com/pradeepasri26/creating-a-backdoor-with-SET/assets/131433142/34c489fc-51c7-414a-b33d-79bc4cd8291c)
It displays the following menu and select 2 for Website Attack Vectors:
![325268283-a872530f-de6f-4abf-9c70-4bd0ea144bab](https://github.com/pradeepasri26/creating-a-backdoor-with-SET/assets/131433142/1677f3a3-70f8-48c1-a2ad-00a6c4ca89b8)
The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![325268396-77f92910-e476-45e2-b693-a927c9703719](https://github.com/pradeepasri26/creating-a-backdoor-with-SET/assets/131433142/e0c76e8f-9408-4819-b4ef-3c57be0300ef)
The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![325268557-63ea173f-f972-497a-826a-54f1a2ea1cc2](https://github.com/pradeepasri26/creating-a-backdoor-with-SET/assets/131433142/2ea86427-f0ac-4d28-b7ec-b7b07b060e0b)
It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![325268753-b980a8bc-26b6-4558-9acf-c5bcb1c27890](https://github.com/pradeepasri26/creating-a-backdoor-with-SET/assets/131433142/36fd6b02-6a93-49e8-84a2-890d197789cb)
It shows the following screen in which the option Google can be selected:
![325268874-8890235b-4895-4590-9e92-d296679eea5c](https://github.com/pradeepasri26/creating-a-backdoor-with-SET/assets/131433142/91865649-580d-433e-9cc7-a7c03d86319c)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![325268959-11c90951-32b4-4bb2-9645-0dbb67f93ad7](https://github.com/pradeepasri26/creating-a-backdoor-with-SET/assets/131433142/57f2e4fe-c91a-4533-b614-08007f57707e)
In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![325269129-f71932e1-23ed-417f-a7e5-7d2d1180179a](https://github.com/pradeepasri26/creating-a-backdoor-with-SET/assets/131433142/886311dd-40f4-4821-99d0-879523e494a7)
SET logs the information regarding the Google credentials:
![325269237-b7ef7748-a10c-4314-a7c6-e83e9e0e284b](https://github.com/pradeepasri26/creating-a-backdoor-with-SET/assets/131433142/c8a61350-3ab8-4d00-9b08-c5143f9d7b30)
SET logs the information in the xml file under /root/.set directory:
![Uploading 325269417-793bc8e0-6b64-495d-8b49-0359b9669581.png…]()

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
