# AutoSongDownload
Download song in just two steps.

###What it does-
"Download song of your choice in audio or video format in two steps by just entering the name."
You can chose to download only one of audio/video or both while giving the command. 

###Getting started-
* Clone the repository. 
* Add the location to your path using environment variables.
* In getUrl.py and youtubeAudio.py change pathA and pathV to folder you want your song to download.

###Usage - 5 ways:-
* Run the program and enter the song name.
* From cmd line or run(win+R) enter "song \<song name\>". This is will give you top
    n results(n=6 by deafult).
* From cmd line or run enter "song /<song name>". First result will be automatically downloaded.
* Add 1 at last to download both video and audio.
  and 0 at last to download only video.
  Don't add anything for only audio.
* You can just copy the song name and run "song" command from cmd or run. No
    need to paste just copy. Note:-This will automatically download the first result by default. (P.S-You
    can change that too.)
* You can create a keyboard shorcut to shorten the 4th way even more. Just copy the
    the song name and press that Keyboard shortcut. And the download will start.

#####Note:- Optionally if you don't want the song to autoplay, you can append the song name with '/'.

######eg. "song /count on me/"  will download this song without giving options but will not play it.
######eg. "song count on me1"   will download both video and audio of song to their respective folders.
######eg. "song shape of you/0" will download only video and not autoplay it after download.

I have made this on windows and python 2.7. It may require some tweaks to get it working on other OS.

If the file is already downloaded it will just play it(only if its not appended with '/'.)
