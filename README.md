#-Deprecated-FirefoxAddon-TTS

This is a firefox addon mostly in javascript I made a while ago, it was used to convert the text files I had created into text.

This addon works by looking at the text files in a folder that was pointed to by a Bash shell script.

The addon then opens the text file and copies it into 5 instances of the website [fromtexttospeech.com](www.fromtexttospeech.com) representing the 5 available voices, then, after converting the text files to speech, it sends the resulting urls linking to the hosted mp3s to the bash script for wget to download.

This method is deprecated because the [new method](https://github.com/KhalfaniWadlington/Convert-Book-or-PDF-To-Audio) for converting Pdfs and text files to audio is headless whereas this method requires multiple applications to run synchronously through the *console* text file liaison.

This add-on requires jpm to run ```jpm -b /usr/lib/firefox/firefox run ```

This addition is mostly for logging my work so all directories are hard coded into the scripts but it can be used as a tool to study how firefox addons are made.

*Note that the directories referenced are hard coded into the program

Refer to the [Firefox addon documentation](https://developer.mozilla.org/en-US/Add-ons/SDK) for hints on how this was made and may be used
