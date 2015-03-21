# MpgTsTool #
MpgTsTool is a bash script to ease conversion of mpeg transport stream files to mpeg program stream or avi format under linux.

## Features ##
  * Automatically finds the video stream and 1st stereo audio stream in the file to extract.
  * Will optionally use a cut file from projectx to edit the file beforehand (useful for removing adverts).
  * Can automatically decide on the output files name if not provided on the command line.
  * Output mpg and avi files can be put in separate directories.

## Requires ##
**projectx** - http://sourceforge.net/projects/project-x/

**mjpegtools** - http://mjpeg.sourceforge.net/

**mencoder** - http://www.mplayerhq.hu

**ffmpeg** - http://www.ffmpeg.org

Standard unix tools **sed**,**grep**,**tr**,**basename**,**dirname**,**nice**,**date**