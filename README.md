# PlayStation Home 1.86 HEN Version

<p align="center">
    PlayStation Home 1.86 Offline Client compatible with HEN/HFW Systems.
</p>

![screenshot_2021_11_06_21_51_42](https://user-images.githubusercontent.com/67494727/140632062-ed93bea0-f144-4e7a-ac98-a57d564db1a4.png)

# About this repo:

![PlayStationÂ®Home Developer   HEN-QA Launcher](https://user-images.githubusercontent.com/67494727/140632031-0ee81fb5-b2a6-4a5c-bd81-06a05520a3b2.png)

- currently wip~

Greetings Homesters, as the Destination Home Team is working on a online server emulation solution, I've decided to tap back into offline client for just a bit. As some of you guys might recollect on how tedious it was to boot into the offline client for Home this repo will solve *most* issues for users who want to play Home in a offline state with out the use of a `DEX/DECR/DECH PS3` along with [ProDG Target Manager](https://en.wikipedia.org/wiki/ProDG_(software)). In comparison to the original offline builds, this HEN compatible build allows users to boot into Home with the use of [multiMan](https://store.brewology.com/ahomebrew.php?brewid=24) or [webMan](https://github.com/aldostools/webMAN-MOD/releases). Currently this side-project is still in it's early phases as there are many "hoops" for the team to consider, when developing this client such as the overall client size, scene compatability, editing key files so Home won't crash, etc.


# Prerequisites:

- Any PS3 with HEN/HFW Installed. I recommend being on the lastest version which is 4.88 as of `11/7/2021`. If your not on HEN/HFW you can watch my offical tutorial guide [here](https://youtu.be/oJWhmBwlCcQ).
- Download the latest release PKG & `GAMES` app folder from the releases [page](https://github.com/DestinationHome/PlayStation-Home-Hen-Offline/releases).
- A FAT32 USB Stick to install [PlayStation Home Developer | HEN-QA Launcher](https://github.com/DestinationHome/PlayStation-Home-Hen-Offline/releases/tag/0.01) *note this is a pre-release build*

# How to install this test client:

**1.** You will need to be on a HEN/HFW PS3 system. For more information on how to install HEN on your device click this tutorial guide [here](https://www.youtube.com/watch?v=oJWhmBwlCcQ). Additionally, you will need a USB that is formatted to `FAT32` to transfer over the `PlayStation Home Developer | HEN-QA Launcher` & the `PlayStation Home Developer | HEN-QA.PKG` file.

**2.** As well you will need to have either [multiMan](https://store.brewology.com/ahomebrew.php?brewid=24) or [webMan mod](https://github.com/aldostools/webMAN-MOD/releases) installed, as your going to be launching the `PlayStation Home Developer | HEN-QA Launcher` application.

**3.** Once you have downloaded the necessary files from this release, you will first drag the `PlayStation.Home.Developer.HEN-QA-PreRelease.pkg` to the `ROOT` of your USB stick. Next, you will unzip the file `PlayStation.Home.Developer.HEN-QA.Launcher.zip` and drag the `GAMES` folder to the ROOT of your USB. Alternatively, you can create a folder on your USB label `PS3ISO` & drag the new [NPIA00010.ISO](https://github.com/DestinationHome/PlayStation-Home-Hen-Offline/blob/main/ISO/NPIA00010.ISO) file to the following directory `PS3ISO/NPIA00010.ISO`.


https://user-images.githubusercontent.com/67494727/140634954-ab899ffb-06aa-447c-9155-da2d3ffc8664.mp4

**4.** With HEN Enabled, on your PS3. Go to `★ Package Manager > Standard > PlayStation Home Developer HEN-QA-PreRelease.PKG` to install the PKG. Note this will take a couple of minutes as it's extracted a bunch of files. Once that is done, head over to multiMan & make sure your USB is still in your PS3. Go to the `Games` columns and you can see the `PlayStation Home Developer | HEN QA Launcher` click `X`.

**5.** Once your back into XMB simply click the launcher and wait for Home to boot up & of course select `Offline`.

![PlayStation®Home Developer   HEN-QA Launcher_1](https://user-images.githubusercontent.com/67494727/140634849-3eab60fa-5768-47cd-b0d0-f45264ef43ea.png)

# 2-Do List For Build:

- [ ] Release a core build with core spaces from the SCEA region of Home e.g., Action Disctrict, The Hub, Pier Park, etc.
- [ ] Change the EBOOT, to have the ID Name as "me" instead of "Nagato"
- [x] Implement screenlinks poster & video content for core spaces. (Might either utilize git as a "CDN Solution" or bake videos within the build).
- [ ] Possibly make update packages so users can download new content such as spaces.

# Build Change Logs:

`As of 11/12/2021`

### Changelog 0.2

<p align="center">
    PlayStation Home Developer | HEN-QA Launcher ISO Version
</p>

![Screenshot 2021-11-12 17-42-42](https://user-images.githubusercontent.com/67494727/141574720-07016976-e63e-4e19-8283-718d61e20287.png)

- CFW/HEN/DECR Systems are now supported.
- PlayStation®Home Developer | HEN-QA Launcher has been converted into a `.ISO` file. Users can now boot home from an external USB that is either `NTFS/EXFAT/FAT32`.
- Destination ID's have been added.
- Hubstart.txt has been updated to read "core" files for objects hosted at this github URL
- Added 2 new public space scenes `Central Plaza & Mall "SCEA Marketplace"`

![img0001](https://user-images.githubusercontent.com/67494727/141598974-98d74a1c-0da8-47c1-bbdb-825e9be784fa.PNG)

- Listen At Home Music Player has been implemented for Central Plaza.

https://user-images.githubusercontent.com/67494727/141604483-6d3c1cb6-3298-4adf-bbe6-202c310851ba.mp4

- Add screenlinks e.g., posters & videos for Central Plaza & Mall.

![img0003](https://user-images.githubusercontent.com/67494727/141599576-79f43fe0-f413-40fb-909a-22cefc2d2a29.PNG)

- Core files, are now downloaded from `https://github.com/DestinationHome/PlayStation-Home-Hen-Offline/tree/main` to save space.


### Changelog 0.1

`As of 11/6/2021`
- Released test client ```PlayStation Home Developer | HEN-QA Launcher``` to show proof of concept.
- Build only has an early revision of `SCEE Bowling Alley` aka Game Space.
- There are no games nor screenlinks for this scene as it was just for testing purposes. + This scene is not fully comptaible with 1.86, thus their is missing models for the TV screens, as you can see from the picture below:

![PlayStation®Home Developer   HEN-QA Launcher](https://user-images.githubusercontent.com/67494727/140633633-fd40075a-df5e-432c-8901-c2c6e79bd285.png)

