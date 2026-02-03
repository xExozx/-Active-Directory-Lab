<img width="656" height="590" alt="Error when opening windows server" src="https://github.com/user-attachments/assets/a368cba6-da86-4450-a8eb-25fa0c8ae910" /># Active Directory Lab

## Objective
[Brief Objective - Remove this afterwards]

The Active Directory project aimed to establish a controlled environment for simulating and detecting cyber attacks on splunk. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security.

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

Ref 3: Upgraded Repository for splunk.

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

Ref 9: Setting up static ip by for Splunk by going into "sudo nano /etc/netplan/00-installer-config.yami".

<img width="841" height="753" alt="changing splunk ip address" src="https://github.com/user-attachments/assets/c95c824c-c837-4e09-be42-f5f4d0ba7895" />

Ref 10: Changed the IP address to 192.168.10.10/24 as shown in the diagram.

<img width="1281" height="122" alt="changed splunk ip address" src="https://github.com/user-attachments/assets/2875ec2a-90bf-44f0-8e57-6df650379226" />

Ref 11: "ip a" is now showing our ip address as 192.168.10.10/24.



