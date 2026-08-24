
# Week 02 Tutorial

## 1. Project Setup
Created a new project named **Setting-IP-12327823**.

![New project created] ( <img width="1695" height="855" alt="week2-1" src="https://github.com/user-attachments/assets/a3335c34-6749-498b-89a9-82c626fcfa69" />
)

## 2. Network Topology
Added four Linux Host nodes and one Ethernet switch, then connected them together to form a LAN.

![LAN topology with 4 hosts and a switch]<img width="906" height="908" alt="week2-2" src="https://github.com/user-attachments/assets/7f0152c9-fc00-4c05-aa92-49537f5ce938" />
)

## 3. IP Address Configuration

### Host 1 & Host 2
Configured IPv4 addresses starting at `10.10.1.11` for Host 1 and Host 2.

![Host 1 & 2 IP configuration]<img width="906" height="908" alt="week2-2" src="https://github.com/user-attachments/assets/2989c7b1-3056-4401-9338-4859063f760b" />
)

Host 3 and Host 4 were left without the configure option applied at this stage. All nodes were then started.

### Host 3 — Static IP via Config File
Used `nano /etc/network/interfaces` on Host 3 to manually configure a static IP address of `10.10.1.13`.

![Static IP configuration on Host 3]<img width="860" height="878" alt="week 2-3" src="https://github.com/user-attachments/assets/05acc2db-e049-4375-94f7-8f358a41f85f" />
)

### Host 4 — Static IP via Command
Used the `ip address add` command on Host 4 to assign an IP address to the host.

![IP address added on Host 4]<img width="863" height="785" alt="week 2-4" src="https://github.com/user-attachments/assets/cb81e058-14b6-406c-8c2e-4821b5587b0d" />
)

## 4. Verifying IP Addresses
Confirmed that all IP addresses were correctly assigned across the four hosts.

![IP verification 1]<img width="806" height="768" alt="week2-5" src="https://github.com/user-attachments/assets/16ca431f-0c19-45be-945d-b7d50fdda955" />
)
![IP verification 2]<img width="887" height="820" alt="week2-6" src="https://github.com/user-attachments/assets/ca9e9dc0-4a9e-489e-a866-448e1e1b30a0" />
)


## 5. Ping Tests

**Pinging Host 2** — successful reply confirming connectivity:

![Ping to Host 2 successful]<img width="734" height="630" alt="week2-10ping" src="https://github.com/user-attachments/assets/0ea2b58d-7a57-4a14-afe0-8f12c2cc3455" />
) 


Week 02 provided me with practical experience in creating and configuring a basic network using GNS3. I created the Setting-IP-12327823 project and built a LAN consisting of four Linux hosts connected through an Ethernet switch. This helped me understand how multiple hosts can be connected within the same network.

