# Getting Started

- Install brew package manager: 
    - Installation is this oneliner: ```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```
    - That takes a minute then you can install things with brew, like node
- Install node and npm: ```brew install node npm```
- Download VSCode: https://code.visualstudio.com
- Open VSCode: 
    - ```Cmd+Shift+E``` For Explorer
    - Click Clone Repository
    - ```git@github.com:loganrenz/stencil-starter-package.git```
    - Select a directory to store the files in, like: VSCODE
    - Trust the authors
- Initialize stencil
    - cd playground
    - In VSCode, cmd+shift+c to open a terminal window
    - ```npm init stencil```
    - y
    - Select app
    - Name your app, like: ```chucks-app```
    - Once its created the project,
    - ```cd chucks-app```
    - ```npm install```
    - ```npm start```
    - Safari should open and you should have a running web app!

- Make a change...
    - Go back to VSCode
    - Navigate to playground > chucks-app > src > components > app-root > app-root.tsx
    - Update ```<h1>Stencil App Starter</h1>``` to be ```<h1>Chucks App</h1>```
    - Cmd+S to Save
    - Watch your app live update in the Safari window!

- VSCode Hints
    - Cmd+Shift+P opens the commands list.
    - Cmd+Shift+P, type commit -- Commit your code
    - Cmd+Shift+P, type push -- Push your code