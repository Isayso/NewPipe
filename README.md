<p align="center"><a href="https://newpipe.schabi.org"><img src="assets/new_pipe_icon_5.png" width="150"></a></p> 
<h2 align="center"><b>NewPipe</b></h2>
<h4 align="center">A libre lightweight streaming frontend for Android.</h4>
<p align="center"><a href="https://f-droid.org/packages/org.schabi.newpipe/"><img src="https://f-droid.org/wiki/images/0/06/F-Droid-button_get-it-on.png"></a></p> 

<p align="center">
<a href="https://github.com/TeamNewPipe/NewPipe/releases" alt="GitHub release"><img src="https://img.shields.io/github/release/TeamNewPipe/NewPipe.svg" ></a>
<a href="https://www.gnu.org/licenses/gpl-3.0" alt="License: GPLv3"><img src="https://img.shields.io/badge/License-GPL%20v3-blue.svg"></a>
<a href="https://travis-ci.org/TeamNewPipe/NewPipe" alt="Build Status"><img src="https://travis-ci.org/TeamNewPipe/NewPipe.svg"></a>
<a href="https://hosted.weblate.org/engage/newpipe/" alt="Translation Status"><img src="https://hosted.weblate.org/widgets/newpipe/-/svg-badge.svg"></a>
<a href="http://webchat.freenode.net/?channels=%23newpipe" alt="IRC channel: #newpipe"><img src="https://img.shields.io/badge/IRC%20chat-%23newpipe-brightgreen.svg"></a>
<a href="https://www.bountysource.com/teams/newpipe" alt="Bountysource bounties"><img src="https://img.shields.io/bountysource/team/newpipe/activity.svg?colorB=cd201f"></a>
</p>
<hr>
<p align="center"><a href="#screenshots">Screenshots</a> &bull; <a href="#description">Description</a> &bull; <a href="#features">Features</a> &bull; <a href="#updates">Updates</a> &bull; <a href="#contribution">Contribution</a> &bull; <a href="#donate">Donate</a> &bull; <a href="#license">License</a></p>
<p align="center"><a href="https://newpipe.schabi.org">Website</a> &bull; <a href="https://newpipe.schabi.org/blog/">Blog</a> &bull; <a href="https://newpipe.schabi.org/FAQ/">FAQ</a> &bull; <a href="https://newpipe.schabi.org/press/">Press</a></p>
<hr>

<b>WARNING: THIS IS A BETA VERSION, THEREFORE YOU MAY ENCOUNTER BUGS. IF YOU DO, OPEN AN ISSUE VIA OUR GITHUB REPOSITORY.</b>

<b>PUTTING NEWPIPE OR ANY FORK OF IT INTO GOOGLE PLAYSTORE VIOLATES THEIR TERMS OF CONDITIONS.</b>


## Description

NewPipe does not use any Google framework libraries, nor the YouTube API. Websites are only parsed to fetch required info, so this app can be used on devices without Google services installed. Also, you don't need a YouTube account to use NewPipe, which is copylefted libre software.


### Supported Services

NewPipe supports multiple services. Our [docs](https://teamnewpipe.github.io/documentation/) provide more info on how a new service can be added to the app and the extractor. Please get in touch with us if you intend to add a new one. Currently supported services are:

* YouTube
* SoundCloud \[beta\]
* media.ccc.de \[beta\]
* PeerTube instances \[beta\]

## Updates
When a change to the NewPipe code occurs (due to either adding features or bug fixing), eventually a release will occur. These are in the format x.xx.x . In order to get this new version, you can:
 * Build a debug APK yourself. This is the fastest way to get new features on your device, but is much more complicated, so we recommend using one of the other methods.
 * Download the APK from [releases](https://github.com/TeamNewPipe/NewPipe/releases) and install it.
 * Update via F-droid. This is the slowest method of getting updates, as F-Droid must recognize changes, build the APK itself, sign it, then push the update to users.

When you install an APK from one of these options, it will be incompatible with an APK from one of the other options. This is due to different signing keys being used. Signing keys help ensure that a user isn't tricked into installing a malicious update to an app, and are independent. F-Droid and GitHub use different signing keys, and building an APK debug excludes a key. The signing key issue is being discussed in issue [#1981](https://github.com/TeamNewPipe/NewPipe/issues/1981), and may be fixed by setting up our own repository on F-Droid.

In the meanwhile, if you want to switch sources for some reason (e.g. NewPipe's core functionality was broken and F-Droid doesn't have the update yet), we recommend following this procedure:
1. Back up your data via "Settings>Content>Export Database" so you keep your history, subscriptions, and playlists
2. Uninstall NewPipe
3. Download the APK from the new source and install it
4. Import the data from step 1 via "Settings>Content>Import Database"

## Contribution
Whether you have ideas, translations, design changes, code cleaning, or real heavy code changes, help is always welcome.
The more is done the better it gets!

If you'd like to get involved, check our [contribution notes](.github/CONTRIBUTING.md).


## Privacy Policy

The NewPipe project aims to provide a private, anonymous experience for using media web services.
Therefore, the app does not collect any data without your consent. NewPipe's privacy policy explains in detail what data is sent and stored when you send a crash report, or comment in our blog. You can find the document [here](https://newpipe.schabi.org/legal/privacy/).

## License
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

NewPipe is Free Software: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.  

![GitHub Releases (by Release)](https://img.shields.io/github/downloads/Isayso/NewPipe19/total)

