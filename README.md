# Script written in Bash for easy interaction between Ci and Us
Created by @hipexscape

## How to use ?

- First fork this repo and fill the variables (defined below)
- Clone this repo using curl
- Then do bash script.sh
- Done

### Variables 

---------------
```bash
# Lunch command , you should not leave it empty device codename get pulled from the command! :
CONFIG_LUNCH="lineage_lancelot-user"

# Compilation target. e.g. bacon or bootimage [Default is bacon!] :
CONFIG_TARGET="bacon"

# Set to yes if you need to use brunch to build else no for lunch and bacon :
CONFIG_USE_BRUNCH=""

# Your telegram group/channel chatid eg - "-xxxxxxxx"
CONFIG_CHATID=""

# Your HTTP API bot token (get it from botfather) 
CONFIG_BOT_TOKEN=""

# Set the author of the build
CONFIG_AUTHOR=""

# This flag which is to be exported as true to make a GAPPs build (Rom specific)
CONFIG_GAPPS_FLAG=""

# How many jobs (CPU cores) to assign for the repo sync and build task
CONFIG_SYNC_JOBS=8 and CONFIG_COMPILE_JOBS=8

# Set as true if you want to config repo sync
CONFIG_SYNC=""

# Config sync eg- https://github.com/crdroidandroid/android.git
CONFIG_SYNC_REPO=""

# Config branch from repo sync eg- 14.0
CONFIG_SYNC_BRANCH=""

# Set the build variant gapps/vanilla (edit as per rom)
CONFIG_BUILD_VARIANT=""
```
