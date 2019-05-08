# SDB-Enhanced-fixed-
SDB Enhanced is/was a Chrome extension by Coreha and is considered by some to be one of the best quality of life-enhancing extensions for Neopets. This extension suddenly stopped working - it's become broken on the Chrome app store and attempting to reinstall older versions wouldn't work. 
After poking around the extension's code, (https://github.com/coreha/neopets/tree/master/sdb-enhanced) and doing some legwork of my own, it seems Google may have changed some of their requirements for what is considered a valid extension manifest. I have removed the offending line and trailing comma, and it's working for me, so I thought I would share it. 
I am no expert at this sort of development, but this change does not seem to impact functionality in any evident way.
