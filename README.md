# My Shell Scripts
This is the centralized repository of all my personal shell scripts which I use for a number of different purposes.

**Important:**  I am a novice programmer and I bear no responsibility whatsoever if any of these scripts that I have written wipes your computer, destroys your data, crashes your car, or otherwise causes mayhem and destruction.  USE AT YOUR OWN RISK.

## What's here

* **etc/** - This directory contains the various configuration files for the scripts contained elsewhere.
* **lib/** - Located in the `lib` folder are a number of shared scripting libraries that I use throughout my other scripts.
* **setupScripts/** - This directory contains my scripts that configure new computers from scratch.  Including:
	* Insalling [Homebrew][1] & associated packages
	* Installing mac applications using [Homebrew Cask][2]
	* Configuring OSX
	* Syncing user preferences and files using [Mackup][3]
	* Installing [RVM][4] and associated Gems
	* Pushing a new SSH key to Github
* **syncScripts/** - I use [RSYNC][5] and [Unison][6] all the time to sync various computers, drives, and servers.  I keep my base syncing scripts here.

[1]: http://brew.sh
[2]: http://caskroom.io
[3]: https://github.com/lra/mackup
[4]: https://rvm.io
[5]:http://en.wikipedia.org/wiki/Rsync
[6]: http://www.cis.upenn.edu/~bcpierce/unison/