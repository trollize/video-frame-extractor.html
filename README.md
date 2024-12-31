# video-frame-extractor.html
Locally Extract Video Frames As PNG Images. I show the prompt I use on Claude.AI to show how I made it...

# My claude.ai prompts used to make this:

Request #1:

i need a web app (html with embedded javascript version ES3 and css) that allows uploading a video to display in canvas. Include a button for processing and displaying each image frame (every single frame) of the video below video preview. Each image extracted should remain in sequence.

Request #2:

can you add a download working button that will package all the single frame images into a zip/rar/7z file?

Request #3:

ok, then one more thing. Can you make it so I downloads a array (CVS text file) of the toDataURL (base64) encoded to list (one per line).

# What The Web Based Application Does:

Upload a video, extract all the frames, save as *.zip file or DataURL (base64) list/array as a *.cvs database.

# Why 3 Files?

video-frame-extractor-zip-csv.html (online version) uses external *.js file so it won't run offline.

video-frame-extractor-zip-csv-embedded-JS.html (offline/local version) has the JavaScript code embedded to make it portable (runs on linux/android/windows/mac) and will and do it's thing offline or without internet (my addition). 107KB

video-frame-extractor-zip-csv-compressed-JS.html (offline) is embedded JS, but it's the script is compressed to half the size (48KB).


