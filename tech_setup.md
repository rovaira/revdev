## Tech Setup

A quick resource list of the tools I use to setup my development environment.

### Setup Scripts
- https://github.com/thoughtbot/laptop - Laptop is a script to set up an OS X laptop for web development.

### Terminal & Shell
- https://www.iterm2.com/ - better terminal

**Set iTerm to Reuse Previous Session's Directory:** `Preferences -> Profiles -> General -> Working Directory` 

- https://github.com/robbyrussell/oh-my-zsh

**Verify that zsh if the default shell**

Go to system preferences -> Users & Accounts -> click the lock -> enter your password -> right click on your account (control+click) -> hit advanced options -> verify your login shell is /bin/zsh -> if not, change it and reboot.

Finish the Oh My ZSH installation by restarting iTerm.

### Editors
- https://atom.io/ - Atom 

**Configure Atom**
```
# 'Atom' -> 'Open Your Config'
'global':
  'exception-reporting':
    'userId': 'fd9c7c10-b8c6-0f9d-a902-9c1c19bbc862'
  'welcome':
    'showOnStartup': false
  'core': {}
  'editor':
    'invisibles': {}
    'tabLength': 2
  'whitespace':
    'ensureSingleTrailingNewline': true
    'removeTrailingWhitespace': true
```
**Open file in Atom from terminal:**
`'Atom' -> 'Install Shell Commands'`

**Set Atom as default:**
`echo "export EDITOR=\"/usr/local/bin/atom --wait\"" >> ~/.zshrc`

### Ruby Version Control

### Fun
- http://bowtieapp.com/ - nice Apple desktop app to sync w/ Spotify
