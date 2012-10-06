# LockCode - Protect your NXT at startup

Ever wanted to protect your NXT from a pesky brother or sister?

When you startup your NXT it will show a splash image and play a sound, then prompt for a four didgit code. The first time the program is run it will ask you to set a code. If you enter the wrong code, the NXT will flash a message, otherwise, the program will end, allowing you to access your NXT. The dark grey button will turn off the NXT instead of ending the program.

If you forget the code and want to set a new one, simply delete the file 'LockCode.bat' from the NXT using somthing like [NeXT Explorer](http://bricxcc.sourceforge.net/utilities.html) or [NeXT Commander](http://nextcommander.sourceforge.net/).
There is also a program incuded in the zip file, `Delete Code.nxc` that will do just that.

[Discuss on the Mindboards Forums](https://sourceforge.net/apps/phpbb/mindboards/viewtopic.php?f=4&t=1473)

## Changelog

### 1.0.2
	Released on 2012-10-06
* Removed splash image
* Fixed sercurity issue with the user being able to turn off the NXT while the sound was being played

### 1.0.1
	Released on 2012-05-06
* The NXT cannot be turned off for 10 seconds to prevent it from locking up.

### 1.0 
	Released on 2012-05-04
* Initial release