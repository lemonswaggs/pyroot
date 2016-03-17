# Details #

Bug Fixes:

  * Fix GUI rendering issue, caused execution leaving main loop for too long.  (Probably use threading or something to execute code outside of the main loop inside of a separate thread.  Don't know how well forking would work using python.)


Features:
  * Add device model detection, so that we know what kind of phone we're working with.
  * Add software version detection, so that we know what root to use.
  * Add an easy method for adding new root methods.
  * Add more phones and root methods.