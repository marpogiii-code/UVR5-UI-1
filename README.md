<h1 align="center"><b> 🎵 UVR5 UI BY MAR 🎵 </b></h1>
<div align="center">
</div>
<div align="center">

</div>
 
<div align="center">

</div>

## Features: 
* User Friendly Interface
* All VR Arch Models
* All MDX-NET Models
* Demucs v4 Models
* MDX23C Models
* Mel-Band Roformer Models
* BS Roformer Models
* Music Source Separation Models
* VIP Models
* Separation of an audio/video from all sites supported by [yt_dlp](https://github.com/yt-dlp/yt-dlp). Check the complete list [here](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md).
* Batch Separation
* Available in multiple languages
* Windows/Linux support

## Requirements

### Hardware Requirements:
* Nvidia Series 2000 (RTX) or higher.
* At least 10Gb of disk space. 

> [!NOTE]  

### Prerequisites:
- Git. You can download Git [here](https://git-scm.com/downloads).
- FFmpeg. You can download FFmpeg [here](https://www.ffmpeg.org/download.html)
- For linux users, run this command on an terminal: (Debian and Ubuntu users): `sudo apt install ffmpeg git` (For Arch linux users): `sudo pacman -S ffmpeg git` (For Fedora users): `sudo dnf install ffmpeg git`
(Some distributions already come with Git and FFmpeg preinstalled so this step may be optional.)

> [!IMPORTANT]  
> FFmpeg has to be added to the PATH. (only needed on Windows)

## Getting Started

Clone the repository (git needed) or download the source code of the latest release [here](https://github.com/marpogiii-code/UVR5-UI-1/releases)

```
git clone https://github.com/marpogiii-code/UVR5-UI-1.git
```

Then continue with the steps described below

### 1. Installation

Run the installation script based on your operating system:

- **Windows:** Double-click `UVR5-UI-installer.bat` (DONT RUN AS ADMINISTRATOR 🚧).
- **Linux:** Run `UVR5-UI-installer.sh` with `chmod +x UVR5-UI-installer.sh` and `./UVR5-UI-installer.sh`.

### 2. Running UVR5 UI

Start UVR5 UI using:

- **Windows:** Double-click `run-UVR5-UI.bat`.
- **Linux:** Run `run-UVR5-UI.sh` with `chmod +x run-UVR5-UI.sh` and `./run-UVR5-UI.sh`.

### 3. Update UVR5 UI (If you want/need it)

Update UVR5 UI using (git needed):

- **Windows:** Double-click `UVR5-UI-updater.bat`.
- **Linux:** Run `UVR5-UI-updater.sh` with `chmod +x UVR5-UI-updater.sh` and `./UVR5-UI-updater.sh`.

### 4. Debug (If you want/need it)

Check the status of audio-separator core:

- **Windows:** Double-click `status-checker.bat`.
- **Linux:** Run `status-checker.sh` with `chmod +x status-checker.sh` and `./status-checker.sh`.

## Docker Instance

A more technical level is required for this type of use. You can use this Jupyter notebook to initialize UVR5 on virtual machines with GPU. This will install the entire UVR5 from the main branch of GitHub.

### Requirements/Recommendations
- Use the docker image `>= ubuntu/ubuntu:20.04`
- At least `20 GB of storage minimum.` (Add more space for your models/training)
- Use Jupyter `>= 7.3.1`
- Configure port forwarding `9999 (UVR5-UI GUI)`
- Install necessary drivers to use the GPU

