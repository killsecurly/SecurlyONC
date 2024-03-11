# SecurlyONC
Network config ONC file to completely disable extensions such as GoGuardian and Securly.<br/>
<br/>
The software `SecurlyONC` comes without any sort of warranty. All damages or inconvenience caused by SecurlyONC is all the user's liablity.<br/>
## __v1.3.0 Stable for Chrome__<br/>
### How to Enable<br/>
1. Go to `chrome://network#state` and click on `+` next to the network you want to enable ONC on.<br/>
2. Go to main page at `https://killsecurly.github.io/ONC` and paste all text that appeared after the `+`.<br/>
3. Click `Download ONC`. You should not touch `Advanced DNS Options` unless instructed to do so.<br/>
4. Unzip the file that you downloaded. It will be named `network.zip`.<br/>
5. Take out the two files `kill.onc` and `revive.onc`. Keep both of them safe inside a folder.<br/>
6. Go to `chrome://network` and upload `kill.onc` under `Upload ONC File`.<br/>

### How to Disable<br/>
1. Upload `revive.onc` onto Import ONC File. You can find `revive.onc` in the ZIP you downloaded.<br/>

### Notes<br/>
__Turn on when Securly Classroom is Off__<br/>
If you start ONC with Securly Classroom on, the device will never get the signal to turn Classroom off, which causes the flitering to stay active forever.<br/>

## Past Bugs<br/>
Currently, the ONC network config blocks these SSO (Single-Sign-On) Applications:<br/>
Clever, CPM Educational Program, Writable<br/>
Turn off by using `revive.onc` when you have to turn on SSO.<br/>

## Credits<br/>
Works with Securly, GoGuardian, CKAuth, and more!<br/>
Credit to omadaDNS, caub, dragon73101, and killsecurly.<br/>
