# Description

Script converts any video file to a video with "old movie" effect.
Some files from YouTube are downloaded during a process.

# Usage

```
mkfile_old MOVIEFILE DURATION_SECS
```

Note that the script speeds up the source video x2 times (if PTS_RATIO=0.5). So the specified duration
must be twice less than the length of the source video.

View the script source to change source resources.

# Example

https://www.youtube.com/watch?v=hOMuZ8WJrnw
https://www.youtube.com/watch?v=OuUkj7D_2BE

# Packages to install (Ubuntu 14.04)

```
sudo apt-get install youtube-dl
sudo apt-get install sox
```

# FFMPEG installation

Install from the following link as deb package or static install

https://www.ffmpeg.org/download.html

Change FFMPEG script variable after installing ffmpeg
