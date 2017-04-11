# Sublime JSX

This is a simple (and crude) implementation of JSX syntax highlighting for Sublime Text 3 that extends the default JavaScript patterns.

Currently all of the JSX syntax highlighting packages depend on the ES6 highlighting from Babel and/or JavaScriptNext packages which do not use the correct scopes for highlighting JavaScript files.

See here for more information:

- https://github.com/sublimehq/Packages/issues/133
- https://github.com/sublimehq/Packages/issues/63
- https://github.com/sublimehq/Packages/pull/96
- https://github.com/sublimehq/Packages/commit/409ccb469bca8bcc2a5c70c562d1db3428d3015f

## Installation

If you are using Sublime Package Control you can press `command+shift+p`. Then select `Package Control: Install Package` and choose `Simple JSX`.

## Usage

Highlighting should be enabled by default for files that end with a `.jsx` extension.

To turn on JSX highlighting for other files, open a JavaScript file containing JSX then press `command+shift+p` and select `Set Syntax: JSX`.

You can also select `View -> Syntax -> Open all with current extension as…` and select `JSX` from the top nav to enable highlighting for all files with a certain extension (`.js`, `.jsx`, etc).

## Screenshots

#### Before

![](https://cloud.githubusercontent.com/assets/259316/24020697/abdc0caa-0a73-11e7-87d3-9b1e600ec24d.png)

#### After

![](https://cloud.githubusercontent.com/assets/259316/24020706/b24fc2f2-0a73-11e7-924e-fbcf12c21b63.png)
