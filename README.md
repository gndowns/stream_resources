# Stream Resources
This is a guide for setting up everything needed to stream audio on Mac.
It is mainly intended for streaming live DJ sets through Zoom, but it should
be compatible with any streaming purposes or apps.


## Zoom
Zoom is a useful app for video conferencing and can be modified to stream
audio with (almost) original quality. Follow these steps to install Zoom
and configure it for audio streaming.

#### Install Zoom
First download the Zoom installer from the [official site](https://zoom.us/download).
Once the file is downloaded, click on it and follow the instructions to install the Zoom app.

#### Configure Zoom to Use Original Sound
Normally Zoom applies some noise cancellation to your audio, but when streaming
we want to preserve our computer's original audio.
Follow the instructions [here](https://support.zoom.us/hc/en-us/articles/115003279466-Enabling-option-to-preserve-original-sound)
to enable original sound. Use the instructions under the "User" section.


## Soundflower
Mac does not let you stream audio directly to other apps by default, so we will
use a free application called Soundflower.

#### Install Soundflower
Soundflower can be quite annoying to install so follow these instructions carefully if you encounter any errors.

Download the Soundflower installer [here](https://github.com/mattingalls/Soundflower/releases/tag/2.0b2).
Scroll down to the bottom of the page and click on the file labeled `Soundflower-2.0b2.dmg`.

![soundflower download](images/soundflower_download.png)

Click on the file once it is downloaded.
Click on `Soundflower.pkg` to run the installer.

You may get a security warning like this when running the installer.

![soundflower warning](images/soundflower_warning.png)

If you do, close the warning, open System Preferences, click on "Security & Privacy" and open the "General" tab.
There should be a notice at the bottom saying that `Soundflower.pkg` was blocked from running, click "Open Anyway"

![soundflower open anyway](images/soundflower_open_anyway.png)

Follow the steps in the Soundflower installer.

The installation may fail the first time. If it does don't panic! Do not close the installer!
Close System Preferences and re-open it, and navigate back to "Security & Privacy."
There should be a notice on the bottom to allow the Soundflower installer to run. Click "allow".

Now you can close the installer and re-run it, and this time the installation should complete succesfully.

#### Install SoundflowerBed (optional)
SoundflowerBed is an app to help manage Soundflower. It makes it easier to monitor and control your audio while streaming, so I recommend it.

Download  SoundflowerBed [here](https://github.com/mLupine/SoundflowerBed/releases).
Click on the file labeled `SoundflowerBed-2.0.0-release.dmg` and open it when it's finished downloading.

![soundflowerbed download](images/soundflowerbed_download.png)

Click on the app to run it.

![soundflowerbed app](images/soundflowerbed_app.png)
