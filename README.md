# ffbatch_OSX
.sh scripts for installing ffmpeg via homebrew and extracting multitrack .mp4 containers

<h1>
  How it works
  </h1>
  
Download ffmpegbatch.zip, extract, then move the ffmpegbatch folder to your home dir ~/


Navigate to ~/ffmpegbatch and open it

<h3>Run: Install_apps.sh in Terminal and follow the prompts</h3>

Once complete, move unextracted multitrack .mp4 into the 'in' folder, found within ffmpegbatch folder previously extracted

<h3>Run: ffbatch.sh</h3>

Once complete, audio and video streams 0-9 will be extracted as seperate .mp4 files to the 'out' folder, found within ffmpegbatch folder previously extracted. Each  resulting file will be named in relation to the corresponding audio and video stream (track)

Move extracted .mp4 files to a safe place, remove .mp4 from 'in' folder
