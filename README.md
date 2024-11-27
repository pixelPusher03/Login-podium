 # LoginPod  
 ### Password encrypter + manager 
 **Stop** using plain text passwords for your online accounts you are making your accounts more prone to a hack.</br> 
 LoginPod is a password encrypter and password manager written in bash with python3 as supportive backend for encrypting passwords and account password management. Like other encryption algorithm's LoginPod has it's own encryption algorithm which works based on a 5 digit encryption key which is a input from user. Using LoginPod you can encrypt your password's, to make it more strong and store it in password vault. 
  
   ## Why to use LoginPod and not other password managers ? 
 + You don't get flexibility while using other encryption algorithms, but here based on 5 digit encryption key from 00000 to 99999 you get 100000 different encrypted output based on key you entered.  
  
 + It stores your passwords on your system disk instead of any server keeping you safe in case of any data breach attack. 
  
 + All your password are stored in plain text, passwords are encrypted only at runtime and to get correct password correct 5 digit encryption key must be entered. 
  
 + Stop using online password encrypters as you are giving your passwords to them and they might track you. 
  
 + Really, is there any gurantee that password manager softwares will store your password at their server and never going to peek on them. Better you store them on your system disk. 
  
  
 ## Usage 
 **1.** When you run the script, you are welcomed with this screen where you have to enter 5 digit encryption key on which the encryption algorithm works ranging from 00000 to 99999. For each encryption key entered the algorithm gives different output, so you have to decide a 5 digit encryption key and always use that same encryption key. 
  
 <img src="![Screenshot_20231024-003918~2](https://github.com/thedeveloper03/mail/assets/123274423/671a976f-2f74-443b-8990-ebc7708e64ee)
" width="100%"></img> 
  
 **2.** After entering the encryption key user is welcomed with the main menu, where he can encrypt his passwords and if user wants to store the password for different accounts the password vault can be used.</br> 
  
 <img src="![Screenshot_20231024-003942~2](https://github.com/thedeveloper03/mail/assets/123274423/25b7c836-9757-4267-881b-f8f7106d36aa)
" width="100%"></img> 
  
 **3.** Selecting the second option (encrypter) where user can enter his password and get the encrypted value.</br> 
  
   **4.** Selecting the first option (password vault) will take user to the vault menu, where user can add account name and password, update, retrive saved account passwords and delete an saved account. 
  
 **5.** Saving account and password: user can save the account and password (passwords are stored in plain text
 
 **6.** Retrive password: Added accounts passsword can be retrived. 
  
 <img src="![Screenshot_20231024-004039~2](https://github.com/thedeveloper03/mail/assets/123274423/e58c98ac-ff6e-47e5-b481-2d5228cb39d2)
" width="100%"></img> 
  
  
 ## Installing and requirements 
 - Python 
 - Pyhton3 
 - Linux or Unix-based system 
  
 ### Installing 
 ``` 
 ~ ❯❯❯ git clone https://github.com/thedeveloper03/mail.git 
  
 ~ ❯❯❯ cd mail
  
 ~ ❯❯❯ chmod +x login.sh 
  
 ~ ❯❯❯ ./loginpod.sh 
 ``` 
  
