Git clone using `git clone --recursive` to clone all submodules (zsh plugins).

## Firefox
- Run `firefox-setup.sh <username of new firefox profile>` and it will setup [argenfox user.js](https://github.com/arkenfox/user.js) for you.
- **I use custom firefox sync server, so if you don't plan to use it, delete it from `user-overrides.js`**
- Extensions
  - [Decentraleyes](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/)
  - [I don't care about cookies](https://addons.mozilla.org/en-US/firefox/addon/i-dont-care-about-cookies/)
  - [SponsorBlock](https://addons.mozilla.org/en-US/firefox/addon/sponsorblock/)
    - '.local/share/sponsorblock.backup.json` 
  - [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
    - `.local/share/ublock-origin.backup.txt`

## VS Code
- Copy `.local/share/vscode-settings.json` into `~/Library/Application Support/Code/User`. Rename it to just `settings.json`
