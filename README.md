# LockCode - Protect your NXT at startup

Ever wanted to protect your NXT from a pesky brother or sister?

When you startup your NXT, instead of showing the startup animation, it will prompt for a four digit code. The code must be entered correctly before you can access your NXT. If you enter the wrong code, the NXT will flash a message, otherwise, the program will end, allowing you to access your NXT. The dark grey button will turn off the NXT instead of ending the program.

If you use the NXC Enhanced Firmware, the dark grey exit button will not simple exit the program, instead it will turn off the NXT. LockCode *can* be used without the enhanced firmware, but this functionality will be disabled, decreasing the usefulness of this program.

The first time the program is run it will ask you to set a code. If you forget the code and want to set a new one, simply delete the file `LockCode.dat` from the NXT using something like [NeXT Explorer](http://bricxcc.sourceforge.net/utilities.html) or [NeXT Commander](http://nextcommander.sourceforge.net/).
There is also a program included, [`Delete Code.nxc`](https://github.com/bungeshea/LockCode/blob/master/DeleteCode.nxc), that will do the same.

[Discuss on the Mindboards Forums](https://sourceforge.net/apps/phpbb/mindboards/viewtopic.php?f=4&t=1473)

## Changelog

### 1.0.2
__Released on 6<sup>th</sup> October 2012__

* Removed splash image
* Fixed security issue with the user being able to exit the program while the startup sound was being played

### 1.0.1
__Released on 6<sup>th</sup> May 2012__

* The NXT cannot be turned off for 10 seconds to prevent it from locking up.

### 1.0 
__Released on 4<sup>th</sup> May 2012__

* Initial release