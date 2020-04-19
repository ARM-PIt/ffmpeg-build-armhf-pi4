# ffmpeg-build-armhf-pi4
Dockerized builder for ffmpeg to be used with Raspberry Pi 4 on armhf architecture in Debian 10 or Raspbian Buster. As is, the resulting deb package provides ffmpeg with one apt dependency under a minimal Debian environmnet: libgl1. Installing libgl1 will bring in all Mesa/OpenGL dependencies. Disabling --enable-opengl in the ffmpeg configure options will provide an independent installation of ffmpeg.
