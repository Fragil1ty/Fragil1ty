
## Fragility's tweaks, settings & more.

So this guide overs "advanced" PC optimisation settings that 'should' be commonly known. This guide aims to cover everything that you would get out of a normal optimisation appointment so that a.) It's going to save you time and money and b.) You're educating yourself to hopefully further pass on this knowledge. If everyone knows this stuff (which can be learnt in a 1-2 week period) then you don't have to trust someone else to do it for you.

## Build/part recommendations?
[Build Recommendations](https://uk.pcpartpicker.com/user/Fragil1ty/saved/)

## Timings
[Current Timings](https://ibb.co/PGStyy0L) </br>

## Operating System

* Windows 10 is more resilient when it comes to tweaks and it can be stripped down to its bones without sacrificing functionality, while Windows 11 needs UWP app support, StateRepository, DWM and many other things running to ensure nothing breaks. With that being said, due to W10 being EoL, I wouldn't use anything other than Windows 11 for my daily machine.

## Windows Tweaks

* Firstly, install whatever version of Windows you prefer, as I stated above, I would recommend a fresh install of W11 - 25H2 Home or Professional as this is what has proven to be the more reliable for me personally. If you want to streamline the process and use a custom OS which I will always be in favour of, providing stability is at the forefront of the .iso or .pbx project, then I would definitely use one of the following: FSOS, CactusOS or SynergyOS.

* Use an autounattend file to automate as much of the installation process as possible, if you don't know what an autounattend file is? Google is your best friend but there are many out there and they provide a much easier and streamlined experience to the reinstallation process. 

* Disable Defender (common sense is your best anti-virus), disable audio enhancements in the sound control panel, I personally dislike anything interfering with my audio experience I consider the toggle to be useless and lacking benefits. Best bet is to just set to 2-channel, 24-bit 48khz and away you go.

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
2. Use installation/post-install scripts of your own choosing. [Zoicware](http://github.com/zoicware) is a fantastic place to start or if you would rather install a custom, pre-tuned/deblaoated operating system? Then refer to the above statement made earlier.
3. Apply any further tweaks that you deem acceptable i.e. custom powerplans, hosts blocking (asus/razer), telemetary removal etc.
4. Apply your GPU tweaks (see below for recommended settings/.NIP profile)
5. Profit.

**Bonus**

6. One thing that I always do these days is remove Windows Defender, I just don't like using it or having it on my computer, it feels invasive and as we all know. The best Antivirus is common sense, so what to do about it? Well there are scripts in both Fr33thys advanced folder or for a more streamlined and easier method, you can always refer to Zoicware's Defender Pro tools as seen here: https://github.com/zoicware/DefenderProTools

## Best BIOS settings - AMD (AM5)

There is a lot of misinformation circuluating the internet on what the "best" BIOS settings are for AMD. I'm here to clear up what the best settings actually are. Refer to the screenshots below. 

## Best NVIDIA Control Panel Settings
[1](https://ibb.co/ZpmZrdWC) 
[2](https://ibb.co/nMrq7LgP) 
[3](https://ibb.co/4Rp040Kx) 
[4](https://ibb.co/WND66RTK) 

If you would like to automate this process, then you can download my .nip profile [here](https://github.com/Fragil1ty/Fragil1ty/blob/main/FRAGOS2.nip). Simply head to: (https://github.com/Orbmu2k/nvidiaProfileInspector/releases) > download the latest release > unzip > NVPI > import user defined profiles > apply changes and you're done.
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
