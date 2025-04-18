# Download multiple Youtube Videos at once!
A short and easy code to download multiple Youtube videos, if you already have their URLs saved


The following guide is for windows. Although, you can use the code for linux too. The only difference is to download/install FFmpeg in Linux. 

1. Install yt-dlp (if not already installed):
Open Command Prompt (cmd) and run:

```
pip install yt-dlp
```

2. Download FFmpeg (Required for proper MP4 conversion):
Download FFmpeg from **https://ffmpeg.org/download.html**
Under the "Windows" section, click on "Windows builds from gyan.dev" (or another trusted source).
Download the "ffmpeg-git-full.7z" or "ffmpeg-release-full.7z" file.
Extract the downloaded .7z file using 7-Zip or WinRAR.
Rename the extracted folder to "ffmpeg" for easy access.
Move it to a convenient location like: C:\ffmpeg

> Extract it and add its bin folder to System PATH.
Press Win + R, type sysdm.cpl, and hit Enter.
Go to the Advanced tab → Click Environment Variables.
Under System Variables, find and select Path, then click Edit. Click New, and add:
```
C:\ffmpeg\bin
```
Open Command Prompt (Win + R, type cmd, and hit Enter) to verify the installation (this is crucial)

Type:
```
ffmpeg -version
```

3. Save the given script "main" as {whatevername}.py

4.  Run the script on CMD (administrative permissions are a good to have!)


In case of any difficulty, contact me or just ask Chatgpt!

