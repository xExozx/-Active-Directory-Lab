

## Objective


The Active Directory project aimed to establish a controlled environment for simulating and detecting cyber attacks on splunk. Setting up an Active Directory (home lab) that includes Splunk and Kali Linux. Explored how a domain environment works, learned how to ingest events to a SIEM and generate telemetry related to attacks seen in the wild that would help me detect them in the future.
### Skills Learned


- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used


- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps
![Active Directory Project](https://github.com/user-attachments/assets/df7bacb4-e6e3-4893-8a6e-ef5acd6107f6)

Ref 1: Network Diagram

<img width="1112" height="897" alt="downlaoding all vms" src="https://github.com/user-attachments/assets/46297210-2b5b-46e5-83aa-54c42992ad60" />

Ref 2: Downloaded all VM's. Windows 10, Windows server "Active Directory", Kali Linux, Ubuntu "Splunk.

<img width="798" height="598" alt="upgrade repository" src="https://github.com/user-attachments/assets/ccffed0f-a086-4b1a-bed6-5dc9d6bb550b" />

Ref 3: Upgraded repository for splunk.

<img width="656" height="590" alt="Error when opening windows server" src="https://github.com/user-attachments/assets/4b6fef52-1870-4ba3-9b1e-0af04286a918" />

Ref 4: Was running into an error that would not open my windows server VM.

<img width="1095" height="633" alt="Fix for E_FAIL" src="https://github.com/user-attachments/assets/62dea484-9e9e-4961-8d62-8013b15e31d5" />

Ref 5: Fixed the error by opening my cmd on my main computer with administrator privilage and typing "bcdedit /set hypervisorlaunchtype off".

<img width="795" height="597" alt="Upgrading repository" src="https://github.com/user-attachments/assets/6dc3ca4c-e51d-4b2e-9c2b-58cc115f5874" />

Ref 6: Upgrade complete for splunk repository.

<img width="953" height="936" alt="Creating AD Network" src="https://github.com/user-attachments/assets/e772f46f-be25-40c9-acb3-7236ba0473d7" />

Ref 7: Creating a "Active Directory" NAT network for all of my VMs. 

<img width="970" height="635" alt="Putting all Networks into AD Network Enviroment" src="https://github.com/user-attachments/assets/1e4a9eeb-f5b9-41c5-abbe-754d762751ec" />

Ref 8: Adding all vm's to the NAT network.

<img width="842" height="757" alt="setting up static ip for splunk" src="https://github.com/user-attachments/assets/0f226f58-8416-444a-8abf-7a3c9a1bdbc5" />

Ref 9: Setting up static ip by for splunk by going into "sudo nano /etc/netplan/00-installer-config.yami".

<img width="841" height="753" alt="changing splunk ip address" src="https://github.com/user-attachments/assets/c95c824c-c837-4e09-be42-f5f4d0ba7895" />

Ref 10: Changed the ip address to 192.168.10.10/24 as shown in the diagram.

<img width="1281" height="122" alt="changed splunk ip address" src="https://github.com/user-attachments/assets/2875ec2a-90bf-44f0-8e57-6df650379226" />

Ref 11: "ip a" is now showing our ip address as 192.168.10.10/24.

<img width="1277" height="328" alt="valid connection" src="https://github.com/user-attachments/assets/5bbe058a-f69e-4225-a346-22a793fddd88" />

Ref 12: Checking connectivity pinging to google.com.

<img width="1280" height="273" alt="adding vboxsf user and installing vboxsf" src="https://github.com/user-attachments/assets/088b44c9-bcc8-46fc-82d3-36d3c53750a2" />

Ref 13: Installed guest add-ons for virtual box.

<img width="1277" height="390" alt="added user to vboxsf group" src="https://github.com/user-attachments/assets/b0e7d4db-76f6-4b55-aa31-2fd0e9a9cbcd" />

Ref 14: Added user to vboxsf group.

<img width="1280" height="63" alt="made new directory called share" src="https://github.com/user-attachments/assets/457253b0-8da9-4acd-b371-bb5f29680992" />

Ref 15: Created a new directory called share.

<img width="1280" height="390" alt="Mounted share folder onto directory called share" src="https://github.com/user-attachments/assets/3241e655-4b63-4240-888f-446547a3d430" />

Ref 16: Mounting my shared folder into directory called share.

<img width="862" height="60" alt="installing splunk" src="https://github.com/user-attachments/assets/ad7d5bdf-871b-4db4-8715-87921b3ce9a5" />

Ref 17: Installed splunk installer

<img width="1258" height="337" alt="changed into splunk directory and all users are now under splunk" src="https://github.com/user-attachments/assets/2f3ff47e-ec9f-4cb9-99c6-54a8bacdb9c2" />

Ref 18: Changed into directory and all users are now under splunk.

<img width="1027" height="35" alt="changed into splunk as a user and into bin for the binary that splunk can use" src="https://github.com/user-attachments/assets/18b24a50-f484-4bcc-a39f-3dd36edb20eb" />

Ref 19: Changed into splunk as a user and into bin for the binary that splunk can use.

<img width="1262" height="828" alt="splunk installed " src="https://github.com/user-attachments/assets/eab4e6f1-3916-4ded-80b2-5d92549aae79" />

Ref 20: Installed splunk.

<img width="1262" height="135" alt="command to make splunk start up whenever machine reboots" src="https://github.com/user-attachments/assets/826af597-e909-4915-ae01-04fccd5499f2" />

Ref 21: Splunk starts up everytime my vm reboots.

<img width="1022" height="866" alt="changing windows10 ip address " src="https://github.com/user-attachments/assets/d2189aa6-6841-492e-bbc2-5f46576266f1" />

Ref 22: Changed my windows10 ip address to the same as in the network diagram.

<img width="1018" height="862" alt="confiriming change in ip address for windows 10" src="https://github.com/user-attachments/assets/0e32461c-8d27-484b-909f-6d50646858aa" />

Ref 23: Confirming the change in ip address for windows10.

<img width="1017" height="867" alt="downloaded splunk universal fowarder" src="https://github.com/user-attachments/assets/172b3a39-707d-4c83-8b97-13980af10e96" />

Ref 24: Downloaded splunk universal fowarder into windows10.

<img width="1017" height="726" alt="downloaded sysmon" src="https://github.com/user-attachments/assets/e96e3257-200b-4635-ac65-ffe17295e6e5" />

Ref 25: Downloaded Sysmon into windows10.

<img width="1018" height="860" alt="DOWNLOADING SYSMON CONFIG" src="https://github.com/user-attachments/assets/f9dd507a-a49b-436d-998f-05d959a7e141" />

Ref 26: Downloaded the sysmon config by olaf.

<img width="762" height="98" alt="installed sysmon through powershell admin" src="https://github.com/user-attachments/assets/998cd1a0-2b1d-4307-a835-c61f00a96b6f" />

Ref 27: Installed sysmon through powershell as admin.

<img width="752" height="517" alt="instructing splunk fowarder to push events related to applications security system and sysmon" src="https://github.com/user-attachments/assets/ed9a9230-be59-4a27-93db-0afee99844aa" />

Ref 28: Instructing fowarder to push events related to application, security, system, and sysmon.

<img width="782" height="587" alt="put input conf under local file" src="https://github.com/user-attachments/assets/609f9df5-98d4-4d6c-80bd-70114be89ef6" />

Ref 29: Placed input config under local file.

<img width="800" height="591" alt="making it local system to collect logs" src="https://github.com/user-attachments/assets/13e29cbd-fe92-4e31-8fdf-1b562e9eac2f" />

Ref 30: Making service to local system to collect logs.

<img width="886" height="725" alt="restarting after making splunk local" src="https://github.com/user-attachments/assets/0c4e07b6-fb09-48be-8bf8-f9428ca832b7" />

Ref 31: Restarting after making splunk local.

<img width="1017" height="866" alt="making new index for endpoint" src="https://github.com/user-attachments/assets/16ec77cf-9479-40ba-94bf-20b764e13388" />

Ref 32: Making a new index for endpoint.

<img width="1020" height="857" alt="enabling splunk server to recieve data" src="https://github.com/user-attachments/assets/35a3365a-09ac-4d47-95d0-31ee5ea6c818" />

Ref 33: Enabling splunk server to recieve data.

<img width="1013" height="870" alt="receiving data from index endpoint, host is target-pc, sources from application security system sysmon" src="https://github.com/user-attachments/assets/3277cddd-b6e6-4a89-bbd5-8190b5b4fe22" />

Ref 34: Receiving data from index endpoint. The host is target-pc and is sending sources from application, security, system, and sysmon.

<img width="1017" height="865" alt="changing ip of server to the same one as the diageram" src="https://github.com/user-attachments/assets/389eb3b1-0b21-4076-8eac-4d74038119eb" />

Ref 35: Changing ip of windows server to the same as the one on the diagram. 192.168.10.7.

<img width="1017" height="862" alt="pinging splunk server" src="https://github.com/user-attachments/assets/0bb2932d-87b0-4ef2-bbc4-6d055bf77caf" />

Ref 36: Pinging splunk server to see connectivity.

<img width="1017" height="872" alt="installing active directory" src="https://github.com/user-attachments/assets/a596f30e-44fd-4f24-a6cb-243ebd668101" />

Ref 37: Installing active directory.

<img width="1017" height="865" alt="installation success" src="https://github.com/user-attachments/assets/f11e0f70-5267-46f4-b00e-977fc3f6c84c" />

Ref 38: Installation successfull.

<img width="1017" height="866" alt="making domain controller" src="https://github.com/user-attachments/assets/347c00a7-391e-41db-9bad-e70917cf727e" />

Ref 39: Making domain controller in AD.

<img width="1016" height="868" alt="indicates that we installed AADS and promoted our server to our domain controlelr" src="https://github.com/user-attachments/assets/1a2390f5-60e5-444d-8bbe-225a29872e75" />

Ref 40: Screen indicated that we installed AADS and promoted my server to my domain controller.

<img width="1015" height="867" alt="made new orginizational unit" src="https://github.com/user-attachments/assets/9d2b5970-1178-4c04-8bde-d03798413a28" />

Ref 41: Made a new orginizational unit.

<img width="1018" height="867" alt="made new user in IT unit" src="https://github.com/user-attachments/assets/f8ff977b-1960-4348-80b0-f8f24a286846" />

Ref 42: Made a new user in the IT unit.

<img width="1017" height="865" alt="making a second orginizational unit" src="https://github.com/user-attachments/assets/6a46a472-51b4-49ae-ba80-18371ea49fc0" />

Ref 43: Making a second orginizational unit.

<img width="1016" height="865" alt="made 2 users into 2 units" src="https://github.com/user-attachments/assets/d773f83c-b508-438f-b30e-5b6135606bc4" />

Ref 44: Made 2 users into 2 units.

<img width="1017" height="865" alt="trying to add windows 10 to active directory EXOZ" src="https://github.com/user-attachments/assets/843117fa-6127-4f7c-bc15-d2817ed747b9" />

Ref 45: Error when trying to add windows 10 to active directory EXOZ.

<img width="1020" height="862" alt="changing dns server to domain server" src="https://github.com/user-attachments/assets/b7d1d5b9-5f68-4004-a9c2-580594e49b2e" />

Ref 46: Changed my dns server to the domain server.

<img width="1018" height="863" alt="dns server is pointing to our domain controller" src="https://github.com/user-attachments/assets/be9ff716-7a37-4b18-8be5-d9c57089953c" />

Ref 47: Using ipconfig /all and now it is pointing to my domain controller.

<img width="1016" height="866" alt="windows 10 joining exoz domain" src="https://github.com/user-attachments/assets/ef57783f-8e15-47ab-933c-8a299f68e70f" />

Ref 48: Now windows 10 joined Exoz domain.

<img width="1022" height="868" alt="logging into windows 10 as a domain user" src="https://github.com/user-attachments/assets/2d5b79ce-5f8e-4ac6-83a4-f1d50ea81314" />

Ref 49: Logging into windows 10 as a domain user.

<img width="710" height="572" alt="configured kali linux ipv4" src="https://github.com/user-attachments/assets/068e2008-89df-4683-9574-6cbfa43d7449" />

Ref 50: Configured my kali linuz ipv4 to my ip address as per my diagram.

<img width="637" height="458" alt="ip a showing our ip address" src="https://github.com/user-attachments/assets/2d52effd-3304-426f-8ed4-e8bb83a4b5ba" />

Ref 51: Using "ip a" to show my ip address as the same as diagram ip.

<img width="712" height="570" alt="updating and upgrading kali" src="https://github.com/user-attachments/assets/5aba33a8-b3e0-4868-acf3-8c296cd1281c" />

Ref 52: Using "sudo apt-get update && sudo apt-get upgrade -y" to update and upgrade kali linux.

<img width="715" height="580" alt="making new directory and downloading crowbar tool to do brute force attack" src="https://github.com/user-attachments/assets/1b1d96e7-043b-4ba6-a15c-ac3b67a7e24d" />

Ref 53: Made a new directory and downloaded crowbar tool to do brute force attack to my target machine.

<img width="712" height="576" alt="downloading and unzipping rockyou" src="https://github.com/user-attachments/assets/0352678c-2d55-42ab-a716-e4213a92a865" />

Ref 54: Using a popular wordlist, downloading and unzipping rockyou.

<img width="712" height="577" alt="copying file ontop ad project folder" src="https://github.com/user-attachments/assets/3c86e76e-94d8-4d2f-9d77-c524eb0e80a1" />

Ref 55: Copied the file ontop of my ad project folder.

<img width="716" height="577" alt="making 20 passwords with first 20lines" src="https://github.com/user-attachments/assets/7e4a79a1-000a-4b60-bbc4-765cad248cea" />

Ref 56: Making 20 paasswords only with the first 20 lines.

<img width="710" height="582" alt="making new password in password txxt file" src="https://github.com/user-attachments/assets/b50dd1a8-c8e3-4041-9e9f-a99bd9b5b674" />

Ref 57: Made my new password in paassword text file.

<img width="986" height="852" alt="enabled RDP for both users" src="https://github.com/user-attachments/assets/7d26c08c-10b6-484a-9296-49cd082c0c6a" />

Ref 58: I had to enable RDP on both users for the brute force attack to work.

<img width="912" height="892" alt="used hydra since crowbar was not working and it worked" src="https://github.com/user-attachments/assets/8c74f5fd-7d48-45ae-b755-2afe11afbc9f" />

Ref 59: I tried using crowbar with the command of "crowbar -b rdp -u tsmith -C passwords.txt -s 192.168.10.100/32" and an error occured.
Even after downloading the newer versoin of crowbar the command still did not work. So insteal I downlaoded Hydra and used brute force and it worked.

<img width="1018" height="861" alt="event id on 4625 windows security an account failed to log on" src="https://github.com/user-attachments/assets/c3b520e5-ebc5-47db-877d-5387d44718cf" />

Ref 60: On splunk the telemetry shows event id 4625 which indicated an account failed to log on. This id can be found on windows security with many different id explanations.

<img width="1012" height="866" alt="event showing my kali linux logging in" src="https://github.com/user-attachments/assets/bdf0df87-bf6a-48c4-853d-783b03734a66" />

Ref 61:Kali linux with its ip address is shown to be the machine causing event id 4625.

End.





















