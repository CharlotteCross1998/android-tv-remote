# Project

This fork is a simple UI enhancement to the bluetooth-remote app. Currently only builds in debug mode. Any changes to the code should be directed to the original author. 

# Screenshots

### Old UI
![](Screenshot_2022-07-17-14-27-33-619_com.app.bluetoothremote.jpg)

### New UI & App Icon
![](Screenshot-20221203-033051-One-UI-Home.png)
![](Screenshot-20221203-033102-Android-TV-Remote.png)

# Original ReadMe

I wanted to create a bluetooth remote application so that I can control my Android TV.

After doing intensive search on the web, I found lots of sample code, but there is no ready-built app in the play store.

I decided to build this app using the sample snippets I found, with massive optimization also, built and tested on
Android 12 (MIUI).

I also released the code to the community for more optimization from anyone.

This app is using the Android HID API to simulate a Bluetooth peripheral.

It is still not working on Windows for some reason, but works on all android devices.

Keyboard input is also supported, just type anything in the textbox and hit enter to submit it.

First you pair you device in the normal Android Bluetooth settings, and then open the app and select a paired device,
then click on the "Connect" button.
