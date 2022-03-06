# VSCodeSettings

With the current version of Visual Studio Code as of this writing (1.22.1), you can find your settings in

- ~/.config/Code/User on Linux (in my case, an, Ubuntu derivative)
- %APPDATA%\Code\User (C:\Users\username\AppData\Roaming\Code\User) on Windows
- ~/Library/Application Support/Code/User/ on Mac OS X (thank you, Christophe De Troyer)
- 
The files are settings.json and keybindings.json. Simply copy them to the target machine.

Your extensions are in

- ~/.vscode/extensions on Linux and Mac OS X
- %USERPROFILE%\.vscode\extensions (C:\Users\username\.vscode\extensions) on Windows (i.e., essentially the same place as on Linux and Mac OS X)
- 
Alternately, just go to the Extensions, show installed extensions, and install those on your target installation. For me, copying the extensions worked just fine, but it may be extension-specific, particularly if moving between platforms, depending on what the extension does.

## Custom snippets

### On Mac:
Put them in ~/Users/<username>/Library/Application Support/Code/User/snippets/
### Windows:
Put them in  %APPDATA%\Code\User\snippets

## Installed Extensions
"*" means i don't know if i need it

In Use:
- DotENV
- EJS language support
- ES7 React/Redux/GraphQL/React-Native snippets
- ESLint
- Gremlins tracker
- Image preview
- indent-rainbow
- Live Server
- Material Icon Theme
- Path Intellisense
- Prettier - Code formatter

Not sure:
- *Auto Rename Tag
- *Babel JavaScript
- *Code Runner
- *Docker
- *GitLens
- *GraphQL
- *GraphQL
- *Language Support for Java(TM) by Red Hat
- *Markdown All in One
- *PHP Intelephense
- *Pug beautify
- *Theme - Oceanic Next
- *TODO Highlight
- *vscode-styled-components
- *Live Sass Compiler
- *Tabnine

## On Mac:
Other GUI apps:
- Chrome
- Slack
- Compass
- Postman

Not GUI:
- Node
- Oh my zsh
- XCode Tools
- then: You typically configure your global username and email address after installing Git.
To set your global username/email configuration:
Open the command line.
Set your username: git config --global user.name "FIRST_NAME LAST_NAME"
Set your email address: git config --global user.email "MY_NAME@example.com"

Maybe later:
- Docker

## On PC:
Install:
- VSCode
- Git bash
- Node
