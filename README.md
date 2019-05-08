To those who don't know or might have forgotten, SDB Enhanced is/was a Chrome extension by Coreha and is considered by some to be one of the best quality of life-enhancing extensions for Neopets. For those who need an overview, check out its Chrome extension page (https://chrome.google.com/webstore/detail/neopets-sdb-enhanced/fneefihgecbpnkhpoimbhnobkbcfopdc?hl=en). Don't try to download/install from there, though - it's broken.

A few months ago, this extension suddenly stopped working - it's become broken on the Chrome app store and attempting to reinstall older versions wouldn't work. After poking around the extension's GitHub (https://github.com/coreha/neopets/tree/master/sdb-enhanced) and doing some legwork of my own, it seems Google may have changed some of their requirements for what is considered a valid extension manifest. I have removed the offending line and trailing comma, and it's working for me, so I thought I would share it. I am no expert at this sort of development, but this change does not seem to impact functionality in any evident way.

To install:

1. Download the .zip archive

2. Extract the archive somewhere on your hard drive

3. Open Chrome's Extensions menu (chrome://extensions/)

4. Click "Pack extension" in the upper-left corner

5. Click "Browse" under "Extension root directory"

6. Navigate to where you extracted the archive and select the root folder ("sdb-enhanced")

7. Click "Pack extension"

8. Enjoy!

It should be noted that this may be an older version of the extension and that I am not the developer, so there may be small issues, but I have not noticed any myself. This archive also does not include the original readme files; if you need a readme, check the GitHub link above.

**Important:** 
A feature of this extension could be considered against Neopets rules - namely, the option to have the extension search Neopets as a logged out user for exact item rarities ("Lookup rarities" in the settings menu). This feature should be disabled by default (check it just in case), and should you choose to use it, you assume your own risk of getting your account frozen.

All credit for this extension goes to Coreha. I did not write any of it, I just removed offending code to make it functional again.
