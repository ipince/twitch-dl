# twitch-dl

Simple script to download Twitch livestreams. It uses streamlink and ffmeg to download the stream and correct any errors in the resulting video. The stream must be currently live in order for this to work.

Usage:

```
devbox run download <twitch-username> <filename>

devbox run fix <filename>
```


Installation:
- Install [devbox](https://github.com/jetify-com/devbox), and then use it to run the scripts
- Or, feel free to inspect `devbox.json` and see what the scripts are doing; it's pretty straightforward.
