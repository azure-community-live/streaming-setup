# streaming-setup
Setup for Azure Community Live hosts to stream

## Tools needed

install the following tools

- OBS Studio (https://obsproject.com/download)
- My stream timer (https://github.com/jamesmontemagno/MyStreamTimer)
- Skype, make sure you take the win 32 installer and NOT the windows store version (https://go.skype.com/windows.desktop.download)
- OBS Ndi plugin (https://obsproject.com/forum/resources/obs-ndi-newtek-ndi%E2%84%A2-integration-into-obs-studio.528/)

## Setup the tools

### Skype
in Skype you need to enable NDI -> howto: https://www.skype.com/en/content-creators/

### OBS
OBS Studio is the main tool to be used. Since OBS does not have any cloud storage like Streamlabs OBS we need to configure it on each PC of each host. Geert has created an initial set of Scenes and exported these. These + additional resources can be found on onedrive as a zip file called "streaming--resources.zip"

It's important to download and extract these files to c:\acl\ since the paths in the scenes are hardcoded paths and this way exporting and importing just works.

after all files are extracted open OBS studio, go to "Scene Collection" -> "Import" and select "acl scene collection.json"
you should now be able to select the scene collection and you are ready to stream
