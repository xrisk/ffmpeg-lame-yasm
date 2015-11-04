# ffmpeg-lame-yasm

This buildpack lets you use [ffmpeg](https://github.com/xrisk/ffmpeg-lame-yasm) compiled with [lame](lame.sourceforge.net/) on your Heroku app—mp3 encoding party! 🎉

Make sure you’re using the multi-buildpack. Instructions for that [here](https://github.com/ddollar/heroku-buildpack-multi). Then in your project root:

`echo "https://github.com/xrisk/ffmpeg-lame-yasm" >> .buildpacks`

Voila, you’re done. You now have a ffmpeg binary in `/app/vendor`. Make sure to add that to your path when running your app.
