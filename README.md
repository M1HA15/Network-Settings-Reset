# 🌐 Network Settings Reset (**NSR**)

## 🚀 A Simple and Efficient Solution for Network Maintenance on Windows

The Network Settings Reset Script is a powerful yet user-friendly Windows batch script designed to simplify the process of resetting and maintaining network settings. It's perfect for users who want to optimize their network configurations, resolve connectivity issues, or refresh DNS settings with just a few clicks.

## 💻 Key Features

- ⛔ **Administrator Privileges Check:** Ensures seamless execution by verifying that the script is run with administrator privileges.

- 📊 **Comprehensive Network Maintenance Tasks:**
  - **Flushing DNS:** Clears the DNS resolver cache for improved performance.
  - **Registering DNS:** Refreshes DHCP leases and re-registers DNS names.
  - **Releasing IP:** Releases the current IP address configuration.
  - **Renewing IP:** Obtains a new IP address configuration from a DHCP server.
  - **Resetting Winsock:** Resets the Winsock catalog to its default state.
  - **Setting DNS Provider:** Allows users to choose their preferred DNS provider for enhanced browsing security and speed.

    Choose from popular DNS providers:
    - Cloudflare (1.1.1.1)
    - Cisco Umbrella (208.67.222.222)
    - GCore (95.85.95.85)
    - Quad9 (9.9.9.9)
    - Google (8.8.8.8)

  - **Script automatically pings the recommended DNS providers** for optimal performance before making a selection.

  - Additionally, you can **input your custom DNS provider**, supporting both IPv4 and IPv6.

- 🤝 **User-Friendly Restart Option:** After completing network tasks, the script prompts users to restart their computers for changes to take effect.

## ⚙️ Usage

1. **📁 Download:** 
Get the latest version of the script from the [Releases](https://github.com/M1HA15/Network-Settings-Reset/releases) page.

2. **🛡️ Run with Administrator Privileges:**
   ```bash
   > NSR.bat
   ```
   
3. **🌎 Choose DNS Provider (Optional):**
   ```bash

   ```

4. **🚀 NSR GitHub Page (Optional):**
   ```bash
   Do you want to open the GitHub page of this project? (Y/N): Y
   Opening default web browser...
   ```

5. **🌌 Restart (Optional):**
If desired, restart your computer to apply the network settings changes.
     ```bash
     Do you want to restart the computer now? (Y/N): Y
     We appreciate you using the script. Your computer will restart shortly!
     ```

## ⚠️ Disclaimer
Use this script at your own risk. Be sure to understand the implications of resetting network settings on your system before running the script.

## 📝 Contributing
We welcome contributions! Please read the [Contributing Guidelines](https://github.com/M1HA15/Network-Settings-Reset/blob/main/CONTRIBUTING.md) before submitting issues or pull requests.

## 🚧 Report Issues
If you encounter any issues, please [report them here](https://github.com/M1HA15/Network-Settings-Reset/issues).

Your feedback is valuable in improving the script!

## 👤 Author
- **[Mihai](https://github.com/M1HA15)**

## 👥 Contributors
- **[rad](https://github.com/RadNotRed)**

## 📃 License
This project is licensed under the GPL-3.0 License - see the [LICENSE](https://github.com/M1HA15/Network-Settings-Reset/blob/main/LICENSE) file for details.
