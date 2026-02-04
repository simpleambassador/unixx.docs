---
description: >-
  This documentation provides simple support and fixes for Amped Internal COD
  software.
---

# 🆘 Support

## Common Issues

1. Failed to Load the Vulnerable Driver
   * [Download the fix tool](https://mega.nz/file/hLFnUBDZ#Y_oMmNgAV2jEW78uTToU39EQ_zXTvPxUAkqLCg4pXmo)
   * Run as Administrator
   * When prompted with (Y/N), type Y and press Enter
   * Restart your PC
2. BSOD (Blue Screen of Death)
   * [Download the BSOD fix tool](https://mega.nz/file/cDVW2ByI#DMaPKdIAcm7ELWLr2CS5hrevmLdUabZ3R5TSth1cDs4)
   * Run as Administrator
   * Type Y when asked
   * Restart your PC
3. Memory Integrity
   * Open Windows Security
   * Go to Device Security → Core Isolation Details
   * Turn off Memory Integrity
   * Restart your PC
4. Driver Errors (e.g., C0000041)
   * Uninstall Valorant and Riot Vanguard
   * Restart your PC
5. VCRUNTIME Error
   * [Download Visual C++ All-in-One](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/)
   * Run installer as Administrator
   * Select Install All
6. D3DCOMPILER\_43.dll Missing
   * [Download DirectX Runtime](https://www.microsoft.com/en-us/download/details.aspx?id=35)
   * Install and restart your PC
7. Error 202 – Vulnerable Driver Blocklist
   * Open Command Prompt as Admin
   * Run:\
     `reg add HKLM\SYSTEM\CurrentControlSet\Control\CI\Config /v VulnerableDriverBlocklistEnable /t REG_DWORD /d 0x000000`
   * If “Access Denied” appears, run:\
     net user administrator /active:yes
   * Restart your PC
8. Common Error Codes
   * 0x80002003 → Restart your PC
   * 0xC0000041 → Uninstall Riot Vanguard
   * 0xC035001E → Enable Virtualization in BIOS
   * 0xC0000365 / 0xC0000138 / 0xC0000013A → Invalid Windows Version
   * 0xC0000043 → Disable other spoofers like Woofer
   * 0xC0000603 → Use the vulnerable driver fix
9. Game Crashing Fix – Verify Files
   * Open Battle.net
   * Select Call of Duty → Options → Scan and Repair
   * Click Begin Scan
   * Relaunch COD after scan completes
10. “Application Has Unexpectedly Stopped Working”
    * Disable NVIDIA Reflex and On-Demand Texture Streaming
    * Update GPU drivers (NVIDIA/AMD)
    * Restart your PC
11. Battle.net File Wipe
    * Press Windows + R, type %appdata%, press Enter
    * Go to the Battle.net folder and delete all contents
12. Steam Cleanup
    * Verify integrity of game files
    * Press Windows + R, type %temp%, delete all contents
    * Empty Recycle Bin
    * Relaunch game
13. System Check for Random Crashing
    * Run [Support Tool.exe](https://mega.nz/folder/FykX1RIZ#bJcWRx5kv8SxKeAUpwRMmw/file/MqkHSDjA)
    * Ensure the following states:\
      Virtualization: **Enabled**\
      Hyper-V: **Enabled**\
      Secure Boot: **Disabled**\
      Tamper Protection: **Disabled**\
      Real-Time Protection: **Disabled**\
      Core Isolation: **Disabled**
    * No conflicting services or folders should be found
14. Shadowban & Ban Types
    * Check [status](https://support.activision.com/ban-appeal)
    * Shadowban: Caused by reports, lasts up to 7 days
    * Temp Ban: \~30 days, usually caused by unlocker or unreleased items
    * Perma Ban / HWID Ban: Detected usage or flagged system, not recoverable
15. Shadowban Avoidance Tips
    * Avoid playing obvious or rage-style
    * Always spoof if you were previously banned
    * Don’t unlock unreleased skins or cosmetics
    * Use aged or clean accounts when possible
