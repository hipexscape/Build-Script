# Script written in Bash for easy interaction between Ci and Us
Created by @hipexscape

## How to use ?

- First fork this repo and fill the variables (defined below)
- Clone this repo using curl
- Then do bash script.sh -h
- Done

### Variables 

---------------
```bash
# Lunch command , you should not leave it empty device codename get pulled from the command! :
CONFIG_LUNCH="lineage_lancelot-user"

# Compilation target. e.g. bacon or bootimage [Default is bacon!] :
CONFIG_TARGET="bacon"

# Your telegram group/channel chatid eg - "-xxxxxxxx"
CONFIG_CHATID=""

# Your HTTP API bot token (get it from botfather) 
CONFIG_BOT_TOKEN=""

# Set the Seconday chat/channel ID (IT will only send error logs to that)
CONFIG_ERROR_CHATID=""

# Config PixelDrain api key (get it from https://pixeldrain.com/api)
CONFIG_PDUP_APT=""

# Turn off server after build (save resource)
POWEROFF=""
```
