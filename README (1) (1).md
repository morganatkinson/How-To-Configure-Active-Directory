Watch Me Create This Lab.
https://www.loom.com/share/ad2cbef8d64f44d892b2c25109f3451d?utm_medium=gif
https://www.loom.com/share/42d41d950bcc433ba531d6b54c52422e?utm_medium=gif

# How to Configure Active Directory

## Steps

1. Go to the search bar in the bottom, enter and type in **Server Manager**, then select **Open**.  
2. Give it a second to load. You will know it’s done loading once all the boxes appear in the **Roles and Server Groups**.  
3. In the **Welcome To Server Manager** section, click on **Add roles and features**.  
4. Select **Next**, **Next**, **Next**.  
5. Check the box beside the option **Active Directory Domain Services**, then select **Add features**.  
6. Select **Next**, **Next**, **Next**, then click **Install**.  
   - This installation may take 5–10 minutes to download.  
7. Select **Close** once the installation is done.  
8. Click on the flag in the top-right-hand corner.  
9. Select **Promote this server to a domain controller**.  
10. Select **Add a new forest**.  
11. In the **Root domain name**, enter `Skool.local`.  
12. Select **Next**, create a password, then click **Next**, **Next**.  
13. The **NetBIOS domain name** will be `SKOOL`.  
14. Select **Next**, **Next**, **Next**, then select the first section under **View results**.  
15. Click **Install**, prompting the virtual machine to reboot itself.  
16. After reboot, select **Close**, **Close**.  

## Verification

You will now see that the **Active Directory Domain Service** was installed successfully.
