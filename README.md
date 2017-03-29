# 2PaswordsManager
**This is Chrome extension that know how to password.**

*(Actually just a simple password generator)*

1. Open some site
2. Click to 2PaswordsManager icon
3. Input your login and 2 passwords for manager
4. Choose password length
5. ...
6. Profit. 

![alt text](
https://camo.githubusercontent.com/7de8b142f459b306303a06314b9a683a41fb37cb/68747470733a2f2f70702e757365726170692e636f6d2f633633393632372f763633393632373038382f31333763302f4b715849453030754531632e6a7067 "2PaswordsManager screenshoot")


## How to install extensions in Chrome

1. Open [chrome://extensions/](chrome://extensions/)
2. Check "Developer mode" checkbox
3. Click "Load unpacked extension…"
4. Choose folder with your extension
5. Have fun!


## So how this works?

1. This extension use [Framework 7](https://framework7.io/) for UI (but it is not necessary, I use it because I want try how it will be works in extension)
2. It use iterations of md5 into all inputed data
3. Finaly it use own hash function to create password from md5 string
+ So you cant reconstruct md5 string from password
+ You cant reconstruct inputed data from md5 string 
