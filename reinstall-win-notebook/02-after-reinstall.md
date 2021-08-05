# Softwares that need to be reinstalled

## Software development
 *  JDK
 *  Maven
 *  IDEA
 *  VScode
 *  Git
 *  TortoiseGit
 *  NodeJS
 *  npm
 *  bower

## Browsers
 *  Chrome
 *  Firefox


## Tools
 *  Total Commander
 *  Keepass2
 *  Putty
 *  WinSCP
 *  Docker (installed on HyperV, instead of Docket Toolbox)
 *  MySQL Workbanch
   * It needs Microsoft c++ redistributable, it can be downloaded from here: C++ https://support.microsoft.com/hu-hu/help/2977003/the-latest-supported-visual-c-downloads
 *  Xmind
 *  Skype
 *  Slack
 *  RocketChat (?)
 *  Office
 *  Notepad++
 *  VS Code
 *  Clink (for linux-like tab-tab experience in cmd)
 *  Dropbox
 *  Onedrive
 *  Discord
 *  qBittorent

## Tools Optional
 *  Cmder

# Softwares that need to be configured
 * Outlook

 * IDEA 
   *  https://plugins.jetbrains.com/plugin/9562-active-intellij-tab-highlighter 


 * Git
   *  Disable line ending conversion:
git config --global core.autocrlf false

 * Windows
   * Disabling Windows Update Power Management to automatically wake up the system to install scheduled update.
```
1) Start gpedit.msc

2) Computer Configuration => Administrative Templates => Windows Components => Windows Update

3) There is the setting "Enabling Windows Update Power Management to automatically wake up the system to install scheduled updates". Turn it off.
```

   * Disable touchscreen in Windows 10
```
1) In the search box on the taskbar, type Device Manager, then select Device Manager.
2) Select the arrow next to Human Interface Devices and select HID-compliant touch screen.
3) Select the Action tab at the top of the window. Select disable or enable.
```


   * Windows 10 Microsoft Compatibility Telemetry High Disk Usage --- disable telemetry 
https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/
