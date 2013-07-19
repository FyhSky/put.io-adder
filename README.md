## Put.io magnet: and .torrent Handler for OS X

![alt tag](http://f.cl.ly/items/3Q2t3g311h442c3o1z0K/Screen%20Shot%202013-07-19%20at%209.31.28%20PM.png)

*put.io adder* is a small, open source app for OS X, that registers as new handler for **magnet** URI schemes, so that every
time you click on a manget link, it will automatically add it to your [put.io](http://put.io/) download queue.

Versions 1.4 and above now automatically upload .torrent files you choose to open with the app, and add them to the download
queue as well. There are three ways to do that:

- Drag the .torrent file onto the app icon
- Make *put.io adder* your default handler for .torrent files
- Or right click the torrent and pick "Open with" > put.io adder

Versions 2.0 and above now let you see your current transfers. Double clicking a transfer will open it in the browser,
so you can download it. Support for multiple languages has been added. Feel free to add more!

Follow me on Twitter: [@nicoSWD](https://twitter.com/nicoSWD)!

**NOTES**
- The app requires you to have a [put.io](http://put.io/) account. They're probably not free anymore.
- The app requires KeyChain Access to store put.io's OAuth Token. Denying access might prevent the app from working.

*IMPORTANT:* I added [AFNetworking](https://github.com/AFNetworking/AFNetworking), [PutioKit](https://github.com/PutioKit/PutioKit), and [SSKeyChain](https://github.com/samsoffes/sskeychain) as submodules. 
So if you want to clone the entire repo, please use:

`$ git clone --recursive git@github.com:nicoSWD/put.io-adder.git`

Please [report issues](https://github.com/nicoSWD/put.io-adder/issues) you may encounter. Pull requests are also very welcome!

**DOWNLOADS**
- Newest
  - [put.io adder v2.0](https://nicoswd.com/public/files/putio/put.io-adder-2.0.zip) (MD5 checksum: 4303bb677c36f979d4b7216e4d8343eb)
- Older releases
  - [put.io adder v1.6](http://cl.ly/QFQc) (MD5 checksum: 2fb7b99167707643171edafe29211ea1)
  - [put.io adder v1.5](http://cl.ly/Q7KN) (MD5 checksum: cdf44f9f3dc956fa9e538b168aa1ddec)
  - [put.io adder v1.4](http://cl.ly/Q5sv) (MD5 checksum: 608372b538a55a2d48826c77eef95cea)
  - [put.io adder v1.3](http://cl.ly/Q6ak) (MD5 checksum: 477afa6d458347c6d24b9af0a53a2ab8)
  - [put.io adder v1.2](http://cl.ly/Q5Vx) (MD5 checksum: c82b0c5007c7dd2cd56ad64eb911112f)
  - [put.io adder v1.1](http://cl.ly/Q4uX) (MD5 checksum: f0dad56b625b78d2ef503f3113ff4e55)
  - [put.io adder v1.0](http://cl.ly/Q4r2) (MD5 checksum: 826fb0c5280783bc2b9d08e921255b82)

**SCREENSHOTS**

![alt tag](http://f.cl.ly/items/3Q2t3g311h442c3o1z0K/Screen%20Shot%202013-07-19%20at%209.31.28%20PM.png)
![alt tag](http://f.cl.ly/items/0Y3n24003K0Z2c2X2s2i/Screen%20Shot%202013-07-19%20at%209.31.39%20PM.png)
![alt tag](http://f.cl.ly/items/420N3Y1w3N0h3U27451I/Screen%20Shot%202013-07-19%20at%209.31.48%20PM.png)

**CHANGELOG**
- v.2.0 (Big update)
  - View your transfers (double click opens file in browser)
  - Support for multiple languages (feel free to add more)
  - Added preferences pane (⌘ + ,)
  - Automatically checks for updates
- v1.6 (by [orta](https://github.com/orta))
  - Support for auto closing after uploading (option in menu bar)
  - Minor design changes
  - Auth window improvements
- v1.5
  - Added UTTypeIconFile
  - Version # in UI
  - Changed text a bit
- v1.4
  - Added support for .torrent files
  - Changed UI
  - Added PutIO Kit
- v1.3
  - Displays account info
  - Added link to GitHub repo in menu bar
- v1.2
  - Now displays the "display name" instead of the magnet URL
  - Moved code a bit around
  - Better error control
- v1.1
  - Now compiles with Xcode 4
  - Compatible with OS X < 10.8
  - New Design
- v1.0
  - Initial release

**MIT/X11 LICENSE**

Copyright (C) 2013 Nicolas Oelgart

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
