# Mirror
Welcome to the mirror app for android. A simple mirror using your front camera.
Despite it goes stable, it still have some rough edges and feature missing we've accidentally missed, so you're welcomed to fix bugs, translate this app by sending a pull request or ask any question by opening an issue.
## Features
 * Just a mirrror, no ads, no background tracking (just see the source code if you don't trust me);
 * a minimal app, no neccesary effect or information, or settings, since CameraX will choose the correct resolution for you.
 * free to use/modify, with GNU GPL covered.
## System requirements
 * Needs Android 6.0 (Marshmallow) or later to work;
 * currently have not supported for the Android 13 (Tiramisu). We are planning to enable support for Tiramisu in the next alpha release once it goes to beta stage.
## Current Bugs
These are the bugs we want you (developers) to fix:
 * The Full-Screen feature is deprecated in Java (```window.setFlags(WindowManager.LayoutParams.FLAG_FULLSCREEN, WindowManager.LayoutParams.FLAG_FULLSCREEN)```)
 * This is locked to landscape orientation due to it will crashes when you rotate in the 1.0.1-alpha release of Mirror, so it will affect some of chromebook users with multi-window mode using this application.
 * The first-time setup is
## License
This app is free software: You have the rights to re-distribute it and/or modify it under the terms of GNU General Public License (as published by the Free software foundation; either version 2, or any later version. See LICENSE for more detail.
