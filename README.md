# Network-Security-Lab
## Experiment 01	                                         
    • Step 1: Install vmware
    • Step 2: Keep ready with operating system image files like: Ubuntu, Windows,..,etc 
    • Step 3: Open vmware 
    • Step 4: Click on new 
    • Step 5: Enter the virtual machine name
    • Step 6: Select operating system like linux Ubuntu or Windows in drop down menu
    • Step 7: Select ram size and hard disk click on next
    • Step 8: select image file of operating system as mentioned in step 2
    • Step 9: now click on run button 
    • Step 10: installation process begins
    • Step 11: Output

## Experiment 02
# I ) Using Telnet
    • Step 1:  Press Windows + R
    • Step 2: Enter the below command
            >>  lusrmgr.msc
    • Step 3: Control Panel >> turn on off features >> Telnet or TPF telnet >> turn on both option 
          >> click on Ok 
            Wait for while that complete Process….
    • Step 4: click on >>  Users  >> select your username >> right click to Select >> Properties
    • Step 5: Member of Tab >> select Add >> select find options >> Select Telnet Client >> Ok
    • Step 6: Start >> command Prompt run as admin mode 
    • Step 7 : Enter the below command
              telnet www.google.com 80
    • Step 8: Output 

# II) Using Netcat
    • Step 1: Extract the Netcat.rar file in c\: Drive
    • Step 2: Open the command Prompt as admin mode
    • Step 3: Change the Directory to ur netcat folder where file is extracted
     example: cd  c:/netcat-1.11
    • Step 4: Enter the below command
      >> nc www.google.com 80
    • Step 5: Output

## Experiment 03			 
# I ) Super Scan
    • Step 1: Install Superscan.exe file
    • Step 2: open cmd and enter below command
      >> ipconfig
      >> Copy  the ip address
      >> example: 198.162.0.208
    • Step 3: run Super Scan as admin mode
    • Step 4: Paste the IP address in Super Scan >> click on Enumerate button
    • Step 5: Output

# II ) Zen Map
    • Step 1: Install Zen Map.exe file
    • Step 2: command Prompt copy Ip address
    • Step 3: and Enter the IP address in Command Tab >> Click on scan
    • Step 4: Output

## Experiment 04 
# I ) -V
    • Step 1: open zenmap software
    • Step 2: Open Command Prompt and copy the IP Address 
    • Step 3: Paste IP Address in 
            command Tab Like this: nmap -V 198.168.78.1 
    • Step 4: click on scan 

# II ) –sP
    • Step 1 : open zenmap software
    • Step 2: Open Command Prompt and copy the IP Address 
    • Step 3: Paste IP Address in 
             command Tab Like this: nmap -sP 198.168.78.1 
    •Step 4: click on scan 

# III ) –sV
    • Step 1 : open zenmap software
    • Step 2: Open Command Prompt and copy the IP Address 
    • Step 3: Paste IP Address in 
              command Tab Like this : nmap -sV 198.168.78.1 
    • Step 4: click on scan 

# IV ) –A
    • Step 1 : open zenmap software
    • Step 2: Open Command Prompt and copy the IP Address 
    • Step 3: Paste IP Address in 
              command Tab Like this : nmap -sV 198.168.78.1 
    • Step 4: click on scan 

## Experiment 05     
# UBUNTU:
I ) Xprobe
    • Step 1 : install xprobe2
        >> sudo apt install xprobe2
    • Step 2 :  xprobe –v 127.0.0.1
    • Step 3 : Output

# II ) -O
    •Step 1 : install xprobe2
        >> sudo apt install xprobe2
    • Step 2 :  xprobe –O 127.0.0.1
    • Step 3 : Output

# WINDOWS:

# III) zenmap
    • Step 1 : open zenmap software
    • Step 2: Open Command Prompt and copy the IP Address 
    • Step 3: Paste IP Address in 
            command Tab Like this: nmap -O 198.168.78.1 
    • Step 4: click on scan 

# Experiment 06                                        
    • Step 1: Install wire shark software
    • Step 2 : Open Command Prompt and copy the IP Address 
    • Step 3: now Open the wire shark software
    • Step 4: click on local network then scan Data packets are visible
    • Step 5: Output

# Experiment 07                                      
    • Step 1: Install DUMPSEC Software
    • Step 2 : goto browser and search for any website
    • Step 3: now Open the dumpsec software
    • Step 4: Goto >> Report>> select computer
    • Step 5: Paste IP Address and click on ok
    • Step 6: Goto >> Report>> User as tables>> select options like: groups,user,..,etc
    • Step 7: After selection of options click on ok 
    • Step 9: Output

# Experiment 08                                      
    • Step 1: Install JDK (JAVA DEVELOPMENT KIT)
    • Step 2: Install JCT(Jcrypt Tool)
# I ) RSA ENCRYPTION
    • Step 1: Goto >>File>>New>>Empty File in Texteditor
    • Step 2:Enter some text and save it
    • Step 3:Goto>>Algorithms>>Asymmetric>>RSA
    • Step 4: Click on >> Create a new key pair in the keystore
    • Step 5: Enter the desired name for  Contact Name
    • Step 6: Enter the password for encryption
    • Step 7: click on finish
    • Step 8: Encrypted text will appears  
    
# RSA DECRYPTION
    • Step 1:Goto>>Algorithms>>Asymmetric>>RSA
    • Step 2: Select >> Decrypt Radio button
    • Step 3:click on finish
    • Step 4: Enter the password for Decryption
    • Step 5: click on ok
    • Step 6: Decrypted text will appears  

# II ) AES Encryption
    • Step 1: Goto >>File>>New>>Empty File in Texteditor
    • Step 2:Enter some text and save it
    • Step 3:Goto>>Algorithms>>Symmetric>>AES	
    • Step 4: Click on >> Create a new key pair in the keystore
    • Step 5: Enter the desired name for  Contact Name
    • Step 6: Enter the password for encryption
    • Step 7: click on finish
    • Step 8: Encrypted text will appears  
    
# AES Decryption
    • Step 1:Goto>>Algorithms>>Symmetric>>AES
    • Step 2: Select >> Decrypt Radio button
    • Step 3:click on finish
    • Step 4: Enter the password for Decryption
    • Step 5: click on ok
    • Step 6: Decrypted text will appears  

# III ) Message Digest
    • Step 1: Goto >>File>>New>>Empty File in Texteditor
    • Step 2:Enter some text and save it
    • Step 3:Goto>>Algorithms>>HASH>>SHA	
    • Step 4: click on Finish
    • Step 5: Message Digest will appears  

# Experiment 09                                      
# Snort
    • Step 1: install snort software
    • Step 2: Install wincap software
    • Step 3: Open c:\ drive  copy the bin path of snort example : C:\Snort\bin
    • Step 4: goto start search env and select environment variable 
    • Step 5: click on Environment Variables 
    • Step 6: click on new
    • Step 7: Variable Name: PATH
    • Step 8: Variable Value: C:\Snort\bin
    • Step 9: Goto Command Prompt 
    • Stpe 10 : snort –v
    • Step 11: Output



