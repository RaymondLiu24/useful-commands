# macOS commands

###### Resources
- [herrbischoff/awesome-macos-command-line](https://github.com/herrbischoff/awesome-macos-command-line)

### Show/Hide Hidden Files
#### Show
```sh
defaults write com.apple.finder AppleShowAllFiles TRUE
killall Finder
```
#### Hide
```sh
defaults write com.apple.finder AppleShowAllFiles FALSE
killall Finder
```
