# awesome-nodejs

Here is a chart that compares the npm and Yarn equivalent commands:

| npm command | Yarn equivalent |
| --- | --- |
| `npm install` | `yarn install` |
| `npm install --save` | `yarn add` |
| `npm install --save-dev` | `yarn add --dev` |
| `npm install --save-optional` | `yarn add --optional` |
| `npm install <package>@latest` | `yarn upgrade <package>` |
| `npm uninstall <package>` | `yarn remove <package>` |
| `npm update` | `yarn upgrade` |
| `npm cache clean` | `yarn cache clean` |
| `npm init` | `yarn init` |
| `npm publish` | `yarn publish` |
| `npm run <script>` | `yarn run <script>` |
| `npm test` | `yarn test` |
| `npm login` | `yarn login` |
| `npm logout` | `yarn logout` |
| `npm view <package>` | `yarn info <package>` |
| `npm list` | `yarn list` |
| `npm outdated` | `yarn outdated` |
| `npm owner ls <package>` | `yarn owners ls <package>` |
| `npm owner add <user> <package>` | `yarn owners add <user> <package>` |
| `npm owner rm <user> <package>` | `yarn owners rm <user> <package>` |
| `npm link` | `yarn link` |
| `npm unlink` | `yarn unlink` |
| `npm pack` | `yarn pack` |
| `npm audit` | `yarn audit` |
| `npm audit fix` | `yarn audit fix` |

Note that some of the npm commands may have slightly different behavior or options in Yarn. For example, the `yarn add` command has a `--peer` option that corresponds to the `--save-peer` option in npm, and the `yarn run` command has a `--silent` option that corresponds to the `--silent` option in
