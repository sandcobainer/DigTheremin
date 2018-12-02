Leapmotion For Max
===========================================

This is a simple Max external for Leap Motion Skeletal Tracking.

The object is inspired by aka.leapmotion, developed by Masayuki Akamatsu, but was re-written for the new tracking API. The object has separate outlets for gestures, hands, fingers, and frame information. Most of the features of the SDK are dumped as prefixed messages in Max.

The object was developed for research or experimental applications. Therefore, the object is in beta, and we do not guarantee any sustained development and support. The source code is available on Ircam-Forge.

__Compatibility:__ Max 6+ [Mac OSX 10.6+ // Windows 32/64bits]

__Features:__
- Full Skeletal Tracking
- Automatic left/right hand routing
- Automatic finger routing
- Build-in Leap Motion gesture recognition
- Simple record/replay based on MuBu

### Contact

Jules Françoise: <jules.francoise@ircam.fr>

### author

This code has been initially authored by <a href="http://julesfrancoise.com">Jules Françoise</a> during his PhD thesis, supervised by <a href="frederic-bevilacqua.net">Frederic Bevilacqua</a>, in the <a href="http://ismm.ircam.fr">Sound Music Movement Interaction</a> team of the <a href="http://www.ircam.fr/stms.html?&L=1">STMS Lab</a> - IRCAM - CNRS - UPMC (2011-2015).

## Compiling

### Mac OS X

__requirements:__
- Max SDK
- Leap Motion SDK

Place the "LeapSDK" folder from Leapmotion SDK v2 to the root directory of the project and modify paths to the Max SDK in "build/xcode/leapmotion.xcconfig".

### Windows

__requirements:__
- Max SDK
- Leap Motion SDK

Modify paths to SDKs in the project settings (header path & library path)
