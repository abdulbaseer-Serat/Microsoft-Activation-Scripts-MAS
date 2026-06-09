# Microsoft-Activation-Scripts-MAS-
An open-source Windows and Office activator featuring HWID, Ohook, TSforge, and Online KMS activation methods, along with advanced troubleshooting.

# Activation Methods

<details>
  <summary style="font-size:16px; font-weight:bold; color:#7b2cbf;">
    ▶ Method 1: PowerShell (Recommended)
  </summary>

  <br>

 ### This method is the most convenient and works on Windows 8.1, 10, and 11.
1. Click the **Start Menu**, type `PowerShell`, and open it.  
2. Copy and paste the code below and press **Enter**.

```powershell
irm https://get.activated.win | iex
```
If the above is blocked (by ISP/DNS), try this (needs updated Windows 10 or 11): 
 ```powershell
iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
```   
3. In the menu that appears, type the number corresponding to one of the Green options.

> 💡 **TIP**
>
> - Some ISPs/DNS providers block access to our domains.  You can bypass this by enabling **[DNS-over-HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/)** in your browser.
> - **Having trouble?** visit to [troubleshooting page](https://massgrave.dev/troubleshoot)
  
</details>



<details>
  <summary><b>▶ Method 2: Traditional (Offline)</b></summary>

  <br>
  
### Use this method if you prefer downloading a file or cannot use the PowerShell method.


1. Download the script:

- [MAS_AIO.cmd](https://github.com/yourusername/yourrepo/releases/download/v1.0/MAS_AIO.cmd) (Direct script)  
- https://github.com/yourusername/yourrepo/releases/download/v1.0/MAS_AIO.zip (If the direct script is blocked by your browser)

2. Run the `MAS_AIO.cmd` file.

3. In the menu that appears, type the number corresponding to one of the **Green** options.




</details>

## Features

- **HWID (Digital License):** Permanently activate Windows.  
- **Ohook:** Permanently activate Office.  
- **TSforge:** Permanently activate Windows, ESU, and Office.  
- **Online KMS:** Activate Windows/Office for 180 days (lifetime with renewal task).  
- Advanced activation troubleshooting.  
- `$OEM$` folders for pre-activation.  
- Change Windows edition.  
- Change Office edition.  
- Check Windows/Office activation status.  
- Available in All-In-One and separate file versions.  
- Fully open source and based on batch scripts.
- Fewer antivirus detections.

