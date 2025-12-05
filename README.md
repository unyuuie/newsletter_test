# NTHU Racing Newsletter Production, Refinement & Delivery
The project is going to cover the newletter production process, refinement through Sourcetree and Visual Studio Code, and the preperation for two delivery formats for Gmail and LINE sponsor outreach.

## Newsletter Production Using Mailchimp
教學影片

## Refinement and Customization
### a. Setup
1. Save all images used in the newsletter locally.
2. Export the HTML file from Mailchimp. 
1) Copy the code and paste it on Word.
2) Copy the entire code and paste it on Visual Studio Code, then press `Save as...` and named it index.html
3. Put the images and index.html in a FOLDER.
4. Download SourceTree, Visual Studio Code, and Git.
5. Go to `Extension` in Visual Studio Code and search for Live Server. Press install.
   
   ![live server](https://github.com/user-attachments/assets/982f19d9-1ec2-474e-b3f2-baba6f2d9521)

6. Right-click on the HTML file and select `Open with Visual Studio Code`.
7. Press `Go Live` in the bottom right in Visual Studio Code.
8. Create a GitHub account and join NTHU-Racing's organization.
8. Connect SourceTree to your personal GitHub account.
Tutorial: https://s81679.github.io/2020/04/09/start-sourcetree/#%E9%96%8B%E5%95%9F-SourceTree (starting from the index `開啟SourceTree`)
9. Open Scourcetree and press `Add Existing Local Repository`, then upload the FOLDER.
   
### b. Remove the Mailchimp Logo
1. Open Git Pages (Select the repository >> Settings >> Pages >> Press the link in bold)
2. Press `F12` to open develop mode.
3. Press the botton in the picture to select the Mailchimp logo.

   ![icon](https://github.com/user-attachments/assets/136e5c6c-c0d9-407c-bac4-5558a1fb50e3)

4. You will be directed to the corresponding code. Delete the code.
5. Now you have a new code without the logo. Go back to Live Server and delete the body (scroll down until you see <body>), and paste the new one.
6. Save changes.

### c. Replace Images With Local Assets
1. Replace all image links from Mailchimp to local paths (starting with `./images/` ) in Live Server.
   
   <img width="874" height="540" alt="Screenshot 2025-12-01 at 8 02 04 PM" src="https://github.com/user-attachments/assets/9b9588f3-9e57-47dd-8d21-0b57e438b304" />
2. Save changes.
3. Open SourceTree, and press `Commit` on the upper left, type _________ commit (ex. link update commit), and press `Commit` on the bottom right.
4. Press `Push` to upload the changes on GitHub.
NOTICE: For Mac users, here are the steps for macOS not saving Git Pull/Push access tokens (do not press Push and do these instead):
1) Open the Terminal applicatoin on your Mac.
2) Paste `git config credential.helper store` and press enter.
3) Paste `git push origin master` and press enter.

## For Gmail Outreach Sponsors: Copy the Context From Git Pages
Copy all content from GitHub Pages and paste it directly into the email body for Gmail delivery.

<img width="1918" height="1019" alt="image" src="https://github.com/user-attachments/assets/3ac297fd-db9c-41c0-bbb1-2111519083cd" />

## For LINE Outreach Sponsors: Copy the Link of Git Pages
Copy the link of git pages and send it to the sponsors.

