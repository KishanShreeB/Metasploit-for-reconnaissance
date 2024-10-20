# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Find out the ip address of the attackers system
## Output
![image](https://github.com/user-attachments/assets/77bd0024-7a3c-4b7a-b967-aa89bd3c7e82)

## Invoke msfconsole
## OUTPUT:
![image](https://github.com/user-attachments/assets/8bff09e4-cbde-40ef-983a-f9a522b10b2e)
Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.
![image](https://github.com/user-attachments/assets/ad7102df-8852-4b96-a82b-328d8efe50c5)
## Port scanning:
## msf > nmap -sT 192.168.1810/24-p1-1000
![image](https://github.com/user-attachments/assets/c77e903b-5272-4b94-a8c0-3698731f34f3)
## msf > db_nmap 192.168.181.0/24
![image](https://github.com/user-attachments/assets/05c20652-39a1-4b43-9824-91e2f46327b5)
## kali > ls-l
![image](https://github.com/user-attachments/assets/f59ea334-d429-4f88-8941-3c255c5432ea
## search
![image](https://github.com/user-attachments/assets/c7389e1a-220b-48a9-8de0-5cb72b728507)
## info
![image](https://github.com/user-attachments/assets/aefe8783-51ab-4017-a777-8fd6e869d772)
## MYSQL ENUMERATION
## db_nmap -sV -sC -p 3306 <metasploitable_ip_address>
![image](https://github.com/user-attachments/assets/1664671c-6336-4fbf-a3de-62fbebaa4d0a)
## search
![image](https://github.com/user-attachments/assets/7c039b67-ebb2-4775-84ee-10518196e0b8)
## use 11 Or: use auxiliary/scanner/mysql/mysql_version
![image](https://github.com/user-attachments/assets/cadecacb-e531-4b61-a69b-23ff0f66c68a)
## Use the set rhosts command to set the parameter and run the module, as follows:
![image](https://github.com/user-attachments/assets/e35eba59-474f-4d6f-942d-6c5f3a67bb7a)
## After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module.
![image](https://github.com/user-attachments/assets/6f5f2b2b-fa74-44ac-a723-883395891ea9)
## /usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt
![image](https://github.com/user-attachments/assets/89bfefe6-97e2-4df5-a233-e94366820b24)
![image](https://github.com/user-attachments/assets/71a0cf2d-88f4-4919-ac1f-be39d43eb6c8)

## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
