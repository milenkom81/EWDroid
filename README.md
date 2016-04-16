# EWDroid
EverWatch Android Agent for Nagios

This is a rudimentary native Android Nagios Agent.  This is not just something you can download and use, as it requires a Nagios server component that is not yet ready to be released to the public.  As such, this is beta software.  There are some requirements for participating in this beta:

* You must be running Android Lollipop or better on your device.
* You must be willing to run my beta, which is not available from the play store.
* If you do not know how to install third-party APK files, then you should not participate.

You must be willing to let me track any or all of the following (more, if we can make it work):
* Device connectivity to the Internet
* Device battery level
* Device memory usage
* Device location in latitude/longitude
* Wifi SSID the device is connected to
* Nearest Cell Tower ID
* OS level

Obviously, this will all be held confidential, but the point is to be able to potentially monitor and track Android devices with Nagios.  This is a closed beta.  You will be required to run software that I provide on your device.  It is based on Tasker but distributed as a standalone app.  **You do not need Tasker installed on your device.**

The beta is currently set to use one of our Nagios servers.  It will note work on any other Nagios servers at this time due to the Nagios component not being distributed (yet).

When you first run the app, you will need to click "device name." You can accept the default or name your device whatever you want. **WHATEVER it is, you need to tell me so I can add it to our Nagios configuration**.  Alerts for down devices are NOT currently provided, as the current testing is mainly to see if it will install on other people's devices and work from outside our firewalls properly.

At this time, the information logged to our server is only visible to me.  That will change as we figure out what sort of remote access can be provided for beta users.

"Refresh time" is in minutes and defaults to 15. Feel free to change it.  It will not allow you to set it to less than 15 minutes.

There are two "on/off" toggles on the screen. A slider which sets off to the left and on to the right, and a toggle button in the middle.  Looking for feedback on what people like better.  Please let me know.

The interface is functional but not ideal.
