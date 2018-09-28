### Some Awkward Operations

------

##### 1. When you just want to change your admin's name of MacOs, and you lost your privileges of admin finally. Yeap, you deleted youself. Please clam down and following the steps：

* Shut down
* Press the key of  `command + s`  when booting , so that you can enter the safe mode.
* After the command line scrolls to stop, you can see the flashing cursor and then hit `enter` .
* Please enter the following command : 
  * `mount -rw /` 
  * `rm var/db/.AppleSetupDone` 
  * `reboot`
* The computer will reboot and return to the interface for the first boot setup. After setting up according to the prompts, you will be logged in as a new admin user.
* Don‘t be worried, although your Mac is as strange as a new machine at the moment, it would be restored as soon as possible.
* Please enter the `System Preferences`  >  `Users & Groups` .
* Select your original admin user and check the option : `Allow user to administer this computer` .
* Now you have two admin users, then you can log out the current account and log in at the origin admin   account. Of course, you can delete the new adimn user, or keep it later.
* Congratulation, everything back to normal ~







