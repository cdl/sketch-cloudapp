# sketch-cloudapp

**:warning: Heads up: this project is no longer maintained. :warning:**

**I suggest you use [sketch-upload](https://github.com/jelias/sketch-upload) instead. Thanks for all the stars and support, guys - I just don't have time to maintain this (and no longer use CloudApp). :yellow_heart::yellow_heart::yellow_heart:**

A plugin to upload the current [Sketch.app](http://bohemiancoding.com/sketch/) artboard to [CloudApp](http://www.getcloudapp.com/) with a keystroke.

### Usage

1. [Grab the repository.](https://github.com/cdl/sketch-cloudapp/archive/master.zip)
2. Open up Sketch, and go to `Plugins` > `Reveal Plugins Folder...`
3. Copy `Upload to CloudApp.sketchplugin` from the repository into the folder.

Now, hit `ctrl + cmd + r` when in Sketch, and voila - Cloud.app will upload your current artboard.

### Issues

1. Be sure you have Cloud.app open on your computer first! Otherwise, this won't work!
2. ~~Currently this only works with one artboard. Unfortunately, for some reason, [there's no way to grab the active artboard in the Sketch plugin API](http://bohemiancoding.com/sketch/support/developer/03-reference/MSArtboardGroup.html), but I've gone ahead and [contacted the team](https://twitter.com/cdl/status/458365170520031232) about it (hopefully they get back to me soon!).~~ This has been fixed!