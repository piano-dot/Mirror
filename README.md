# Mirror
Welcome to the mirror app for android. A simple mirror using your front camera.
Despite it goes stable, it still have some rough edges and feature missing we've accidentally missed, so you're welcomed to fix bugs, translate this app by sending a pull request or ask any question by opening an issue.
## Features
* Just a mirrror, no ads, no background tracking (just see the source code if you don't trust me);
* a minimal app, no neccesary effect or information, or settings, since CameraX will choose the correct resolution for you.
* free to use/modify, with GNU GPL covered.
## System requirements
* Needs Android 6.0 (Marshmallow) or later to work.
* The latest release have support up to Android 12L(for foldables and large screens, API level 32).
## Current Bugs
These are the bugs that you can fix:
* The Full-Screen feature is deprecated in Java (```window.setFlags(WindowManager.LayoutParams.FLAG_FULLSCREEN, WindowManager.LayoutParams.FLAG_FULLSCREEN)```), a replacement required;
* The first-time setup has no translation with ```strings.xml``` whatsoever, due to it will crash when first startup with a translated.
## Download the app
You can now download the app on the amazon appstore! [![amazonbadge](https://user-images.githubusercontent.com/63381178/171801953-131fe9a6-6011-4215-9d00-f6e94bfe0a21.png)](https://www.amazon.com/gp/product/B0B124M26K/ref=mas_pm_Mirror)
</br>
Or, download it on github releases.
 ---
## FAQs
Q: Are android tiramisu (13) supported?</br>
A: I haven't tested. It is "for older version of android and will not function appropriately" (specifically, android 12L or earlier). So it still up to you to report compatability issues to us.

Q: Can I use this app with android version below 6.0?

A: Well, you can do that, but CameraX still only supports android 5.0 (Lolipop) or later to work. So if you have a android 5.0 device, you can do that by modifying the build.gradle under /app directory and change ``minSdk`` from 23 to 21.

Q: Can I modify it for my own use cases?</br>
A: Sure, you can! GPL only came effective when you release it to the public, so it's fine to modify it yourself and not to release it (that's how google used GPL programs in its search service).

## Features working on progress
 * Use a first time setup "activity" when the app is first launched.
---
## License
Mirror: A simple mirror for android using the front camera
Copyright (C) 2022 Linyixuan10.

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
