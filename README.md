# FLEEK-GUIDE-CLI
FLEEK GUIDE CLI


Pre-Requirements 🛠
Install node.js & npm
node.js

# curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
# sudo apt install -y nodejs


npm
# sudo apt install nodejs npm

Install fleek CLI

# sudo npm install -g @fleek-platform/cli

Verify the Installation with
# fleek

![image](https://github.com/user-attachments/assets/0cf8b8a2-f1ed-4532-b44c-bf5a57f137d2)


Login

# fleek login

Run the above command to get the login page link:

Login with your Wallet and Email (both)

After login, open the above link again to sign

![image](https://github.com/user-attachments/assets/b5746fcf-ad84-4d6f-af05-0da94427cd58)


Back to Terminal & u could see a success message:
![image](https://github.com/user-attachments/assets/99bffb8b-8844-4203-95f1-f270bedb73cb)


Create a project

# fleek projects create


This will promt u to enter a project name: Enter anythinkanything u like:

🔺🔺 If u see somethink like that (check ss given below), than dont do anythink, just do next process of Set up a simple page

![image](https://github.com/user-attachments/assets/ec85ca26-e14c-4b3c-9d8f-0863cb046d08)


Set up a simple page

Create a New Directory

# mkdir ~/fleek-quick-start

Navigate to it

# cd ~/fleek-quick-start

Create a simple html page inside ~/fleek-quick-start

# echo "Hello world" > index.html
Setup a Fleek site

# fleek sites init


This will promt u to do many thinks, just follow the CLI instructions

You’ll have to enter a name for the new site.

This will Promt ✔ Please specify the directory containing the site files to be uploaded just enter . (a dot)

This will promt ✔ Would you like to include the optional "build" command? just enter no

This will promt ✔ Select a format for saving the site's configuration: just select JSON (fleek.config.json) & Enter

Check the below given SCREENSHOT for more clarification

![image](https://github.com/user-attachments/assets/0946f74c-141c-49ac-b4cd-14381ce8ed00)


Deploy the Fleek site

# fleek sites deploy

![image](https://github.com/user-attachments/assets/07550049-9e09-45b0-8acc-0ca6a29cbfe0)


Done!⚕️✅

👉 Join TG for more Updates: https://telegram.me/cryptogg

If U have any issue then open a issue on this repo or Dm me on TG~

Thank U! 👨🏻‍💻

Happy Coding💗
