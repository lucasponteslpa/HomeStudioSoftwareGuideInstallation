# HomeStudioSoftwareGuideInstallation

## Dedependencias para instalação do Ardour

> sudo apt-get -y install libboost-all-dev
> sudo apt-get -y install libasound2-dev
> sudo apt-get -y install libglib2.0-dev
> sudo apt-get -y install glibmm-2.4-dev
> sudo apt-get -y install libsndfile1-dev
> sudo apt-get -y install libcurl4-gnutls-dev
> sudo apt-get -y install liblo-dev
> sudo apt-get -y install libtag1-dev
> sudo apt-get -y install vamp-plugin-sdk
sudo apt-get -y install librubberband-dev
sudo apt-get -y install libfftw3-dev
sudo apt-get -y install libaubio-dev
sudo apt-get -y install libxml2-dev
sudo apt-get -y install libcwiid-dev
sudo apt-get -y install jack
sudo apt-get -y install libjack-dev
sudo apt-get -y install jackd
sudo apt-get -y install qjackctl
sudo apt-get -y install liblrdf0-dev
sudo apt-get -y install libsamplerate-dev
sudo apt-get -y install lv2-dev
sudo apt-get -y install libserd-dev
sudo apt-get -y install libsord-dev
sudo apt-get -y install libsratom-dev
sudo apt-get -y install liblilv-dev
sudo apt-get -y install libgtkmm-2.4-dev
sudo apt-get -y install libarchive-dev
sudo apt-get -y install libsuil-dev //opcional... para poder carregar as UIs dos plugins

# Comandos para instalar o Ardour
./waf configure
./waf
./waf install

# Comandos no terminal em seguencia para utilizar o ardour
qjackctl
[a2jmidid] //ponte para dispositivos midi
ardour5

# Dependencias para instalar Calf Studio Gear
apt-get install libtool autoconf libexpat1-dev libglib2.0-dev libfluidsynth-dev jackd libjack-dev lv2core libglade2-dev lv2-dev
sudo apt-get install automake

# Comandos para instalar Calf Studio Gear
./autogen.sh
automake -a
make
make install

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
  
  # Links uteis
  http://calf-studio-gear.org/
  http://libremusicproduction.com/tutorials/setting-and-using-drumgizmo-ardour
  https://www.drumgizmo.org/wiki/doku.php
