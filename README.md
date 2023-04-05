# macOS configuration

This is a very opiniated write-up of my macOS configuration and apps for two main reasons:
- set up a new device easily
- refer to this document when asked by friends

## apps

### productivity

#### [Raycast](ray.so)
> deserves it's own section
Replaces spotlight on macOS (cmd + space) and is faster, more reliable in terms of search result ranking and extensible through plugins.

##### plugins and shortcuts
built-in features
- clipboard hisory on `option+c`
- file search `option+f`
- window management
- browser bookmark search `option+b`

additional plugins
- GitHub Extension `option+g`
  allows you to directly search for repositories, users, issues, pull requests on GitHub.

---
- browser: Edge
  controversial pick, but: as fast as Chrome, feels more memory-efficient (though I can't prove it), you can disable nearly all of Microsofts bloat and it has a nice, vertical tab view.
  `brew install --cask microsoft-edge`

- todos: Things 3
  clean and fast todo app with a lot of keyboard shortcuts and a very sane / non-bloated interface. no subscription, just one time fee.

- passwords: Bitwarden
  free & open source password manager with good (enough) integrations (browser, cli) and all necessary features
  `brew install --cask bitwarden` and `brew install bitwarden-cli`

- terminal: iterm2 x tmux

- window switcher: alt-tab
  allows you to switch between windows of the same application with `alt+tab` while `cmd+tab` only switches between applications

- learning / flashcards: anki
  `brew install --cask anki`

---

## OS settings

- Dock on the left/right side
  you often have enough screen space horizontally (e.g. on websites the content goes downward not sideways) but not enough vertically (e.g. you may need to scroll often through (web) documents).

- 3-finger-dragging on trackpad
  allows you to replace a hard press on the trackpad with just 3-finger gestures
  hidden away in the system settings under: accessibility > pointer control > trackpad options 

- the classics: show bluetooth, battery percentage and sound settings in menu bar
