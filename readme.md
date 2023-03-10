# Top.gg voter bot

Top.gg Voter is a simple desktop app that allows you to vote for your favorite Discord bots on Top.gg.

[![Github All Releases](https://img.shields.io/github/downloads/nozzOne/topgg-voter/total.svg)]()

## Features

-   Vote for multiple bots at once
-   Multiples accounts support (cookies)
-   Bypass hcaptcha using [hektCaptcha-extension](https://github.com/Wikidepia/hektCaptcha-extension)
-   Block ads using [uBlock Origin](https://github.com/gorhill/uBlock)

## Requirements

-   [Windows 10](https://www.microsoft.com/en-us/software-download/windows10)
-   [Google Crome](https://www.google.com/chrome/)

## Installation

1.  Download the latest release from [Here](https://github.com/NozzOne/topgg-voter/releases/latest)
2.  Extract the zip file or execute the portable version
3.  Run the `topgg-voter.exe` file
   
## Usage

1. Enter all ids of bots you want to vote for in the `Bots` field
2. Enter your cookies in the `Cookies` field (see [How to get cookies](#how-to-get-cookies))
3. Click `Vote` to start the voting process
4. Now you can minimize the app and it will continue to vote for you in the background, you can close from the tray icon.
5. [INFO] if you want to add multiple accounts you must use incognito mode, since the account cookie is deleted when you log out or switch to another account. You should also keep in mind that cookies last for 30 days stored in top.gg
6. [INFO] You can add all the cookies you want. 
7. [INFO] The app check each 1 hour if you have to vote again.
8. [INFO] In the first run the app create a shortcut in the startup folder, so you don't need to open the app every time you turn on your pc.
## How to get cookies

1. Open Google Chrome
2. Install the [EditThisCookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg) extension (if you don't know how to get cookies)
3. go to [top.gg](https://top.gg/) and login
4. After open the EditThisCookie extension and copy the `connect.sid` cookie value
5. Congrats, you now have your cookies!



## Screenshots

![Screenshot](https://i.imgur.com/QOYZs7Y.png)

# Disclaimer

- This app is not affiliated with Top.gg in any way. Use at your own risk.

- This app not save any data, it only uses the cookies to vote for the bots.


