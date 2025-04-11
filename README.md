# nmap-script
Nmap is used to identify and scan systems on the network. It is an important part of network diagnostics and evaluation of network-connected systems.


1. To scan a single host

```bash
  nmap 10.0.2.15
```
![WhatsApp Image 2025-04-11 at 13 04 03_9358f1a7](https://github.com/user-attachments/assets/79100a3e-04eb-47b9-ae96-6d73439a7161)


2. To scan a netwrok range

```bash
  nmap -sn 10.0.2.15/24
```
![image](https://github.com/user-attachments/assets/c4f39c15-9445-4c7e-91a7-adca64a6aab7)

3. To scan all port

```bash
  nmap -p- 10.0.2.15
```
![WhatsApp Image 2025-01-29 at 10 08 24_4c0e1d63](https://github.com/user-attachments/assets/f9757491-bc86-4908-90c7-ae3d1ca7169e)


4. To scan specific ports

```bash
  nmap -p 80,443,1000-1020 10.0.2.15
```
![image](https://github.com/user-attachments/assets/df298b0e-be5f-46c8-bc49-84d7fe33edf9)


5. To check the service and version

```bash
  nmap -sV 10.0.2.15
```
![image](https://github.com/user-attachments/assets/ee3db2d1-8c10-44e6-b62c-cb14ca20df54)


6. To perform OS scanning

```bash
  nmap -O 10.0.2.15
```
![image](https://github.com/user-attachments/assets/406e0c17-8063-4e8c-ac76-b454d8bf3fa6)


7. To perform Aggressive scanning

```bash
  nmap -A 10.0.2.15
```
![image](https://github.com/user-attachments/assets/1a942ea8-d6cc-4789-9b54-553fd8f8bd43)


8. To perform Stealth scanning

```bash
  nmap -sS 10.0.2.15
```
![image](https://github.com/user-attachments/assets/cede8099-4c03-4167-8bc9-14e655d08d2c)

#Firewall and IDS evasion

1. To perform packet fragmenting 

```bash
  nmap -f 10.0.2.15
```











