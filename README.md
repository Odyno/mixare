MIXARE
======

Status of CI
============
* feature-Mvn_and_CI [![Build Status](https://travis-ci.org/Odyno/mixare.png?branch=feature-Mvn_and_CI)](https://travis-ci.org/Odyno/mixare)
* master [![Build Status](https://travis-ci.org/Odyno/mixare.png?branch=master)](https://travis-ci.org/Odyno/mixare)



HowTo Build with Maven
======================
This step is the same used on Travis CI:

* Download a AndroidSDK  ( wget http://dl.google.com/android/android-sdk_r21.1-linux.tgz ; tar xvzf android-sdk_r21.1-linux.tgz
* Set Eviroment Variable ( export ANDROID_HOME=$(pwd)/android-sdk-linux; export PATH=$PATH:$ANDROID_HOME/tools:$ANDROID_HOME/platform
* Download or Update the SDK ( odyno@Itaca:~$ android update sdk --no-ui --filter 1,2,10,45 )
* Go to project root and run Maven (mvn clean install)

Reffer to Maven-Android-Plugin to other info



