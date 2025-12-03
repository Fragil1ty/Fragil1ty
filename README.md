
## Fragility's tweaks, settings & more.

So this guide overs "advanced" PC optimisation settings that 'should' be commonly known. This guide aims to cover everything that you would get out of a normal optimisation appointment so that a.) It's going to save you time and money and b.) You're educating yourself to hopefully further pass on this knowledge. If everyone knows this stuff (which can be learnt in a 1-2 week period) then you don't have to trust someone else to do it for you.


## Build/part recommendations?
[Build Recommendations](https://uk.pcpartpicker.com/user/Fragil1ty/saved/)

## Timings
[Current Timings](https://ibb.co/JRhHkLVf) </br>

## Operating System

* Linux? Still not an option in 2025. If you're on a full AMD system and you are really fed up of the direct that Microsoft is heading towards i.e. heavy AI integration, heavy telemetary and tracking based o/s? then sure, you could switch to Linux but you'll be FAFO'ing around a lot more than you would on Windows. Furthermore, you'll have to sacrifice playing some, if not all anti-cheat based games such as League, Valorant, BF6 and more. Not to mention if you're an NVIDIA user, a high-end NVIDIA user (5070Ti -> 5090) you're going to be looking at horrendous peformance vs using that GPU on Windows due to driver limitations. It's not worth the effort. Unless you have a very specific use-case for Linux? I wouldn't bother.

* Windows 10 still viable in 2025? Personally, I don't believe so. Everyone that I know who was a hardcore Windows 10 main has now converted and made the switch to Windows 11. There are a lot of negatives where W11 is concerned but most if not all can be rectified with tweaks and/or adjustments. But if you're switching to Windows 11, my recommendation is W11 - 24H2 LTSC, it's less bloat-heavy, more stripped and just a better version of Windows, kind of how it was meant to  be shipped.

* Windows 10 is more resilient when it comes to tweaks and it can be stripped down to its bones without sacrificing functionality, while Windows 11 needs UWP app support, StateRepository, DWM and many other things running to ensure nothing breaks.

## Windows Tweaks

* Firstly, install whatever version of Windows you prefer, as I stated above, I would recommend a fresh install of W11 - 24H2 LTSC. This is what I have been dailying for a long time and 'feels' the best out of all other operating systems tested, custom or stock. I would stay away from Custom ISO's in 2025 as it's been proven by Freethy (https://github.com/FR33THYFR33THY/Debunking-Custom-ISOS-And-Windows-Optimizations) that there is no major differences (from a performance point of view) between any of them, so do yourself a favour and just avoid the hassle.

* Install Windows without an internet connection to ensure that all of the update services and automatic updates have been disabled. Make sure to pause Windows updates, make sure to install your GPU drivers and Chipset drivers before enabling Internet access.

* Disable audio enhancements in the Sound control panel. Useless and doesn't offer any benefits. Just set to 2-channel, 24-bit 48hz and away you go.

**Power plans?**

I used to be all for custom Powerplans but nowadays, there isn't much point. But if you need to install a custom Powerplan for AMD/X3D, refer to the following: https://github.com/Fragil1ty/Fragil1ty/blob/main/amd.pow
<br><br>But in reality, Ultimate Performance (which comes pre-installed with Windows) is more than adequate. 

**Autoruns:** unhide Windows services (more can be disabled but these are the ones I find safe to disable, even though my NTLite preset and .bat scripts disable all of the unndeeded ones)

* **Services**: disable Appinfo, ApMgmt, AppReadiness AppXSvc, ApxSvc, BITS, Bluetooth related, CDP services, ClipSVC, CredentialEnrollment services, DeviceFlow services, KeyIso, PlugPlay, sppsvc StorSvc, UDK related, WMI, Wpn services
* **Drivers**: disable amd related (if not needed for AMD), AppleSSD, Bluetooth related, HidBatt, HidBth, i8042prt, Microsoft_Bluetooth, RFCOMM, swenum, WacomPen
* Device Manager: View -> Devices by type
For your storage device under Disk drives, turn off write caching by going into Properties -> Policies

**Typical post installation process?**

1. Install updates > Install drivers > Install chipset > Pause updates
2. Use installation scripts from the likes of Fr33thy (https://github.com/FR33THYFR33THY) and follow the step-by-step for his Ultimate Windows Optimisation guide. It's simple, it's effective and it's idiot-proof (kind of).
3. Apply any further tweaks that you deem acceptable i.e. custom powerplans, hosts blocking (asus/razer), telemetary removal, edge removal etc.
4. Apply your GPU tweaks (see below for recommended settings/.NIP profile)
5. Profit.

## Best BIOS settings - AMD (AM5)

There is a lot of misinformation circuluating the internet on what the "best" BIOS settings are for AMD. I'm here to clear up what the best settings actually are. Refer to the screenshots below. 

## Best NVIDIA Control Panel Settings
[1](https://ibb.co/ZpmZrdWC) 
[2](https://ibb.co/nMrq7LgP) 
[3](https://ibb.co/4Rp040Kx) 
[4](https://ibb.co/WND66RTK) 

If you would like to automate this process, then you can download my .nip profile [here](https://github.com/Fragil1ty/Fragil1ty/blob/main/FRAGOS2.nip). Simply head to: (https://github.com/Orbmu2k/nvidiaProfileInspector/releases) > download the latest release > unzip > NVPI > import user defined profiles > apply changes and you're done.

## Twitter
[https://x.com/fragilitytweaks](https://x.com/fragilitytweaks)</br>


<!--
**Fragil1ty/Fragil1ty** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
