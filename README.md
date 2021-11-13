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

# 2-Do List For Build:

- [ ] Release a core build with core spaces from the SCEA region of Home e.g., Action Disctrict, The Hub, Pier Park, etc.
- [ ] Change the EBOOT, to have the ID Name as "me" instead of "Nagato"
- [ ] Implement screenlinks poster & video content for core spaces. (Might either utilize git as a "CDN Solution" or bake videos within the build).
- [ ] Possibly make update packages so users can download new content such as spaces.

# Build Change Logs:

### Changelog 0.2

<p align="center">
    PlayStation Home Developer | HEN-QA Launcher ISO Version
</p>

![Screenshot 2021-11-12 17-42-42](https://user-images.githubusercontent.com/67494727/141574720-07016976-e63e-4e19-8283-718d61e20287.png)

- Now supporting CEX/DEX/HEN PS3's
- Added 2 new public space scenes `Central Plaza & Mall "SCEA Marketplace`

![img0001](https://user-images.githubusercontent.com/67494727/141598974-98d74a1c-0da8-47c1-bbdb-825e9be784fa.PNG)

- Listen At Home Music Player has been implemented for Central Plaza. 

- Add screenlinks e.g., posters & videos for Central Plaza & Mall.

![img0003](https://user-images.githubusercontent.com/67494727/141599576-79f43fe0-f413-40fb-909a-22cefc2d2a29.PNG)

- Core files, are now downloaded from `https://github.com/DestinationHome/PlayStation-Home-Hen-Offline/tree/main` to save space.






### Changelog 0.1

`As of 11/6/2021`
- Released test client ```PlayStation Home Developer | HEN-QA Launcher``` to show proof of concept.
- Build only has an early revision of `SCEE Bowling Alley` aka Game Space.
- There are no games nor screenlinks for this scene as it was just for testing purposes. + This scene is not fully comptaible with 1.86, thus their is missing models for the TV screens, as you can see from the picture below:

![PlayStation®Home Developer   HEN-QA Launcher](https://user-images.githubusercontent.com/67494727/140633633-fd40075a-df5e-432c-8901-c2c6e79bd285.png)

