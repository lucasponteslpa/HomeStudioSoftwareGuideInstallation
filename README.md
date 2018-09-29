# HomeStudioSoftwareGuideInstallation

## Dedependencias para instalação do Ardour

1. sudo apt-get -y install libboost-all-dev
1. sudo apt-get -y install libasound2-dev
1. sudo apt-get -y install libglib2.0-dev
1. sudo apt-get -y install glibmm-2.4-dev
1. sudo apt-get -y install libsndfile1-dev
1. sudo apt-get -y install libcurl4-gnutls-dev
1. sudo apt-get -y install liblo-dev
1. sudo apt-get -y install libtag1-dev
1. sudo apt-get -y install vamp-plugin-sdk
1. sudo apt-get -y install librubberband-dev
1. sudo apt-get -y install libfftw3-dev
1. sudo apt-get -y install libaubio-dev
1. sudo apt-get -y install libxml2-dev
1. sudo apt-get -y install libcwiid-dev
1. sudo apt-get -y install jack
1. sudo apt-get -y install libjack-dev
1. sudo apt-get -y install jackd
1. sudo apt-get -y install qjackctl
1. sudo apt-get -y install liblrdf0-dev
1. sudo apt-get -y install libsamplerate-dev
1. sudo apt-get -y install lv2-dev
1. sudo apt-get -y install libserd-dev
1. sudo apt-get -y install libsord-dev
1. sudo apt-get -y install libsratom-dev
1. sudo apt-get -y install liblilv-dev
1. sudo apt-get -y install libgtkmm-2.4-dev
1. sudo apt-get -y install libarchive-dev
1. sudo apt-get -y install libsuil-dev //opcional... para poder carregar as UIs dos plugins

## Comandos para instalar o Ardour
1. ./waf configure
1. ./waf
1. ./waf install

## Comandos no terminal em seguencia para utilizar o ardour
1. qjackctl
1. [a2jmidid] //ponte para dispositivos midi
1. ardour5

## Dependencias para instalar Calf Studio Gear
1. apt-get install libtool autoconf libexpat1-dev libglib2.0-dev libfluidsynth-dev jackd libjack-dev lv2core libglade2-dev lv2-dev
1. sudo apt-get install automake

## Comandos para instalar Calf Studio Gear
1. ./autogen.sh
1. automake -a
1. make
1. make install

#Dependencias para instalar DrumGizmo

sudo apt-get install \
  build-essential \
  autoconf \
  automake \
  libtool \
  lv2-dev \
  xorg-dev \
  libsndfile1-dev \
  libzita-resampler-dev \
  libexpat-dev
  
  sudo apt-get install \
  libjack-dev \
  libsmf-dev \
  libasound2-dev
  
  ## Links uteis
  1. http://calf-studio-gear.org/
  1. http://libremusicproduction.com/tutorials/setting-and-using-drumgizmo-ardour
  1. https://www.drumgizmo.org/wiki/doku.php
