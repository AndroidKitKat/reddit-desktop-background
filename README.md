# reddit-desktop-background
Changes Desktop background to top reddit post in set subreddit

# Requirements
Made for Mojave 10.14 in python 2.7 (TODO: add linux/windows support)

* applescript
* pyobjc

# How to?
### Mac

`$ git clone https://github.com/sambattalio/reddit-desktop-background.git`

Set subreddit to desired choice in runBackground.sh (default to earthporn)

`$ crontab -e`

Then, add the following line to crontab window:

`@hourly ~/Path/to/cloned/repo/runBackground.sh`

# Contributing

Please read CONTRIBUTING.md to learn how to contribute

# TODO's
* add init script
* other os support
* easier way to change subreddit / frequency
* REMOVE DEPENDENCY on Virtual environment on my machine
