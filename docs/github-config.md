# How do I use HelloUKey to generate a key for GitHub?

### 1. First, launch **[HelloUKey - SSH Agent & Key Vault](https://apps.microsoft.com/detail/9n0wbprdgf78?referrer=appbadge&cid=github-config&mode=full)** and go to the key management page:
![main](../docs/assets/main.png)
   
### 2. Click "Create Key" to open the key creation window, and fill in the configuration as shown in the figure: 
![create-key](../docs/assets/create-key.png)
   
### 3. Copy the public key in OpenSSH format, paste it into the SSH key text box on GitHub, and save it.
![copy-key](../docs/assets/copy-key.png)

### Next, you can use Git to pull the SSH repository; a Windows Hello authentication window will pop up during the pull. 
### Once you've done this, your GitHub SSH private key will be protected by hardware-level security.
