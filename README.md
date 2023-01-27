# ReverseDucky
A modification of 0iphor13's ReverseDuckyPolymorph found at https://github.com/hak5/usbrubberducky-payloads/tree/master/payloads/library/remote_access/ReverseDuckyPolymorph

I needed to modify the payload because it wasn't working with the current version of PayloadStudio by Hak5.  The modification removes the randomizatin of characters, hence removing polymorphing, but at least it now works.

Setup:  Just put the IP and Port of the attack machine and it's listener into their respective locations in the script. 

This script has the Ducky behave like a thumb drive until the button is pressed, at which point the payload is executed
