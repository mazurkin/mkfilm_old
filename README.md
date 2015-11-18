# Description

Script converts any video file to a video with "old movie" effect.
Some files from YouTube are downloaded during a process.

# Usage

'''
oldfilm MOVIEFILE DURATION_SECS
'''

Note that script speeds up the source video in x2 times (PTS_RATIO=0.5). So the specified duration
must be twice less than in the source video.

# Example

https://www.youtube.com/watch?v=DVHP6pg1HKw

converts to

https://www.youtube.com/watch?v=61UE0VAH6to


# Packages to install (Ubuntu 14.04)

```
sudo apt-get install youtube-dl
sudo apt-get install sox
```

# FFMPEG installation

Install from the following link as deb package or static install

https://www.ffmpeg.org/download.html
