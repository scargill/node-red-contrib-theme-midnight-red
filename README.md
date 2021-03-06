# Midnight Node-RED theme

![Project Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![GitHub Activity][commits-shield]][commits]
[![GitHub Last Commit][last-commit-shield]][commits]

[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]

## About

A dark theme for [Node-RED][node-red] based on the [midnight theme][ha-midnight-theme] for [Home Assistant][home-assistant].

![screenshot](https://raw.githubusercontent.com/bonanitech/node-red-contrib-theme-midnight-red/master/images/screenshot.png)

## Install

Change to the Node-RED `userDir` directory, usually `~/.node-red`.

```shell
cd ~/.node-red
```

Install this package.

```shell
npm install node-red-contrib-theme-midnight-red
```

Add the folowing to the `editorTheme` section of your `settings.js`.

```js
editorTheme: {
    page: {
        css: "<HOME>/.node-red/node_modules/node-red-contrib-theme-midnight-red/midnight.css",
        scripts: "<HOME>/.node-red/node_modules/node-red-contrib-theme-midnight-red/theme-tomorrow.js"
    }
}
```

Replace `<HOME>` with the home directory of the user running Node-RED. For example, `/home/username`.

For more details on the configuration please refer to the [Node-RED official documentation][node-red-doc].

Restart Node-RED.

Enjoy!

## Development Version

For the development version (compatible with Node-RED 1.0) check the [`NEXT`][next-tag]
tag on NPM or the [`1.0`][dev-branch] branch on GitHub.

## License

MIT License

Copyright (c) 2019 Mauricio Bonani

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[bonanitech]: https://github.com/bonanitech
[buymeacoffee-shield]: https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-2.svg
[buymeacoffee]: https://www.buymeacoffee.com/mbonani
[commits-shield]: https://img.shields.io/github/commit-activity/y/bonanitech/node-red-contrib-theme-midnight-red.svg?style=for-the-badge
[commits]: https://github.com/bonanitech/node-red-contrib-theme-midnight-red/commits/master
[contributors]: https://github.com/bonanitech/node-red-contrib-theme-midnight-red/graphs/contributors
[dev-branch]: https://github.com/bonanitech/node-red-contrib-theme-midnight-red/tree/1.0
[discord-shield]: https://img.shields.io/discord/330944238910963714.svg
[ha-midnight-theme]: https://community.home-assistant.io/t/midnight-theme/28598
[home-assistant]: https://home-assistant.io
[issue]: https://github.com/bonanitech/node-red-contrib-theme-midnight-red/issues
[last-commit-shield]: https://img.shields.io/github/last-commit/bonanitech/node-red-contrib-theme-midnight-red.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/bonanitech/node-red-contrib-theme-midnight-red.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/maintenance/yes/2019.svg?style=for-the-badge
[next-tag]: https://www.npmjs.com/package/node-red-contrib-theme-midnight-red/v/next
[node-red-doc]: https://nodered.org/docs/configuration
[node-red]: https://nodered.org/
