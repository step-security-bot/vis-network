# Vis-network

![version](https://img.shields.io/badge/dynamic/json.svg?style=for-the-badge&url=https://raw.githubusercontent.com/NodeSecure/vis-network/master/package.json&query=$.version&label=Version)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=for-the-badge)](https://github.com/NodeSecure/vis-network/commit-activity)
[![OpenSSF
Scorecard](https://api.securityscorecards.dev/projects/github.com/NodeSecure/vis-network/badge?style=for-the-badge)](https://api.securityscorecards.dev/projects/github.com/NodeSecure/vis-network)
[![mit](https://img.shields.io/github/license/Naereen/StrapDown.js.svg?style=for-the-badge)](https://github.com/NodeSecure/vis-network/blob/master/LICENSE)
![build](https://img.shields.io/github/actions/workflow/status/NodeSecure/vis-network/node.js.yml?style=for-the-badge)

NodeSecure [Vis.js](https://visjs.org/) network front-end module.

## Getting Started

This package is available in the Node Package Repository and can be easily installed with [npm](https://docs.npmjs.com/getting-started/what-is-npm) or [yarn](https://yarnpkg.com).

```bash
$ npm i @nodesecure/vis-network
# or
$ yarn add @nodesecure/vis-network
```

## Usage example

```js
// Import Third-party Dependencies
import { NodeSecureDataSet, NodeSecureNetwork } from "@nodesecure/vis-network";

document.addEventListener("DOMContentLoaded", async () => {
  const secureDataSet = new NodeSecureDataSet();
  await secureDataSet.init();

  new NodeSecureNetwork(secureDataSet);
});
```

## API

- [NodeSecureDataSet](./docs/NodeSecureDataSet.md)
- [NodeSecureNetwork](./docs/NodeSecureNetwork.md)

## Scripts

The project scripts are used for those who want to test the code.

- **npm start** to start an httpserver from `./dist`
- **npm run build** to build the `./example` with esbuild.

> **Note**: The start command run the build command before launching the http server.

## Contributors ✨

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-BADGE:END -->

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://www.linkedin.com/in/thomas-gentilhomme/"><img src="https://avatars.githubusercontent.com/u/4438263?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Gentilhomme</b></sub></a><br /><a href="https://github.com/NodeSecure/vis-network/commits?author=fraxken" title="Code">💻</a> <a href="https://github.com/NodeSecure/vis-network/commits?author=fraxken" title="Documentation">📖</a> <a href="https://github.com/NodeSecure/vis-network/pulls?q=is%3Apr+reviewed-by%3Afraxken" title="Reviewed Pull Requests">👀</a> <a href="#security-fraxken" title="Security">🛡️</a> <a href="https://github.com/NodeSecure/vis-network/issues?q=author%3Afraxken" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/im-codebreaker"><img src="https://avatars.githubusercontent.com/u/53506859?v=4?s=100" width="100px;" alt=""/><br /><sub><b>im_codebreaker</b></sub></a><br /><a href="https://github.com/NodeSecure/vis-network/commits?author=im-codebreaker" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/PierreDemailly"><img src="https://avatars.githubusercontent.com/u/39910767?v=4?s=100" width="100px;" alt=""/><br /><sub><b>PierreD</b></sub></a><br /><a href="https://github.com/NodeSecure/vis-network/commits?author=PierreDemailly" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

## License

MIT
