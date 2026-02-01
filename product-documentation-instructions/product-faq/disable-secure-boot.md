---
description: >-
  This section includes a brief guide on disabling Secure Boot to help some
  software run properly. This step is optional but recommended if you play other
  games besides Call of Duty.
---

# 🔓 Disable Secure Boot

## How to Disable Secure Boot (If Enabled)

If your software won’t load or is being blocked during injection, Secure Boot might be interfering. Your software may also require Secure Boot to be turned off to function properly. Here's how to check and disable it:

{% stepper %}
{% step %}
### Check If Secure Boot Is Enabled

* Press **Windows + R**, type `msinfo32`, and hit Enter.
* In the System Information window, find **Secure Boot State**.

If it says **Off**, you're good — you can skip this guide.\
If it says **On**, continue with the steps below
{% endstep %}

{% step %}
### Disable Secure Boot in BIOS/UEFI

To turn it off, you’ll need to access your BIOS/UEFI settings:

* Restart your PC.
* During boot, press the key to enter BIOS — usually **Delete**, **F2**, or **F10** (varies by motherboard).
* Look for a tab like **Boot**, **Security**, or **Authentication**.
* Find **Secure Boot** and set it to **Disabled**.
* Save changes and exit BIOS.

_Note:_ If you can't disable Secure Boot, you may need to set a **Supervisor/Admin password** in BIOS first, or switch Boot Mode from **UEFI to Legacy/CSM** (varies by system).

**Not Sure Where to Find It?**

Search on Google:\
`"Your motherboard model" how to disable secure boot in BIOS`

Example:\
`MSI B550 how to disable secure boot in BIOS`
{% endstep %}
{% endstepper %}
