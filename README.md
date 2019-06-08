Chromium Livestreamer
=====================

A silly example project that can load any website and turn it into a livestream

This project comes with a very simple script + dockerfile showing how to use
Xvfb, Pulseaudio, FFmpeg, and Chromium to turn any website into a livestream.

**WARNING**: Do not use this script and Dockerfile in production, this is simply
an example, and is absolutely not ready for production deployment

Building
--------

`docker build -t chromium_livestreamer .`

Running
-------

`docker run --rm -it chromium_livestream https://www.<your website here>.com rtmp://somewhere.com/app/streamkey`

