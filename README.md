Basic guide for securing/hardening your Windows 11 PC

Prerequisites:

Windows 11 Pro

Modern hardware (personal recommendation: AMD Ryzen 5 PRO 5650G, try to use at least a modern CPU), ECC-RAM, shielded network cables (SF/FTP), do no not use a case with plastic side pandels (all metal!, you can also wrap your case with multiple layers of aluminum foil [10 layers at least]) [EM-Shielding], try to avoid WIFI connections (at least use WPA3 if you need WIFI)

Install newest firmware/bios

WARNING: If you mess up any of the following steps start at the beginning!!! Take your time and you only have to do it once.

Windows 11 Configuration:

1. Install Windows without network connection (create a local account). Do not connect to the LAN or Internet yet!!!

2. Install Windows features

<img width="846" alt="install_device_guard_1" src="https://user-images.githubusercontent.com/6840466/149796165-038292f4-dcc8-4f9e-8630-eef65911f4db.png">

<img width="506" alt="install_device_guard_2" src="https://user-images.githubusercontent.com/6840466/149796200-d9ee180d-7b3d-48fa-a19f-7e242b0bd4c0.png">

Reboot pc

3. Install/enable device guard:

<img width="830" alt="Screenshot 2022-01-17 153521" src="https://user-images.githubusercontent.com/6840466/149796019-8281de6a-9c0f-450c-bc54-924415ba509a.png">

4. Configure Application Guard [for smooth brosing experience, if you want more security dont enable following but watching youtube will suck :)]

<img width="1079" alt="install_device_guard_2_2" src="https://user-images.githubusercontent.com/6840466/149801090-3088cfa2-5b18-488c-aa4f-debd6cf4837c.png">

<img width="1076" alt="install_device_guard_3" src="https://user-images.githubusercontent.com/6840466/149801100-4180353e-f4af-4ffb-80b1-9310ef39f988.png">

5. Enable mandatory ASL

<img width="902" alt="mandatory_ASL_1" src="https://user-images.githubusercontent.com/6840466/149796699-4fcaa30a-e6e8-4d15-9ed4-84c0b3688e76.png">

<img width="902" alt="mandatory_ASL_2" src="https://user-images.githubusercontent.com/6840466/149796736-6edda4c8-b96c-466d-b60e-b51da35eaf81.png">

6. Windows Update

- Only allow downloads from Microsoft directly

<img width="902" alt="windows_update_disable1" src="https://user-images.githubusercontent.com/6840466/149802085-1036c454-e0d5-4125-a12e-781ebb388750.png">

<img width="903" alt="windows_update_disable2" src="https://user-images.githubusercontent.com/6840466/149802090-8a33439c-19a0-4e89-989d-6769164a4d57.png">

- Reboot pc to loginscreen and plugin network cable. Do not login yet! If you have connected to the internet before start from the beginning
	Wait till updates are installed (aprox. 10min)

- Go to Windows Update and install the updates which did not get installed before

- Go to Windows Update and install optional driver updates

- Do not install any drivers outside of Windows Update unless necessary!

- Reboot pc

7. Create a normal User Account and use it as default (i prefer local accounts

- Set UAC to maximum

<img width="561" alt="account_1" src="https://user-images.githubusercontent.com/6840466/149799663-becf11ce-c9be-41cf-94d3-8db9d07fb7ba.png">

- Create local User-Account

<img width="845" alt="account2" src="https://user-images.githubusercontent.com/6840466/149799711-7ae48fdf-d489-4075-b127-1d0617fdf51e.png">

<img width="362" alt="account3" src="https://user-images.githubusercontent.com/6840466/149799729-33cf70f2-21df-4968-8d9f-c1bfbc7dcd63.png">

<img width="845" alt="account4" src="https://user-images.githubusercontent.com/6840466/149799744-511e7d03-a4c6-41c5-ba1c-0a1f44a564b9.png">

<img width="510" alt="account5" src="https://user-images.githubusercontent.com/6840466/149799768-6ba85935-27bc-4a2d-8642-d8e25f1bf328.png">

8. Edge-Browser (personal recommendation because of virtualization, you can also use Windows Sandbox [not described in this guide])
- Install Edge updates before opening any websites!!!

<img width="1382" alt="edge1" src="https://user-images.githubusercontent.com/6840466/149796876-cc64066e-efa3-4f52-a319-f173f0fc6f49.png">

- Restart Edge!!! (If you opened any Websites before start at the beginning)

- Configure Edge

<img width="951" alt="edge2" src="https://user-images.githubusercontent.com/6840466/149796981-2e5c5147-8bf0-4739-9cf4-5f68e06adb32.png">

Scroll down

<img width="951" alt="edge2_2" src="https://user-images.githubusercontent.com/6840466/149797142-f6333a60-6d08-4eba-8d97-6aef6f43631c.png">

<img width="951" alt="edge3" src="https://user-images.githubusercontent.com/6840466/149797206-9e1c226f-3f10-4926-9da7-1ab2527fe4bc.png">

- Set flags (flags may change with newer Edge versions)

<img width="960" alt="edge_flags1" src="https://user-images.githubusercontent.com/6840466/149800664-6bc20985-69b7-4030-b7c6-8aaf14416ea0.png">

<img width="960" alt="edge_flags2" src="https://user-images.githubusercontent.com/6840466/149800698-eb33a910-ad12-49e0-8ddb-2d5388c166ce.png">

- Install extensions (Adblocker etc. personal recommendation: Ublock origin)

- Start Microsoft Defender Application Guard and repeat the steps from above

- Install Microsoft Defender Application Guard Companion from Windows Store and add it to your taskbar


Annotations:
- Try to always use Microsoft Defender Application Guard and not the normal Edge-Browser! Unfortanetly it is not always possible and you can not set it as default yet :(

- Also you can not store bookmarks but can still open existing ones. You can use the normal Edge-Browser to manage your bookmarks.

- Try to use Windows Store UWP apps

- Try to avoid apps outside of the Windows Store

- Try to use a VPN

- You can do additional steps for privacy concerns but this should make your Windows 11 PC really hard to hack but you still will be tracked! Nothing is 100% safe. Always install the newest updates and do not do anything illegal!

Pardon me for my bad english but they (political parties in germany) brainwashed me and im just recovering. Had to train for a few years to recover.
See my facebook account https://www.facebook.com/profile.php?id=100070019901989
Also try to use a Pixel 6 with GrapheneOS. Will try to make a guide for it in the future if they do not get me before.

NEVER GIVE UP

THE RESISTENCE WILL NEVER DIE. YOU ARE NOT ALONE.
