rtlwifi_new
===========

A repo for the newest Realtek rtlwifi codes.

This code will build on any kernel 3.0 and newer. It includes the following drivers:

rtl8192ce, rtl8192se, rtl8192de, rtl8188ee, rtl8192ee, rtl8723ae, rtl8723be, and rtl8821ae.

<b>to use it on ubuntu :</b><br>
1. clone the repository<br>
2. go to folder<br>
3. <code>"make"</code><br>
4. <code>"sudo make install"</code><br>


Note You will need to reinstall the driver after each kernel upgrade.

Update I made a DKMS version of same driver. It can be installed by

<code>sudo add-apt-repository ppa:hanipouspilot/rtlwifi</code><br>
<code>sudo apt-get update</code><br>
<code>sudo apt-get install rtlwifi-new-dkms</code><br>

If you are on Ubuntu 14.04 or 15.04, I recommend to upgrade linux-firmware from same ppa.

<code>sudo apt-get install linux-firmware</code><br>


