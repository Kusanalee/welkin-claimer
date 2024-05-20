# Welkin-Claimer ![AppleScript Badge](https://img.shields.io/badge/AppleScript-Scripting-blue)

The Welkin-Claimer is an AppleScript program designed to automate the process of opening  Genshin Impact app, performing a series of click actions, and then quitting the app. (this description was totally not written by gpt because i couldn't be bothered)

## How it works

1. The script first opens the Genshin Impact app.
2. It waits for a specified delay (default is 30 seconds).
3. It performs a left click at a specified location.
4. It repeats the delay and click two more times.
5. Finally, it quits the Genshin Impact app.

## Customizable Delay

The delay between each click is customizable. By default, it's set to 30 seconds, but you can easily adjust this to fit your preferences. Simply update the delay value in the script to the number of seconds you prefer.

## Pre-requisites

Before using this script, please ensure that Genshin Impact is installed on your Mac using PlayCover. The script will of course not do anything if the game isn't installed. 
[PlayCover](https://github.com/PlayCover/PlayCover/)

Be sure to grant accessibility access too - as this script just uses Apple's accessibility framework to claim your welkin.

## Bypassing Security Warnings

If you encounter a warning that says the app "cannot be checked for malicious software" when you try to open it for the first time, don't worry. This is a common macOS security feature for apps that aren't signed. To bypass this, follow these steps:

1. Try to open the app normally first and close the warning dialog that appears.
2. Find the app in your Applications folder or wherever you saved it.
3. Right-click (or control-click) on the app and select "Open" from the context menu.
4. When the warning dialog appears again, you'll see an option to open the app anyway. Click "Open".


## Disclaimer

This script is provided as is, and you bear the risks of using it. The author is not responsible for any consequences of its use. Please use responsibly and ensure you understand what the script does before running it.

