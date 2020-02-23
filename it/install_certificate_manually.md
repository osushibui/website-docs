---
title: "Installing the certificate manually"
old_id: 12
---
If you're having troubles connecting to Shibui or the switcher doesn't install the certificate properly, you can try installing it manually.

### Instructions
- First, download the certificate [by clicking here](/static/shibui.crt)
- Then, open **certificate.cer**
- Click **Install certificate...**
- Click **Next**
- Select **Place all certificates in the following store** (second option), then click **Browse...**
- A new window will pop up, select **Trusted root certification authorities** and click **Ok**
- Click **Next**
- Click **Finish**

### How to test the certificate
Once you've installed the certificate, you can test whether it was successfully installed by attempting to connect to the server. If you are still having issues, double check you are actually connected to the server. If so, join our [Discord](https://discord.gg/vY29JhD) and alert us in #support channel and we will do our best to help.  

### If everything else fails...
...you can try to remove all existing Shibui certificates and install the certificate again. Follow these steps:

- Press **Win+R**  
- Type `mmc certmgr.msc` in the run box and press **enter** to open the Certificate Manager  
- Select **Trusted root certification authorities** on the left  
- Select **Certificates** on the right  
- You should see some some **\*.ppy.sh** entries in the list. Select them, **right click** and click on **Delete**  
- Select all the positive options (Ok/Yes etc)  
- Restart the switcher, click on **Install certificate**, then **Yes**  
**If the certificate is installed fine but you still can't connect to Shibui from the game client, try running osu! as administrator or join our [Discord](https://discord.gg/vY29JhD)**.
