# Termux-YTD2.0
### A light weight tool to download any kind of Video, Music or shorts from Youtube with 2 clicks on your phone using Termux.
<hr>

Termux-YTD2.0 is a Upgraded version of Termux-YTD, Since Youtube-dl really slow know Termux-YTD is still downloading things but really slow and Termux-YTD2.0 overcomes that problem. I have added all the previous features of Termux-YTD as well as added youtube shorts support. So now while watching shorts you can just share any shorts with termux and it will download it at a lightning speed.

<p align="center">
<img src="https://user-images.githubusercontent.com/32749921/197327887-c4aca7fc-e475-4175-a289-08af6dceb340.png">
</p>
  
<p align="center">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/khansaad1275/Termux-YTD2.0?style=for-the-badge">
  <img src="https://img.shields.io/github/issues/khansaad1275/Termux-YTD2.0?color=violet&style=for-the-badge">
  <img src="https://img.shields.io/github/forks/khansaad1275/Termux-YTD2.0?color=teal&style=for-the-badge">
  <img src="https://img.shields.io/github/stars/khansaad1275/Termux-YTD2.0?style=for-the-badge">
</p>


### Installation:

```
pkg install git 
```
```
git clone https://github.com/HYPER12755/YTD-2.0.git
```
```
cd Termux-YTD2.0
```
```
bash install.sh
```
### script.if you want to download in maximum quality 

```
mkdir -p /storage/emulated/0/Youtube && mkdir -p $HOME/bin && echo 'yt-dlp -N 8 --no-part --continue -f "bv*+ba/b" --merge-output-format mp4 -o "/storage/emulated/0/Youtube/%(title)s.%(ext)s" "$1"' > $HOME/bin/termux-url-opener && chmod +x $HOME/bin/termux-url-opener
```
<br>
<br>

# access:
to access downloaded files go to your device home and you will find a file named Youtube. inside the Youtube folder you will find all videos.

### Usage:
Detaild post on How to use :https://www.learntermux.tech/2022/10/Termux-YTD2.0.html

Basic Idea of Usage: <br>
[1] While Using Youtube on your phone tap on share button of any video and and select termux. <br>
[2] Termux will open automatically and now just select the quality of the video.<br>
- after this the video will be downloaded automatically. if you are downloading shorts then you don't have to do 2nd step, just share it and it will be downloaded in one click.

### Features:
- Download Shorts
- See The Downloading Process.
- Download any Video in Just 2 Clicks.
- Select the Quality Of your Video.
- Downlaod Mp3 Version of the Video.

<br>
<br>
