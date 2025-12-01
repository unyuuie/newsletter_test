# NTHU Racing Newsletter Production, Refinement & Delivery
The project is going to cover the newletter production process, refinement through Sourcetree and Visual Studio Code, and the preperation for two delivery formats for Gmail and LINE sponsor outreach.

## Newsletter Production Using Mailchimp
教學影片

## Refinement and Customization
### a. Stepup
1. Create a GitHub account and join NTHU-Racing's organization.
2. Download the HTML file fomr Mailchimp.
3. Create a new repository on GitHub and upload the HTML file. (在organization還是personal)
4. Download Sourcetree, Visual Studio Code, and Git.
5. Go to `Extension` in Visual Studio Code and search for Live Server. Press install.
   
   ![live server](https://github.com/user-attachments/assets/982f19d9-1ec2-474e-b3f2-baba6f2d9521)

6. Save all images used in the newsletter locally.
7. Open the HTML file with Visual Studio Code and press `Go Live` in the bottom right.

### b. Replace Images With Local Assets
Replace all image links from Mailchimp to local paths starting with `./images/` in Live Server.
   
   <img width="874" height="540" alt="Screenshot 2025-12-01 at 8 02 04 PM" src="https://github.com/user-attachments/assets/9b9588f3-9e57-47dd-8d21-0b57e438b304" />
   
### c. Remove the Mailchimp Logo
1. Open Git Pages (Select the repository >> Settings >> Pages >> Press the link in bold)
2. Press `F12` to open develop mode.
3. Press the botton in the picture to select the Mailchimp logo.

   ![icon](https://github.com/user-attachments/assets/136e5c6c-c0d9-407c-bac4-5558a1fb50e3)

5. You will be directed to the corresponding code. Delete the code.

## For Gmail Outreach Sponsors: Copy the Context From Git Pages
Copy all content from GitHub Pages and paste it directly into the email body for Gmail delivery.

<img width="1918" height="1019" alt="image" src="https://github.com/user-attachments/assets/3ac297fd-db9c-41c0-bbb1-2111519083cd" />

## For LINE Outreach Sponsors: Publishing Newsletter on GitHub
我不知道電子報要怎麼上傳到GitHub(readme?)
