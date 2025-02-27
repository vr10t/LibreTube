<div align="center">
  <img src="https://libre-tube.github.io/images/gh-banner.png" width="auto" height="auto" alt="LibreTube">

[![GPL-v3](https://libre-tube.github.io/assets/widgets/license-widget.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)
[![Matrix](https://libre-tube.github.io/assets/widgets/mat-widget.svg)](https://matrix.to/#/#LibreTube:matrix.org)
[![Telegram](https://libre-tube.github.io/assets/widgets/tg-widget.svg)](https://t.me/libretube)
[![Twitter](https://libre-tube.github.io/assets/widgets/tw-widget.svg)](https://twitter.com/libretube)
[![Reddit](https://libre-tube.github.io/assets/widgets/rd-widget.svg)](https://www.reddit.com/r/Libretube/)
[![Discord](https://libre-tube.github.io/assets/widgets/discord-widget.svg)](https://discord.gg/Qc34xCj2GV)

</div><div align="center" style="width:100%; display:flex; justify-content:space-between;">

[<img src="https://libre-tube.github.io/assets/badges/fdrload.png" alt="Get it on F-Droid" width="30%">](https://f-droid.org/en/packages/com.github.libretube/)
[<img src="https://libre-tube.github.io/assets/badges/izzyload.png" alt="Get it on IzzyOnDroid" width="30%">](https://apt.izzysoft.de/fdroid/index/apk/com.github.libretube)<br/>
[<img src="https://libre-tube.github.io/assets/badges/ghload.png" alt="Get it on GitHub" width="30%">](https://github.com/libre-tube/LibreTube/releases/latest)

</div>

<details>
  <summary>📜️ Credits</summary>

<sub>Readme Design and Banners by [XelXen](https://github.com/XelXen)</sub> <br>
<sub>Readme Screenshots by [ARBoyGo](https://github.com/ARBoyGo)</sub> <br>
<sub>Readme Emoji is from [openmoji](https://openmoji.org)</sub>

  <summary>Icons</summary>

<sub>[Default App Icon](https://github.com/libre-tube/LibreTube/blob/master/app/src/main/res/mipmap-xxxhdpi/ic_launcher_round.png) by [XelXen](https://github.com/XelXen)</sub> <br>
<sub>[Boosted Bird](https://github.com/libre-tube/LibreTube/blob/master/app/src/main/res/mipmap-xxxhdpi/ic_bird_round.png) by [Margot Albert-Heuzey](https://margotdesign.ovh)</sub>

</details>

<h2 align="left">
<sub>
<img  src="fastlane/metadata/android/en-US/images/readme/about.svg"
      height="30"
      width="30">
</sub>
About
</h2>

YouTube has an extremely invasive [privacy policy](https://support.google.com/youtube/answer/10364219) which relies on using user data in unethical ways. They store a lot of your personal data - ranging from ideas, music taste, content, political opinions, and much more than you think.

This project is aimed at improving the users' privacy by being independent from Google and bypassing their data collection.

Therefore, the app is using the [Piped API](https://github.com/TeamPiped/Piped), which uses proxies to circumvent Google's data collection and includes some other additional features.

If you have questions or need help, please make sure to read the [FAQ](https://libre-tube.github.io/#faq) before asking for help at the community channels. The [Matrix room](https://matrix.to/#/#LibreTube:matrix.org) is considered as the main communication channel, all other forums or social media accounts are maintained by volunteers from the community but not the developer(s).

<h2 align="left">
<sub>
<img  src="fastlane/metadata/android/en-US/images/readme/phone.svg"
      height="30"
      width="30">
</sub>
Screenshots
</h2>

<div style="width:100%; display:flex; justify-content:space-between;">

[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Screenshot_1.png" width=20% alt="Home">](fastlane/metadata/android/en-US/images/phoneScreenshots/Screenshot_1.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Screenshot_2.png" width=20% alt="Home">](fastlane/metadata/android/en-US/images/phoneScreenshots/Screenshot_2.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Screenshot_3.png" width=20% alt="Subscriptions">](fastlane/metadata/android/en-US/images/phoneScreenshots/Screenshot_3.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Screenshot_4.png" width=20% alt="Library">](fastlane/metadata/android/en-US/images/phoneScreenshots/Screenshot_4.png)

</div>

<h2 align="left">
<sub>
<img  src="fastlane/metadata/android/en-US/images/readme/feature.svg"
      height="30"
      width="30">
</sub>
Features
</h2>


| Feature           |     |
| ----------------- | --- |
| User Accounts     | ✅ |
| Subscriptions     | ✅ |
| User Playlists    | ✅ |
| Playlist Bookmarks| ✅ |
| Channel Tabs      | ✅ |
| Search Filters    | ✅ |
| Player Gestures   | ✅ |
| SponsorBlock      | ✅ |
| Comments          | ✅ |
| Captions          | ✅ |

<h2 align="left">
<sub>
<img  src="fastlane/metadata/android/en-US/images/readme/community.svg"
      height="30"
      width="30">
</sub>
Contributing
</h2>

Whether you have ideas, translations, design changes, code cleaning or really heavy code changes, help is always welcome. The more is done, the better it gets! Please respect our [Code of Conduct](https://github.com/libre-tube/LibreTube/blob/master/CODE_OF_CONDUCT.md) in order to keep all interactions and dicussions healthy.

If creating a pull request, please make sure to format your code (preferred ktlint) before.

> **Note** <br>
> Any issue avoiding the issue template will be ignored and forced to be closed.

<h2 align="left">
📝 Translations
</h2>

<a href="https://hosted.weblate.org/projects/libretube/#languages">
<img src="https://hosted.weblate.org/widgets/libretube/-/287x66-grey.png" alt="Translation status" />
</a>

<h2 align="left">
<sub>
<img  src="fastlane/metadata/android/en-US/images/readme/ltvnp.svg"
      height="30"
      width="30">
</sub>
Differences to NewPipe
</h2>


With NewPipe, the extraction is done locally on your phone, and all the requests sent towards YouTube/Google are done directly from the network you're connected to, which doesn't use a middleman server in between. Therefore, Google can still access information such as the user's IP address. Aside from that, subscriptions can only be stored locally.

LibreTube takes this one step further and proxies all requests via Piped (which uses the NewPipeExtractor). This prevents Google servers from accessing your IP address or any other personal data.<br>
Apart from that, Piped allows syncing your subscriptions between LibreTube and Piped, which can be used on desktop too.

If the NewPipeExtractor breaks, it only requires an update of Piped and not LibreTube itself. Therefore, fixes usually arrive faster than in NewPipe.

While LibreTube only supports YouTube, NewPipe also allows the use of other platforms like SoundCloud, PeerTube, Bandcamp and media.ccc.de.<br>
Both are great clients for watching YouTube videos. It depends on the individual's use case which one fits their needs better.

<h2 align="left">
<sub>
<img  src="fastlane/metadata/android/en-US/images/readme/privacy.svg"
      height="30"
      width="30">
</sub>
Privacy Policy and Disclaimer
</h2>

The LibreTube project aims to provide a private, anonymous experience for using web-based media services. Therefore, the app does not collect any data without your consent.

The LibreTube project and its contents are not affiliated with, funded, authorized, endorsed by, or in any way associated with YouTube, Google LLC, or any of its affiliates or subsidaries.<br>
Any trademark, service mark, trade name, or other intellectual property rights used are owned by the respective owners.

LibreTube is an open source software built for learning and research purposes.

## License
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)

LibreTube is Free Software: You can use, study, share and modify it at your will. The app can be redistributed and/or modified under the terms of the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) version 3 or later published by the Free Software Foundation.

<div align="right">
<table><td>
<a href="#start-of-content">↥ Scroll to top</a>
</td></table>
</div>
