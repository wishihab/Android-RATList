[![RAT-DIR-logo.png](https://i.postimg.cc/KYsdQmTS/RAT-DIR-logo.png)](https://postimg.cc/94Z8Q51J)

# Android Remote Access Trojan (RAT) Directory

This repository serves as a comprehensive documentation directory of known **Android Remote Access Trojans (RATs)**, compiling free, commercial, open-source, and leaked variants alongside their core tracking payloads, features, and systemic permission requirements. 

> [!IMPORTANT]
> **Educational & Research Purpose Only:** This information is intended strictly for security researchers, malware analysts, and educational documentation. 

---

## ⚠️ Security Warning

> [!CAUTION]
> **HIGH INFECTION RISK:** DO NOT download, compile, or execute these projects unless you fully understand the systemic risks involved. 
> * There is an exceptionally high risk of being infected by the tools/builders themselves.
> * Always leverage isolated sandboxes (VMs/Emulators) and thoroughly inspect all source code or executables.
> * **Remember:** A Trojan hidden inside a Trojan builder is a highly common delivery vector.

---

# 🧠 Vx-Underground

  * [Vx-Underground Builders Archive](https://vx-underground.org)
  * [Ultimate RAT Collection GitHub Repository](https://github.com)

---

## 🛠️ Utility & External Archives

* **Dataset Archive:** Access the broader telemetry dataset via the [Android RAT Dataset](https://github.com).
* **Network Testing:** If you require port forwarding without purchasing a VPN or modifying local router rules, utilize [Ngrok](https://ngrok.com). 

---

## 🏆 Top 10 RATs Ordered by Remote Access Capabilities

The following ranking lists the top 10 Android Remote Access Trojans documented in this directory, ordered by their total number of verified functional capabilities and permission checks.

### 1. Lab-RATS 🧪
> **Score: 15/21 Checkmarks**
*   **Key Capabilities:** GUI, Camera, Mic, SMS, MMS, Contacts, Call, Call Logs, Storage, Location, Keylogger, Screenshot, Notification, Remote Takeover, Stealth Mode.
*   **Focus:** Native IPv6 reverse tunnels bypassing NAT for advanced connectivity ``.

### 2. SpyNote 👁️
> **Score: 12/21 Checkmarks**
*   **Key Capabilities:** GUI control, App binding, Storage/Location access, SMS/Call/Call Log theft, Media (Camera/Mic) streaming, and Browser/Device info extraction.
*   **Focus:** Comprehensive environment monitoring and stealthy binding.

### 3. Dash 📊
> **Score: 12/21 Checkmarks**
*   **Key Capabilities:** GUI, Camera, Multi-client support, Stealth, Location, Recording (Call/Ambient), SMS, Keylogger, Overlays, and Notification sniffing ``.
*   **Focus:** Modern web dashboard for concurrent monitoring ``.

### 4. LokiDroid ⚡
> **Score: 11/21 Checkmarks**
*   **Key Capabilities:** GUI, SMS/Call/Log/Contact theft, Toasts, Browser, Storage, Location, and Microphone/Camera access ``.
*   **Focus:** HTTP-based bot management with asynchronous task queuing ``.

### 5. Hawkshaw 🦅
> **Score: 11/21 Checkmarks**
*   **Key Capabilities:** Call/SMS/Contact theft, Device info, Media (Camera/Audio), Location, Storage, Account details, Hardware manipulation, and Keylogging ``.
*   **Focus:** Hardware manipulation (vibration, flash) and chat surveillance ``.

### 6. Android Spyware 🕵️
> **Score: 11/21 Checkmarks**
*   **Key Capabilities:** SMS/Call/Contact/Info, App management, Webview injection, Camera, Storage, Mic, and Remote ADB Control ``.
*   **Focus:** High-density sensory exfiltration with low-level ADB control ``.

### 7. Monokle 🪐
> **Score: 10/21 Checkmarks**
*   **Key Capabilities:** Location, Audio, Call Recording, Screen Capture, Keylogger, Browser/Log history, and Root Shell ``.
*   **Focus:** Advanced surveillance, unique encryption, and root exploitation ``.

### 8. Nexus 🔗
> **Score: 10/21 Checkmarks**
*   **Key Capabilities:** Storage, Camera, Audio, SMS/Call, Shell, Location, Keylogger, Banking/Crypto Overlays, and 2FA scraping ``.
*   **Focus:** Financial manipulation targeting auth apps and crypto wallets ``.

### 9. KevDroid ⚙️
> **Score: 10/21 Checkmarks**
*   **Key Capabilities:** App/UUID theft, GPS Polling, Contacts, SMS/Calls, Mails, Storage, and Mic ``.
*   **Focus:** Metadata harvesting and automated location/cache dumps ``.

### 10. AndroRAT 🔌
> **Score: 10/21 Checkmarks**
*   **Key Capabilities:** GUI, Contacts, Logs, Calls, SMS, Location, Camera, Mic, and Video/UI interaction ``.
*   **Focus:** Open-source foundation for stable socket-based, live audio/video streaming ``.

---

## 📊 Comprehensive RAT Matrix (A-Z)

| Trojan Name | UI / Interface Type | Project Links / Repositories | Core Features & Permissions |
| :--- | :--- | :--- | :--- |
| **Adobot** | CLI Tracker | • [adonespitogo/AdoBot](https://github.com) | Real-time command loop execution, Cron/Scheduled commands, Icon concealment (Stealth mode), Contacts/SMS/Call logs extraction. |
| **AhMyth** | GUI | • [AhMyth/AhMyth-Android-RAT](https://github.com) | Camera, Microphone, Storage, GPS tracker, SMS interception, Call log extraction, Contacts dumping. |
| **AIRAVAT** | CLI / Payload | • [Th30neAnd0nly/AIRAVAT](https://github.com)<br>• [GoutamHX/MAXXRAT](https://github.com) | Direct filesystem storage parsing, Device Administrator permission hooks, App listing vectors, Complete communication mining (SMS/Call/Contacts), Front/Back camera capture, Ambient microphone scraping, Remote screen capture pipelines, System-locking Ransomware payload, Interactive remote shell environment. |
| **Android Spy App**| CLI | • [abhinavsuthar/Android_Spy_App](https://github.com) | Contacts/Call logs/SMS data mining, General diagnostic logs, GPS tracker, External storage access. |
| **Android Spyware**| Comprehensive Framework | • [CanciuCostin/android-spyware](https://github.com) | Complete communication logging (SMS/Call/Contacts), System information mapping, App package indexing/installation, WebView credential injection, Camera capture, Local storage parsing, Microphone capture, Arbitrary ADB shell command execution. |
| **Android Trojan** | CLI | • [androidtrojan1/android_trojan](https://github.com) | Interactive shell, Browser history, Microphone, GPS tracking, Storage, App management, Contacts/SMS/Call log dumping. |
| **Android Voyage** | CLI | *N/A* | Remote screen mirroring, Screenshots, Keylogging, Traffic monitoring, Persistent system app conversion, Passcode removal, Anti-Antivirus mechanics, Self-destructive mode, Credential grabbers. |
| **AndroRAT** | GUI Available | • [DesignativeDave/androrat](https://github.com)<br>• [karma9874/AndroRAT](https://github.com)<br>• [The404Hacking/AndroRAT](https://github.com) | Contacts, Call logs, SMS, GPS, Camera, Mic, Live video streaming, UI Toast messages, URL redirection, Device vibration. |
| **AndroSpy** | CLI | • [qH0sT/AndroSpy](https://github.com) | Camera triggers, SMS monitoring, Contact extraction, Call history harvesting, Local storage read/write access, Arbitrary package installation and code injection. |
| **Arsink RAT** | Spyware Vector | *N/A* | Complete text parsing (SMS channels), Contact data scraping, Voice call logging pipelines, GPS path mapping, Local network traffic sniffing, Custom social application overlay phishing. |
| **BetterAndroRAT** | CLI | • [mwsrc/BetterAndroRAT](https://github.com) | Package installation/removal, Camera, Microphone, Storage access, Call & SMS routing, Remote hardware controller. |
| **BlueEagle jRAT** | Desktop Client Link| *N/A* | Call/SMS/Contact monitoring, Core system data mining, Camera frame capture, Ambient audio capture, Real-time location parsing, Target account info tracking, Boot persistence hooks, Google Play Protect disabling functions. |
| **BRAT** | Brazilian Banking RAT | *N/A* | Silently installs/uninstalls application layers, Package enumeration, Credential injection modules, Force factory reset execution, Device Administrator privilege hijacking. |
| **Casperspy** | GUI Botnet | • [dhanumurti](https://github.com) | Dendroid-derived botnet architecture, SMS logging, Camera/Storage/Microphone tracking, Remote browser manipulation. |
| **Cerberus App** | Admin Client | *N/A* | Storage access, Real-time GPS location, Camera triggers, Admin privilege persistence, Anti-uninstallation hooks. |
| **Cerberus Banking**| GUI Panel | *N/A* | Botnet overlay mechanics, Core banking/Credit Card credential logging, Mail database harvesting, Call forwarding injection, Audio/SMS/GPS trackers, Play Protect security disabling, Remote application installer/remover, Hard screen lock. |
| **Chameleon** | Advanced Stealer | *N/A* | Target layout phishing templates, Automated system keylogger engine, Contact/SMS/Call tracking databases, Local data storage mining, Live layout screen capture, Dynamic input field accessibility overlays, Local SOCKS proxy establishment, Browser session cookie stealing. |
| **Columbus-Trojan** | CLI | • [project-columbus/trojan](https://github.com) | Minimalist stealth design: Front-facing camera snap, 10-second mic audio clipping, Triangulated cell network location. |
| **Darkweb PexRat** | Commercial Spyware | *N/A* | Continuous screen capturing/mirroring framework, Device Administrator validation enforcement, Distributed infostealer profile modules. |
| **Dash** | GUI Control Panel | • [muneebwanee/Dash](https://github.com) | Integrated camera control, Multi-child client control array, Dynamic launcher icon hiding (Stealth mode), Live GPS coordinates mapping, Bi-directional call recording (Incoming/Outgoing), SMS transaction indexing, Ambient audio monitoring, Native keylogger engine, Targeted social network web phishing templates, Notification stream listeners (WhatsApp, Instagram, Messenger). |
| **Dendroid** | Panel Control | • [nyx0/Dendroid](https://github.com) | Full SMS/Call monitoring, Forced HTTP page opening, Remote video/image exfiltration, App initialization, Native DDoS execution panels, Dynamic C2 reassignment. |
| **DogeRAT** | Admin Panel Client | *N/A* | Stealth app package installation/uninstallation, Active package enumeration, Over-the-air injection layers, Real-time camera frames capture, SMS network monitoring, Integrated device keylogging, Full Device Administrator control. |
| **DroidJack** | GUI | *N/A (Closed/Leaked)* | Camera, Mic, GPS, Storage, SMS/Calls/Contacts, WhatsApp reader, Browser history, App manager. |
| **ERMAC** | Banking Botnet | *N/A* | Automated SMS/Call log interception, Contact database exfiltration, Installed application scanning, Package execution commands, Automated WebView overlay injection. |
| **Fantasy Hub** | Surveillance Toolkit| *N/A* | Direct text tracing (SMS pipelines), 2FA validation token interception, Target contact tracking, Real-time video/microphone parsing, Local directory data traversal, Runtime prompt permission interaction hijacking. |
| **FinSpy** | Commercial Spyware| *N/A* | Advanced storage harvesting, System metadata collection, Call/SMS/MMS extraction, GPS tracking, Native VoIP stream recording (Skype, WeChat, Viber, LINE). |
| **GhostCtrl** | Admin Client | *N/A* | Device administrator privilege escalation, Persistent voice recording, SMS routing, GPS location caching. |
| **Gigabud RAT** | Screen Stealer | *N/A* | Real-time screen recording/mirroring pipelines, Storage file extraction, Package deployment/installation hooks, Custom localized keylogging engines. |
| **GoldDigger** | Financial Malware | *N/A* | Native accessibility-driven keylogger engine, Screen layout scraping, Transaction text SMS interception, Target banking web overlay phishing templates. |
| **GravityRAT** | Targeted Spyware | *N/A* | Background SMS mining, Contact exfiltration, Call log interceptor, Mass system folder exfiltration routines. |
| **HaxRAT** | Framework / Payload | • [Hax4us/haxRat](https://github.com) | Complete external/internal storage traversal, Direct camera control, Live room microphone capture. |
| **Hawkshaw** | CLI / Framework | • [saksham2410/Android-RAT---Hawkshaw](https://github.com) | Full communication log harvesting, Audio/Video/GPS capture, Device user account details theft, Hardware manipulation (Lock, vibrate, flash), Boot-persistence execution hook, Stealth app management, Messenger keylogging overlays. |
| **Hector / ISOON RAT**| APT / Multiplatform | *N/A* | Local filesystem mapping, SMS communication streams extraction, Contact logs lifting, Multi-platform unified system log engine, Low-level administrative ADB control modules. |
| **Hidden Cobra** | APT Payload | N/A | Network proxy hosting, Contact database lifting, SMS exploitation, Secondary malicious payload drop vectors. |
| **HighRise** | Background Service | N/A | Proxy-based capture of incoming and outgoing SMS traffic. |
| **IMG-RAT** | Payload Generator | N/A | Local directory storage traversal, Camera state triggers, Ambient microphone stream capture, SMS extraction tracking, Call record listings, Target contact lifting, Internal keyboard keylogger engines, Basic command shell execution. |
| **i-spy Android** | CLI | • JohnReagan/i-spy-android | Standardized deployment for camera frame capturing, GPS location triangulation, File system storage read/write. |
| **Joanap** | APT Botnet | N/A | Microphone streaming, Distributed botnet tasks, Comprehensive diagnostic and credential system log theft. |
| **Joker** | Play Store Injector| N/A | Stealth SMS/Call/Contact extraction, Local storage access, Background premium subscription manipulation (financial theft). |
| **KevDroid** | CLI | N/A | Installed package enumeration, Phone identification metadata (IMEI/UUID), Forced 10s GPS tracking cycles, Contact/SMS/Call/Mail scraping, Local storage harvesting, Audio mic recorder. |
| **Lab-RATS** | Web Interface / GUI | • [K4N3CO-LABS/Lab-RATS](https://github.com/K4N3CO-LABS/Lab-RATS) | Lightweight web-controlled administration tool. Implements IPv6 traversal pipelines to bypass standard router/ISP port-forwarding requirements. Engineered to support modern operational layouts up to Android SDK 36 (OneUI 8.5). Includes active OSINT reconnaissance arrays, surveillance listeners, and runtime security testing telemetry frameworks. |
| **LaRAT** | CLI | • c4wrd/LaRat | Message database extraction, Remote screenshot taking, Live camera access, Google Forms phishing integration for password grabbing. |
| **LodaRAT** | Surveillance Vector| N/A | Complete camera/microphone control, Voice call routing metrics, Local file storage traversal, GPS telemetry logging, Application installation, Saved account credential extraction. |
| **LokiDroid** | GUI | N/A | Comprehensive SMS/Call extraction, UI manipulation (Toasts/Browser), Hardware/SIM data, HTTP C2 control layer (bypasses port-forwarding constraints), Multi-bot offline command parsing. |
| Trojan Name | UI / Interface Type | Project Links / Repositories | Core Features & Permissions |
| **Mass RAT** | CLI | • [NYAN-x-CAT/Mass-RAT](https://github.com) | Background SMS harvesting, Call logging pipelines, Local filesystem storage access, Covert camera snapshots. |
| **MMRat** | Exploitation Tool | *N/A* | Specialized accessibility keylogger engine, Real-time screen streaming/recording, Multi-threaded automated ADB execution arrays. |
| **Monokle** | Surveillance Tool | *N/A* | Precise GPS logging, Continuous call and room audio recording, Screen recording frames, Fingerprint/Keylogger asset duplication, Browser/Mail logs, Local SMS/Call synthesis, Root privilege execution shell. |
| **NetWire** | GUI Client | *N/A (Commercial)* | Camera access, Audio capture, Native keylogger, Storage access, File upload/download pipelines, GPS location monitoring. |
| **Nexus** | Banking / Info RAT | *N/A* | Broad file storage parsing, Camera deployment, Ambient audio capturing, Full SMS/Call logging, Remote command shell environment, GPS tracking arrays, Multi-mode keylogger, Real-time financial/banking overlay injection, Crypto wallet access hooks, 2FA authenticator database harvesting. |
| **Nivistealer** | Web-Based Stealer | • [swagkarna/Nivistealer](https://github.com) | Network IP resolution tracking, GPS tracking arrays, Local hardware environment diagnostics, Camera triggers, Clipboard text hijacking, Web panel deployment for fake overlay phishing. |
| **OmniRAT** | GUI | *N/A (Commercial)* | Full remote access shell, File manager, App installation, Widget manipulation, System hardware information, Call/SMS management. |
| **Pegasus** | High-Tier Spyware | • [9aylas/Pegasus-samples](https://github.com)<br>• [jonathandata1/pegasus_spyware](https://github.com) | Storage/Mic/GPS tapping, Screenshots, Calendar database access, IM apps tracking (WhatsApp, Signal, etc.), Contacts/Mail/SMS dumping, Browser history, Baseband/Device configurations. |
| **PounceKeys** | Stealth Keylogger | • [NullPounce/pounce-keys](https://github.com) | Absolute launcher app icon concealment (Stealth mode), Persistent input keylogger engine, Baseband/Hardware identity collection, Live application notification harvesting, Clipboard framework memory scraping. |
| **Pupy** | CLI | • [n1nj4sec/pupy](https://github.com) | Cross-platform payload, Text-to-speech injection, Dual webcam (front/back) snapshots, GPS tracking arrays. |
| **Rafel RAT** | Modular Botnet | • [swagkarna/Rafel-Rat](https://github.com) | GPS mapping, Local file harvesting, Camera snapshot hooks, Ambient audio scraping, Phone communication status triggers, [Ransomware module](https://github.com/blob/6398b6ccb48b5039c2ddfc7441ce2adbcc550054/BlackMart/app/src/main/java/com/velociraptor/raptor/InternalService.java#L302) (Storage encryption capabilities), Comprehensive browser history exfiltration, Persistent startup mechanisms. |
| **rdroid** | CLI | • [m301/rdroid](https://github.com) | Contact harvesting, System info, App control, Storage access, Call/Message extraction, Interactive reverse shell. |
| **Rogue RAT** | Spyware Framework | *N/A* | Covert camera triggers, Live ambient audio streaming, Storage directory scraping, GPS location tracking, Native software keylogging engines. |
| **SHConnect** | CLI | *N/A* | Remote camera triggers, GPS tracking, Storage directory traversal. |
| **SpyApp Client** | GUI | • [ghazikr/SpyAppClient](https://github.com) | Notification interception listener (Facebook, WhatsApp, Instagram, Emails), System contacts, SMS monitoring, Call history logs. |
| **SpyNote** | GUI | *N/A (Commercial/Leaked)* | App binding, Storage, GPS, SMS/Calls/Contacts, Camera, Live microphone streaming/recording, Browser history, System hardware data (IMEI, MAC, Carrier), "Fun Panel" interaction. |
| **Steaelite RAT** | Cryptographic Vector | *N/A* | Persistent background keylogger engines, Local directory architecture harvesting, Integrated system locking/Ransomware modules. |
| **Strandhogg** | Vulnerability Exploit| *N/A* | Task-affinity session hijacking, Comprehensive app log mining, Broad Android runtime permission acquisition via injection. |
| **StrongPity** | APT Spyware Vector | *N/A* | Persistent GPS background tracking, Local file structure mapping, Phone system operations tracking, Boot-persistence hooks, Detailed carrier/network metadata exfiltration. |
| **TalentRAT** | CLI / Payload | • [honglvt/TalentRAT](https://github.com) | Core SMS monitoring, Remote call generation, Contact extraction, Continuous GPS polling, Real-time camera frames and microphone audio tracking. |
| **TearDroid PHP** | PHP Web Panel | • [ScRiPt1337/Teardroid-phprat](https://github.com) | Contacts, SMS, and active system service queries, Device location extraction (Active window constraint on SDK 29+), Dynamic shell command pipelines (e.g., `findphno`, `findx:pdf`), Wallpaper manipulation, Forced calls and SMS generation. |
| **TecSpy** | Administrative RAT | • [bmshifat/TecSpy](https://github.com) | Comprehensive communication harvesting (SMS, Calls, Contacts), Active GPS location tracking, Local filesystem manipulation, System notification stream capturing, Clipboard memory scraping, Remote administrative ADB command execution. |
| **TeleRAT / IIRAT**| Telegram C2 Interface| *N/A* | Clipboard hijacking, Process tracking, SMS/Contacts theft, Storage access, Microphone/Camera scraping, Device Admin screen capture, Vibration injection. |
| **TheFatRAT** | CLI / Payload Generator | • [Screetsec/TheFatRat](https://github.com) | Arbitrary command execution, Process manipulation, Camera snapping/streaming, Microphone capture. |
| **Triout Framework**| Framework | *N/A* | Automatic voice call recording/exfiltration to C2, SMS/Call log interception, Persistent media theft, Stealth app-icon hiding. |
| **UnknownRAT** | GUI | *N/A* | Storage access, Custom Android deployment tools (photo snap, screenshot), Audio recording. |
| **WH-RAT** | GUI Panel | • [wh-Cyberspace/WH-RAT](https://github.com) | Leaked variant structurally tied to SpyNote/NjRAT architectures. (Detailed telemetry payloads under expansion). |
| **Xenomorph / GODFather / PixPirate / Sova / Zanubis / BingoMod / TrickMo / BlankBot / Vultur / Octo2 / Medusa** | Advanced Banking Trojans | *N/A (Active Threat Campaigns)* | Complete Device Takeover (ATS / Accessibility Services Abuse), Persistent Device Administrator escalation, External/Internal storage traversal, Direct automated ADB framework execution, Complete text tracking (SMS, Web notification mirroring), Installed app enumeration, Real-time automated injection templates (Phishing/Overlays), Bypasses standard biometric/PIN locks. |
| **ZeroDayRAT** | Stealer Vector | *N/A* | Real-time SMS interception, Call routing details extraction, Active input keylogger module, Camera deployment, Microphone environment scraping, Baseband device profiles enumeration, Cryptographic wallet asset stealer. |

---

## 🔱 Project Evolution & Acknowledgments

This repository is an updated, restructured, and actively maintained evolution of the original project by [wishihab](https://github.com) (originally hosted at `wishihab/Android-RATList`). 

### Why this Fork exists:
* **Active Maintenance:** Tracking modern Android threats up to Android SDK 36 (OneUI 8.5+).
* **Enhanced Scannability:** Restructured from loose bulleted lists into high-density Markdown directories.
* **Telemetry Data:** Integrating deeper structural permissions, capability matrices, and architectural markers.

If you are looking for the original, legacy codebase or initial data layers, you can visit the upstream repository [here](https://github.com/Android-RATList).

---

## 🤝 Contributing to the New Directory

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
