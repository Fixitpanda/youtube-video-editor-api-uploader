# Python YouTube Video Editor + API Uploader
This Python3 code allows you to add intro + outro + logo + upload complete video, including all video details to youtube by single click.

## What exactly is this script doing?
It calls two main functions Video Editor and then Video Uploader.  
<br/> 
Note: you can disable editor or uploader in case you want to use just single function in start_process(), simple add "#" before the call row.

#### Here is complete steps:
Video Editor
1.  Adding intro clip
2.  Adding logo
3.  Adding outtro clip

Video Uploader
1.  Uploading Video
2.  Adding Title
3.  Adding Complete Description + Urls any info you desire
4.  Adding tags
5.  Video will be "Private", edit status manually once uploaded. Note: you can't upload with API as public. Unless you pass audit with google
6.  Uploading thumbnail photo (YouTube account must be confirmed)


## How to use?
1. Create YouTube App at: https://console.cloud.google.com, I will upload complete video tutorial soon.
2. Download client_secrets.json file from google, place it in the root folder.
3. Run main.py
<br/>
Note: All file locations, directories, video details can be edited in videoDetails.py, I added sample files but please don't use these for production beyong testings.
