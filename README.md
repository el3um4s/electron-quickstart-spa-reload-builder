# ![logo](https://raw.githubusercontent.com/el3um4s/electron-quickstart-spa-reload-builder/master/src/icons/64x64.png) Electron Quickstart: SPA + RELOAD + BUILDER

A quickstart for an SPA electron app with auto reload and builder system

**Clone and run for a quick way to see Electron in action.**

This is a minimal Electron application based on the [Quick Start Guide](https://electronjs.org/docs/tutorial/quick-start) within the Electron documentation.

**Use this app along with the [Electron API Demos](https://electronjs.org/#get-started) app for API code examples to help you get started.**

A basic Electron application needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.

I added 3 packages:

- `electron-builder` - [npm](https://www.npmjs.com/package/electron-builder) - A complete solution to package and build a ready for distribution Electron, Proton Native or Muon app for macOS, Windows and Linux with “auto update” support out of the box.
- `electron-reload` - [npm](https://www.npmjs.com/package/electron-reload) - This is (hopefully) the simplest way to load contents of all active BrowserWindows within electron when the source files are changed.
- `electron-is-dev` - [npm](https://www.npmjs.com/package/electron-is-dev) - Check if Electron is running in development.

You can learn more about each of these components within the [Quick Start Guide](https://electronjs.org/docs/tutorial/quick-start).

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/el3um4s/electron-quickstart-spa-reload-builder
# Go into the repository
cd electron-quickstart-spa-reload-builder
# Install dependencies
npm install
# Run the app
npm start
```

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## Additions

Although this is quite similar to [electron-quick-start](https://github.com/electron/electron-quick-start), I have actually utilized some work done by [Cameron Adams](https://github.com/CameronAdams777) and [Santiago García da Rosa](https://github.com/SantiagoGdaR) to bring in the SPA aspect.

- [https://github.com/CameronAdams777/electron-spa-quickstart](https://github.com/CameronAdams777/electron-spa-quickstart)
- [https://github.com/SantiagoGdaR/vanilla-spa](https://github.com/SantiagoGdaR/vanilla-spa)
- [medium.com - Js: Vanilla SPA](https://medium.com/frontend-fun/js-vanilla-script-spa-1b29b43ea475)

## Resources for Learning Electron

- [electronjs.org/docs](https://electronjs.org/docs) - all of Electron's documentation
- [electronjs.org/community#boilerplates](https://electronjs.org/community#boilerplates) - sample starter apps created by the community
- [electron/electron-quick-start](https://github.com/electron/electron-quick-start) - a very basic starter Electron app
- [electron/simple-samples](https://github.com/electron/simple-samples) - small applications with ideas for taking them further
- [electron/electron-api-demos](https://github.com/electron/electron-api-demos) - an Electron app that teaches you how to use Electron
- [hokein/electron-sample-apps](https://github.com/hokein/electron-sample-apps) - small demo apps for the various Electron APIs

## License

[MIT](LICENSE.md)
