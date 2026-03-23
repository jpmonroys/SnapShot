# Snap Shot [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=See%20this%20react%20example&url=https://yog9.github.io/SnapShot/&hashtags=react,context-api,freecodecamp,developers)

[![Build Status](https://travis-ci.org/Yog9/SnapShot.svg?branch=master)](https://travis-ci.org/Yog9/SnapShot)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HitCount](http://hits.dwyl.com/Yog9/SnapShot.svg)](http://hits.dwyl.com/Yog9/SnapShot)

[Demo of Snap Shot](https://yog9.github.io/SnapShot/)

![](/snapscout.png)

### Summary

Snap Shot is a gallery created using React,React Hooks, React Router and Context API. The Routes were setup for four default pages and a search page. Also the images were displayed using the Flickr API and axios to fetch data.

### Motivation

The purpose of this project was to get familiar with React Hooks and Context API.

### Getting Started

Click the demo link or clone/download the repository on your local machine.
Create a config.js file in api folder inside src folders. In config.js file write
`export const apiKey = "YOUR_FLIKR_API_KEY";`

##### Install dependencies

`yarn install`

##### Run Snap Shot from the root directory.

`yarn start`

### Built With

- React js
- React Router
- React Hooks
- Context API
- Flickr API

### Features

**1. Responsive Design.**

**2. Search functionality added to search photos from API.**

### Coming Soon

- [ ] Cypress E2E Tests

### Contributing

Everyone is welcomed to contribute to this project. You can contribute either by submitting bugs or suggesting improvements by opening an issue on GitHub. Please see the [CONTRIBUTING](CONTRIBUTING.md) guidelines for more information.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### se adiciona lineas actividad 1 integracion continua -  marzo del 2026
--

## Development Environment Setup

### IDE: Visual Studio Code

The team uses **Visual Studio Code (VSCode)** as the standard IDE for this project. It is lightweight, highly extensible, and has excellent support for React and JavaScript development.

#### Installing VSCode

1. Go to [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Download the installer for your operating system (Windows, macOS, or Linux)
3. Run the installer and follow the on-screen instructions
4. Launch VSCode once installation is complete

#### Recommended Extensions

Install the following extensions to improve your development experience on this project:

| Extension | ID | Purpose |
|---|---|---|
| **ESLint** | `dbaeumer.vscode-eslint` | Highlights JavaScript/React linting errors in real time |
| **Prettier - Code Formatter** | `esbenp.prettier-vscode` | Enforces consistent code formatting across the team |
| **ES7+ React/Redux/React-Native snippets** | `dsznajder.es7-react-js-snippets` | Provides handy shortcuts to scaffold React components and hooks |
| **Auto Rename Tag** | `formulahendry.auto-rename-tag` | Automatically renames the matching HTML/JSX closing tag |
| **Path IntelliSense** | `christian-kohler.path-intellisense` | Autocompletes file paths in import statements |
| **GitLens** | `eamodio.gitlens` | Enhances Git integration with inline blame, history, and diff views |
| **Bracket Pair Color DLW** | `BracketPairColorDLW.bracket-pair-color-dlw` | Colors matching brackets to improve JSX readability |

#### Installing Extensions

You can install any extension directly from within VSCode:

1. Open VSCode
2. Press `Ctrl+Shift+X` (Windows/Linux) or `Cmd+Shift+X` (macOS) to open the Extensions panel
3. Search for the extension by name or ID
4. Click **Install**

Alternatively, install all recommended extensions at once from the terminal:

```bash
code --install-extension dbaeumer.vscode-eslint
code --install-extension esbenp.prettier-vscode
code --install-extension dsznajder.es7-react-js-snippets
code --install-extension formulahendry.auto-rename-tag
code --install-extension christian-kohler.path-intellisense
code --install-extension eamodio.gitlens
code --install-extension BracketPairColorDLW.bracket-pair-color-dlw
```

#### Suggested Workspace Settings

Create a `.vscode/settings.json` file at the root of the project with the following content to keep formatting consistent:

```json
{
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.tabSize": 2,
  "eslint.validate": ["javascript", "javascriptreact"]
}
```