[![npm version](https://badge.fury.io/js/cordova-plugin-rtsp-vlc.svg)](https://badge.fury.io/js/cordova-plugin-rtsp-vlc)

# PhoneGap/Cordova RTSP player using VLC

## Installation

    cordova plugin add cordova-plugin-rtsp-vlc-unmanned

## Supported Platforms

- Android
- iOS

## Usage

```
window.VideoPlayerVLC.play(
	 url,
	 (done: boolean) => { },
	 (error: string) => { }
);
```

```
window.VideoPlayerVLC.stop(
	 (done: boolean) => { },
	 (error: string) => { }
);
```


## Example:

```
window.VideoPlayerVLC.play(
	 "rtsp://192.168.42.1/live.mov",
	 done => {},
	 error => {}
);
```

References:

https://github.com/disono/libVLC-Player by [@disono](https://github.com/disono)

https://github.com/pengyanb/com.pengyanb.vlcstreamplayer by [@pengyanb](https://github.com/pengyanb)
