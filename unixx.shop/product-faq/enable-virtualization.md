---
description: >-
  This section includes a brief guide on how to enable virtualization in your
  BIOS/UEFI to ensure proper software functionality and prevent crashes.
icon: vr-cardboard
---

# Enable Virtualization

## How to Enable Virtualization (If Disabled)

If your software is crashing or not launching, virtualization might be turned off on your system. Your software may also require it to function properly. Here's how to check and enable it:

{% stepper %}
{% step %}
### **Check If Virtualization Is Enabled**

* Open **Task Manager** (search for it in your Windows search bar).
* Go to the **Performance** tab.
* Click on **CPU** on the left sidebar.
* Look for **Virtualization** on the bottom right.

If it says **Enabled**, you're good to go — you can skip this guide.\
If it says **Disabled** or is missing, continue to the next step.
{% endstep %}

{% step %}
### **Enable Virtualization in BIOS/UEFI**

To enable it, you'll need to access your BIOS/UEFI settings:

* Restart your PC.
* As it boots, repeatedly press the key to enter BIOS — usually **Delete**, **F2**, or **F10** (it depends on your motherboard).
* Look for a setting called **Virtualization Technology**, **Intel VT-x**, or **AMD-V**.
* Set it to **Enabled**, then save and exit BIOS.

**Not Sure Where to Find It?**

Search on Google:\
`"Your motherboard model" how to enable virtualization in BIOS`

Example:\
`MSI B550 how to enable virtualization in BIOS`
{% endstep %}
{% endstepper %}
