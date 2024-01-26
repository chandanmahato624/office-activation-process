
## Office 2019 Unlock process.

Here, I will provide the unlock process for Microsoft Office. Please follow these steps carefully to ensure successful completion.

### Method 1:
This method is basically only for Windows 10, but it also works in Windows 11 as well.
### Step 1:
First, you need to uninstall all existing installations of Office. Next, download the Office Deployment Tool from the official Microsoft Office site. Once downloaded, create a separate folder named 'Office' and move the downloaded file into the 'Office' folder. Double-click on the folder and then extract the file within it.

After extraction, press Shift+Right-click, and then select 'Open PowerShell.' Paste the correct code to initiate the installation process.

```bash
  .\setup.exe /configure .\configuration-office2019Enterprise.xml
```
After pasting, wait for the completion of the download. The file is approximately 2GB, so the time it takes depends on your internet speed. Once the download process is complete, you can simply click 'OK' or 'Yes' to grant the required permissions, and you are good to go.

### Method 2:
In this method, you need to run a file as an administrator. To do that, navigate to the file path provided below, locate 'OSPREARM,' and run it.

```bash
  .C: Program Files/Microsoft Ofice/Office15/....OSPREARM
```
### Others :

[YouTube 1](https://www.youtube.com/watch?v=u80roDVx5Lw)\
[YouTube 2](https://www.youtube.com/watch?v=CaESt4O3elg)
