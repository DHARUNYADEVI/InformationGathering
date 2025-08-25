# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois

<img width="1920" height="1080" alt="Screenshot (233)" src="https://github.com/user-attachments/assets/b155e00b-be7e-48bb-89e4-000b9c551759" />

### Finding Hosting Company :
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6ba1cba7-9629-4a81-aee1-73772293e85f" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9692c70b-a386-4e22-966a-ef8ce0a1ecd7" />

### History of the website :

<img width="1920" height="1080" alt="Screenshot (235)" src="https://github.com/user-attachments/assets/59d89449-18f3-4a92-b3be-34c694cb2ddb" />

### ping command :

### Liux OS

<img width="932" height="585" alt="Screenshot 2025-08-15 131627" src="https://github.com/user-attachments/assets/bb4f1daa-d9d7-44c8-9f79-41ff73bd8a8f" />

### Windows OS

<img width="1034" height="306" alt="Screenshot 2025-08-15 125434" src="https://github.com/user-attachments/assets/fb56308c-66d2-4ddc-99ef-ab6580bebcb4" />

### whois :

<img width="796" height="761" alt="image" src="https://github.com/user-attachments/assets/81751fe2-47d0-495b-9545-88bd96c60c72" />


### netcat :

<img width="792" height="300" alt="Screenshot 2025-08-15 132322" src="https://github.com/user-attachments/assets/075b24a0-6159-42aa-86a7-c3655d103c70" />

### nmap :

<img width="748" height="224" alt="Screenshot 2025-08-15 132629" src="https://github.com/user-attachments/assets/3dc20eb0-954f-44f0-87a3-f8495c58fb46" />

### whatweb :

<img width="933" height="243" alt="Screenshot 2025-08-15 132824" src="https://github.com/user-attachments/assets/e669946d-9fd9-4ec9-9f80-d6ad3926aa5e" />

### httprint :

<img width="752" height="811" alt="Screenshot 2025-08-15 134153" src="https://github.com/user-attachments/assets/eb6ae629-c195-49a2-8ee3-845fccbf5f1e" />

### TCP traceroute :

<img width="932" height="441" alt="Screenshot 2025-08-15 134605" src="https://github.com/user-attachments/assets/00830229-972c-45a6-b314-553f48cdc443" />


### UDP traceroute :

<img width="853" height="529" alt="Screenshot 2025-08-15 134725" src="https://github.com/user-attachments/assets/692e4e15-1dc8-4f4c-9e83-61d2c4158d4b" />



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
