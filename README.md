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
> Some ISPs/DNS providers block access to our domains.  
> You can bypass this by enabling **[DNS-over-HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/)** in your browser.
>
> - **Having trouble?** [Connect with us](https://github.com/yourusername/yourrepo/issues)
   
</details>

<details>
  <summary><b>▶ Method 2: Traditional (Offline)</b></summary>

  <br>

  Step 1: Download file  
  Step 2: Run manually  
  Step 3: Finish ✅

</details>
