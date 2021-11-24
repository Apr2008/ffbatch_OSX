# ffbatch_OSX
.sh scripts for installing ffmpeg via homebrew and extracting multitrack .mp4 containers

<h1>
  How it works
  </h1>
Download ffmpegbatch.zip, extract, then move the ffmpegbatch folder to your home dir ~/

Run: Install_app.sh in Terminal and follow the prompts

Once complete, move unextracted multitrack .mp4 into the 'in' folder, found within ffmpegbatch folder previously extracted

Run: ffbatch.sh

Once complete, audio and video streams 0-9 will be extracted as seperate .mp4 files to the 'out' folder, found within ffmpegbatch folder previously extracted. Each  resulting file will be named in relation to the corresponding audio and video stream (track)

Move extracted .mp4 files to a safe place, remove .mp4 from 'in' folder
