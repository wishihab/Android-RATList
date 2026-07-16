[![RAT-DIR-logo.png](https://i.postimg.cc/KYsdQmTS/RAT-DIR-logo.png)](https://postimg.cc/94Z8Q51J)

# Android Remote Access Trojan (RAT) Directory

This repository serves as a comprehensive documentation directory of known **Android Remote Access Trojans (RATs)**, **compiling free, commercial, open-source**, and **leaked variants** alongside their core tracking payloads, features, and systemic permission requirements. 

> [!IMPORTANT]
> **Educational & Research Purpose Only:** This information is intended strictly for **security researchers, malware analysts**, and **educational documentation**. 

---

## ⚠️ Security Warning

> [!CAUTION]
> **HIGH INFECTION RISK:** DO NOT download, compile, or execute these projects unless you fully understand the systemic risks involved. 
> * There is an exceptionally high risk of being infected by the tools/builders themselves.
> * Always leverage isolated sandboxes (VMs/Emulators) and thoroughly inspect all source code or executables.
> * **Remember:** A Trojan hidden inside a Trojan builder is a highly common delivery vector.

---

# 🧠 Vx-Underground

Additional **archived references** and **general trojan documentation** can be found here:

  * [Vx-Underground Builders Archive](https://vx-underground.org)
  * [Ultimate RAT Collection GitHub Repository](https://github.com)

### 🛠️ Utility & External Archives

* **Dataset Archive:** Access the broader telemetry dataset via the [Android RAT Dataset](https://github.com).
* **Network Testing:** If you require port forwarding without purchasing a VPN or modifying local router rules, utilize [Ngrok](https://ngrok.com). 

---

# 🏆 Top 10 RATs Ordered by Remote Access Capabilities

The following ranking lists the **top 10 Android Remote Access Trojans** documented in this directory, ordered by their total number of **verified functional capabilities** and **permission checks**.

### 1. Lab-RATS 🧪 (Free)
> **Score: 15/21 Checkmarks**
*   **Verified Matrix Checks:** GUI(PC/Mobile), Camera, Mic, SMS, MMS, Contact, Call, Call Logs, Storage, Location, Screenshot, Notification, Keylogger, Remote Takeover, Stealth Mode, and more
*   **Infrastructure Edge:** Bypasses classic port-forwarding constraints entirely by utilizing native **IPv6 direct traversal pipelines**. Optimized to support modern target testing layouts all the way up to **Android SDK 36 (OneUI 8.5+)**.

### 2. SpyNote 👁️ (Paid Commercial Origin)
> **Score: 12/21 Checkmarks**
*   **Verified Matrix Checks:** GUI, Camera, Mic, SMS, Contact, Call, Call Logs, Storage, Location, Browser, App List, Notification.
*   **Infrastructure Edge:** Heavily optimized for system-wide sensory dominance. It handles direct payload app-binding, extracts environmental audio loops, and traces hidden hardware telemetry (IMEI/WIFI MAC).

### 3. Hawkshaw 🦅 (Free)
> **Score: 11/21 Checkmarks**
*   **Verified Matrix Checks:** Camera, Mic, SMS, Contact, Call, Storage, Location, Account Detail, Lock/Vibrate/Flash, App Management, Keylogger.
*   **Infrastructure Edge:** Optimizes persistent data pipelines and social log exfiltration points, ensuring high tracking density directly following reboot sequences.

### 4. LokiDroid ⚡ (Free)
> **Score: 10/21 Checkmarks**
*   **Verified Matrix Checks:** GUI, Camera, Mic, SMS, Contact, Call, Call Logs, Storage, Location, Browser.
*   **Infrastructure Edge:** Designed as a multi-bot HTTP client that removes port-forwarding constraints through an asynchronous web C2 control platform.

### 5. Cerberus Banking 🐕 (Commercial Leased Botnet)
> **Score: 10/21 Checkmarks**
*   **Verified Matrix Checks:** GUI, Mic, SMS, Contact, Storage, Location, App List, Admin Control, Inject, Phishing.
*   **Infrastructure Edge:** A highly destructive financial botnet engine designed for systemic mobile banking takeover. It uses a specialized commercial control panel to coordinate real-time overlay delivery across thousands of distributed zombie targets.

### 6. AIRAVAT 🦅 (Free)
> **Score: 10/21 Checkmarks**
*   **Verified Matrix Checks:** Camera, Mic, SMS, Contact, Call, Call Logs, Storage, App List, Screenshot, Shell.
*   **Infrastructure Edge:** A dual-threat exploitation framework merging continuous surveillance loops with an automated system-locking **Ransomware module**.

### 7. DroidJack 🔌 (Free)
> **Score: 10/21 Checkmarks**
*   **Verified Matrix Checks:** GUI, Camera, Mic, SMS, Contact, Call, Storage, Location, Browser, App List.
*   **Infrastructure Edge:** The historical reference baseline for Android monitoring tools. Maps complete local directories and captures intact WhatsApp messaging databases.

### 8. Android Spyware 🕵️ (Free)
> **Score: 9/21 Checkmarks**
*   **Verified Matrix Checks:** SMS, Call, Contact, Device Info, App List (Install Apps), App List (Get Apps), WebView Inject, Camera, Storage, Mic, ADB Command Control.
*   **Infrastructure Edge:** Offers a dense, raw framework that focuses heavily on sensory extraction and deep background system control via automated low-level ADB shell injection.

### 9. Nexus 🔗 (Free)
> **Score: 9/21 Checkmarks**
*   **Verified Matrix Checks:** Camera, Mic, SMS, Call, Storage, Location, Keylogger, Shell, Inject.
*   **Infrastructure Edge:** A sophisticated threat focused on financial target exploitation, automating crypto-wallet hijacking, web overlay phishing injection, and 2FA authenticator database harvesting.

### 10. AhMyth 🛠️ (Free)
> **Score: 9/21 Checkmarks**
*   **Verified Matrix Checks:** GUI, Camera, Mic, SMS, Contact, Call, Call Logs, Storage, Location.
*   **Infrastructure Edge:** A lightweight open-source framework frequently used as an analytical baseline for background media exfiltration and continuous GPS polling loops.

---

# 📊 Comprehensive RAT Matrix (A-Z)

| Name | GUI | OS | Camera | Mic | SMS | MMS | Contacts | Call | Call Logs | Storage | Location | Browser | App List | Admin Control | Keylogger | Screenshot | Shell | Notification | Remote Takeover | Inject | Phishing | Stealth Mode | GitHub Link | Special Feature |
| :--- | :---: | :---: | :---: | :---: | :---: | :---:| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| **Adobot** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | https://github.com | Realtime command execution, Schedule commands |
| **AhMyth** | ✔️ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com | - |
| **AIRAVAT** | ❌ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com <br> https://github.com | Ransomware, Shell Command |
| **Android Spy App**| ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com | Logs |
| **Android Spyware**| ❌ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com | Adb command control |
| **android_trojan** | ❌ | 🐧💻 | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com | Browser history, Add/remove app |
| **Android Voyage** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | - | Remote Screen, Traffic monitor, System app, Lock/unlock, Hide app, Remove password, Brick device, Anti Antivirus, Self Destructive, Password Grabbers |
| **AndroRAT** | ✔️ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com <br> https://github.com <br> https://github.com | Streaming Video, Toast, Vibrate, Open URL |
| **AndroSpy** | ❌ | 🐧💻 | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com | Install, Inject |
| **Arsink RAT** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | - | Sniff, Phishing |
| **BetterAndroRAT** | ❌ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com | Add/remove app, Remote Device Controller |
| Name | GUI | OS | Camera | Mic | SMS | MMS | Contacts | Call | Call Logs | Storage | Location | Browser | App List | Admin Control | Keylogger | Screenshot | Shell | Notification | Remote Takeover | Inject | Phishing | Stealth Mode | GitHub Link | Special Feature |
| **BlueEagle jRAT** | ❌ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Phone Information, Account Detail, Owner Access (Boot), Block google protect |
| **BRAT** | ❌ | 🐧💻 | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ |  ❌ |- | Install and remove apps, Factory Reset |
| **Casperspy** | ✔️ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com | Botnet by dendroid, Browser open page |
| **Cerberus App** | ❌ | 🐧💻 | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Not deletable |
| **Cerberus Bank** | ✔️ | 🐧💻 | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |- | Bank and CC Logs, Mail logs, Turnoff Play Protected, Download/Install/Remove Apps, Lock device |
| **Chameleon** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | - | Screen Capture, Overlay, Proxy, Cookies Stealer |
| **columbus-trojan**| ❌ | 🐧💻 | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com | Front-facing camera, 10s sound clip, Mobile triangulation |
| **Darkweb PexRat** | ❌ | 🐧💻 | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Screen, Infostealer |
| **Dash** | ✔️ | 🐧💻 | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | https://github.com | Multiple Child clients, Environment recording, Notifications received |
| **Dendroid** | ❌ | 🐧💻 | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com | Opening web pages, Uploading images/video, Denial-of-service, Change C&C server |
| **DogeRAT** | ❌ | 🐧💻 | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Install/remove apps, GetApps, Inject |
| Name | GUI | OS | Camera | Mic | SMS | MMS | Contacts | Call | Call Logs | Storage | Location | Browser | App List | Admin Control | Keylogger | Screenshot | Shell | Notification | Remote Takeover | Inject | Phishing | Stealth Mode | GitHub Link | Special Feature |
| **DroidJack** | ✔️ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Whatsapp Reader, Browser History, App Manager |
| **ERMAC** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | InstallApps, GetApps |
| **Fantasy Hub** | ❌ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | 2FA, Realtime Cam/Mic, Permission runtime |
| **FinSpy** | ❌ | 🐧💻 | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Phone information, Mms, Voip record (Skype, WeChat, Viber, LINE) |
| **GhostCtrl** | ❌ | 🐧💻 | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Voice record |
| **Gigabud RAT** | ❌ | 🐧💻 | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Screen record, Install package |
| **GoldDigger** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | - | - |
| **GravityRAT** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Exfiltrate data |
| **HaxRAT** | ❌ | 🐧💻 | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com | Audio recording |
| **Hawkshaw** | ❌ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | https://github.com | Account Detail, Lock, Vibrate, Flash, Owner Access (Boot), Inject, Logs/Keylog (messenger, socialmedia) |
| Name | GUI | OS | Camera | Mic | SMS | MMS | Contacts | Call | Call Logs | Storage | Location | Browser | App List | Admin Control | Keylogger | Screenshot | Shell | Notification | Remote Takeover | Inject | Phishing | Stealth Mode | GitHub Link | Special Feature |
| **Hector / ISOON** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Log system multi platform, adb control |
| **Hidden Cobra** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Proxy, Payload |
| **HighRise** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Incoming/outgoing SMS |
| **IMG-RAT** | ❌ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Shell integration |
| **i-spy Android** | ❌ | 🐧💻 | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |https://github.com | Standard filesystem storage |
| **Joanap** | ❌ | 🐧💻 | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Botnet, Steal log |
| **Joker** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Manipulating subscription (money), Play Store infection |
| **KevDroid** | ❌ | 🐧💻 | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Installed apps, Phone number, Unique ID, Mails |
| **Lab-RATS** | ✔️ | 🐧💻🍎 | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | https://github.com | IPv6 traversal, Works on Newest Android(SDK 36), Blackout Mode(screen blinding), Remote App Restart(SMS Prompt), Anti-Removal Sheild, Ghost Mechanics, Self Healing, Functional App Decoys.
| **LaRAT** | ❌ | 🐧💻 | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | https://github.com | Add Google form for passwords |
| **LodaRAT** | ❌ | 🐧💻 | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Install application, Account Credentials |
| Name | GUI | OS | Camera | Mic | SMS | MMS | Contacts | Call | Call Logs | Storage | Location | Browser | App List | Admin Control | Keylogger | Screenshot | Shell | Notification | Remote Takeover | Inject | Phishing | Stealth Mode | GitHub Link | Special Feature |
| **LokiDroid** | ✔️ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Phone details, Sim/Internet details, Offline commands, Multiple bots, http RAT |
| **Mass RAT** | ❌ | 🐧💻 | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com | - |
| **MMRat** | ❌ | 🐧💻 | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | adb command automation |
| **Monokle** | ❌ | 🐧💻 | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Screen recording, Fingerprint-device duplicate, Shell as root |
| **NetWire** | ✔️ | 🐧💻 | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Download/Upload pipelines |
| **Nexus** | ❌ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | - | Inject Banking, Crypto app, 2FA app database |
| **Nivistealer** | ❌ | 🐧💻 | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | https://github.com | IP, Web steal based, set phishing site |
| **OmniRAT** | ✔️ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Full Remote Access, File Manager, App Widgets, Full System Information |
| **Pegasus** | ❌ | 🐧💻🍎 | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com <br> https://github.com | Calendar, Instant Messaging, Mail, Device Setting |
| **PounceKeys** | ❌ | 🐧💻 | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | https://github.com | Phone info extraction, clipboard memory scraping |
| **Pupy** | ❌ | 🐧💻 | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | https://github.com | Text to speech, Webcam snapshots (front & back) |
| Name | GUI | OS | Camera | Mic | SMS | MMS | Contacts | Call | Call Logs | Storage | Location | Browser | App List | Admin Control | Keylogger | Screenshot | Shell | Notification | Remote Takeover | Inject | Phishing | Stealth Mode | GitHub Link | Special Feature |
| **Rafel RAT** | ❌ | 🐧💻 | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | github.com | Ransomware module, Persistence mechanisms |
| **rdroid** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | github.com | System diagnostics |
| **Rogue RAT** | ❌ | 🐧💻 | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Continuous telemetry |
| **SHConnect** | ❌ | 🐧💻 | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Basic tracking |
| **SpyApp Client** | ✔️ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | github.com | Notification Listener (Facebook, whatsapp, instagram etc) |
| **SpyNote** | ✔️ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Bind app, Live mic streaming/recording, Hardware details, Fun Panel |
| **Steaelite RAT** | ❌ | 🐧💻 | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Ransomware |
| **Strandhogg** | ❌ | 🐧💻 | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Hijack Session, apps log, wide permission injection |
| **StrongPity** | ❌ | 🐧💻 | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Boot, Network Info tracking |
| **TalentRAT** | ❌ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | github.com | - |
| **TearDroid PHP** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | github.com | Running Services tracker, findphno/findx:pdf command integration, Change Wallpaper |
| **TecSpy** | ❌ | 🐧💻 | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | github.com | Notification logger, Admin adb operations |
| Name | GUI | OS | Camera | Mic | SMS | MMS | Contacts | Call | Call Logs | Storage | Location | Browser | App List | Admin Control | Keylogger | Screenshot | Shell | Notification | Remote Takeover | Inject | Phishing | Stealth Mode | GitHub Link | Special Feature |
| **TeleRAT/IIRAT**| ❌ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Telegram BOT integration, Control Admin Screen, Vibrate |
| **TheFatRAT** | ❌ | 🐧💻🍎 | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | github.com | Execute command, process list optimization |
| **Triout Framework**| ❌ | 🐧💻 | ✔️ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | - | Record phonecall, Steal images/video, Hide app icon |
| **UnknownRAT** | ✔️ | 🐧💻 | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Android Tools (photo, screenshot), Record audio |
| **WH-RAT** | ✔️ | 🐧💻 | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | github.com | Similar with SpyNote NjRAT |
| **Xenomorph / GODFather / PixPirate / Sova / Zanubis / BingoMod / TrickMo / BlankBot / Vultur / Octo2 / Medusa**| ❌ | 🐧💻 | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | - | Fully Control Device, Overlay systems, Bypasses standard biometric/PIN locks |
| **ZeroDayRAT** | ❌ | 🐧💻 | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | - | Cryptostealer, Device info profiles |

---

# 🔱 Project Evolution & Acknowledgments

This repository is an updated, restructured, and actively maintained evolution of the original project by [wishihab](https://github.com) (originally hosted at `wishihab/Android-RATList`). 

### Why this Fork exists:
* **Active Maintenance:** Tracking modern Android threats up to Android SDK 36 (OneUI 8.5+).
* **Enhanced Scannability:** Restructured from loose bulleted lists into high-density Markdown directories.
* **Telemetry Data:** Integrating deeper structural permissions, capability matrices, and architectural markers.

If you are looking for the original, legacy codebase or initial data layers, you can visit the upstream repository [here](https://github.com/Android-RATList).

---

# 🤝 Contributing to the New Directory

Because this is a completely overhauled and expanded version of the database, your contributions are vital to keeping it accurate! 

Whether you want to add a modern malware strain, patch an incorrect permission metric, or fix a broken upstream link:
1. **Fork** this repository.
2. Create your branch (`git checkout -b patch/Add-New-RAT`).
3. Follow our updated high-density data matrix layout.
4. Submit a **Pull Request** targeting our master branch.

---

## ⚖️ Legal & Ethical Disclaimer

> [!WARNING]
> This directory is published entirely for informational, educational, and defensive malware research purposes. 

The maintainers of both the original repository and this evolved fork do not condone, encourage, or support the deployment of Remote Access Trojans (RATs), spyware, or any unauthorized surveillance tools. 

Under no circumstances shall the current or past maintainers of this information be held liable for any misuse, device damage, or legal consequences resulting from the deployment, execution, or modification of the software documented in this directory.
