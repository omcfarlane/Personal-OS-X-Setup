# Mac OS X Setup
This document describes how I set up my personal OS X computers. For a complete list of apps, scripts and modifications, see here. 

I am a regular person. I consider myself an Apple enthusiast and a budding power-user. That said, this setup is designed to maximize OS X’s strengths in it’s speed, security, extensibility through settings and third-party apps for the “average person”. In the end, OS X will manage my writing, photos, music; but I’ll also be able to more easily complete actions with greater ease. For example: 
1. creating an appointment. 
2. rating a song in iTunes from any app. 
3. have a clear menu bar and desktop 
4. Pull files out of subdirectories and into 1 (flatten a folder) 
5. remember all your passwords.

Please feel free to send me any feedback or questions you may have.

Updated for **[OS X Yosemite 10.10.3] (https://support.apple.com/en-us/HT204490)**.

# !! PLEASE Take Notice !!
Remember that this is _my_ personal setup. I do my best to keep the language as general as possible, but I cannot be responsible for anything that happens as a result of this guide. Sorry.	

## Software update
Run Apple’s software update and make sure everything is up to date.

 → About This Mac → Software Update

## System Preferences
?Can this be done through .dotfiles? 
Defaults!
1. 
2. 
3. 

## 1Password
1Password is password management software. They really put it best: tktk. (1Password was the first time I truly fell in love with software. See my full ode here).



## Applescripts & Automator Scripts
## Safari Extensions
## Terminal Commands#

```sh
# Disable the “Are you sure you want to open this application?” dialog
defaults write com.apple.LaunchServices LSQuarantine -bool false
```

## Cask?
### 3. Install softwares


#### homebrew-cask

Many softwares can be installed through
[homebrew-cask](https://github.com/phinze/homebrew-cask) which makes the
process way simpler:

```sh
# install homebrew-cask
brew tap phinze/homebrew-cask
brew install brew-cask

# essential
brew cask install adium
brew cask install caffeine
brew cask install dropbox
brew cask install one-password

# dev
brew cask install charles
brew cask install cornerstone
brew cask install filezilla
brew cask install imagealpha
brew cask install imageoptim
brew cask install iterm2
brew cask install livereload
brew cask install macvim
brew cask install sequel-pro
brew cask install virtualbox
brew cask install vagrant

# utils
brew cask install divvy
brew cask install istat-menus
brew cask install notational-velocity
brew cask install the-unarchiver
brew cask install vlc

# browsers
brew cask install firefox
brew cask install google-chrome

# others
brew cask install limechat
brew cask install skype
brew cask install right-zoom
brew cask install u-torrent

# quick look plugins (https://github.com/sindresorhus/quick-look-plugins)
brew cask install qlcolorcode qlstephen qlmarkdown quicklook-json qlprettypatch quicklook-csv betterzipql webp-quicklook suspicious-package && qlmanage -r
```


## Apps

### Manually
1. [Dropbox (Experimental Build)] (https://forums.dropbox.com/topic.php?id=90322)
2. [1Password] (https://agilebits.com/onepassword/mac)
3. [Chrome] (https://www.google.com/intl/en/chrome/browser/)
4. [1Password Extension for Chrome] (https://agilebits.com/extensions/mac/chrome.html)
5. [Hazel] (http://www.noodlesoft.com/hazel.php)
6. [TextExpander] (http://smilesoftware.com/TextExpander/)
7. Adobe Photoshop (via Adobe Creative Cloud)
8. [Secrets] (http://secrets.blacktree.com/)
9. Flux


### App Store
1. [Fantastical] (https://itunes.apple.com/us/app/fantastical/id435003921?mt=12)
2. [iA Writer] (https://itunes.apple.com/us/app/ia-writer/id439623248?mt=12)
3. [The Unarchiver] (https://itunes.apple.com/us/app/the-unarchiver/id425424353?mt=12)
4. [Divvy] (https://itunes.apple.com/us/app/divvy-window-manager/id413857545?mt=12)

### Additional Apps

Games + Entertainment

1. [rdio] (http://www.rdio.com/apps/)

## System Preferences
General → Show scroll bars: Always  
Security & Privacy → General → Allow applications downloaded from: Anywhere  
Keyboard → Modifier Keys… → Caps Lock Key: No Action  
Keyboard → Keyboard Shortcuts → Full Keyboard Access: All controls  
Universal Access → Check Enable access for assistive devices  
Sharing → Computer Name: Aang  
Sharing → File Sharing → Movies (for AppleTV)
