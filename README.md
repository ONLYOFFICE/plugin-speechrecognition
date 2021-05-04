## Overview

Type with your voice in ONLYOFFICE Docs.

The plugin uses [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API).

It is called "Speech input" in the interface and isn't installed by default in cloud, [self-hosted](https://github.com/ONLYOFFICE/DocumentServer) and [desktop version](https://github.com/ONLYOFFICE/DesktopEditors) of ONLYOFFICE editors.

## How to use

1. Turn on your microphone.
2. Find the plugin on the Plugins tab and click it.
3. Set the language you use.
4. Click the microphone button and start speaking. 
5. After dictation is complete, the text is inserted into the document. To stop inserting text, click the microphone button again . 

## How to install

Detailed instructions can be found in [ONLYOFFICE API documentation](https://api.onlyoffice.com/plugin/installation).

## Known issues

This plugin works in Google Chrome only. To use it in FireFox, enable recognition via `media.webspeech.recognition.enable` flag in `about:config` synthesis is switched on by default. More information [here](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API). 
