# Introduce
This document explains how to flash and update an image.

# Download firmware and tool
- Download the Doron-Velta-V1.img.xz archive and extract it using 7-Zip.
- Download balenaEtcher, Official Github: https://github.com/balena-io/etcher/releases/tag/v2.1.7

# Flash Image
- Prepare a MicroSD card (minimum 16GB, Class 10 or faster) and connect it to your PC.
- Launch balenaEtcher, click "Flash from file", and select the extracted Doron-Velta-V1.img.xz file.
<p align="left">
  <img src="./Images/file.png" width="560" height="360">
</p>
- Select the disk for the inserted SD card.
- Click to burn now
<p align="left">
  <img src="./Images/disk.png" width="560" height="360">
</p>

# Update
Power off the FYSETC-Doron_Velta machine and insert the SD card. Turn on the power, and the screen will show "Updating..." until completion. 
<p align="left">
  <img src="./Images/sd.png" width="560" height="380">
</p>

Once the update is finished, power off the machine to remove the SD card safely.

