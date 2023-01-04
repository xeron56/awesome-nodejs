# awesome-nodejs
Advantages of yarn over npm 
Yarn is a package manager for JavaScript that was developed by Facebook in collaboration with Exponent, Google, and Tilde. It was designed to improve upon the shortcomings of the npm package manager, and it offers the following benefits:

Faster installation: Yarn uses a lockfile and an optimized dependency tree to reduce the install time for packages, compared to npm.

Offline mode: Yarn allows you to install packages from your local cache, which can be faster and more reliable than installing from the internet.

Deterministic installs: Yarn guarantees that an install that worked on one machine will work exactly the same way on any other machine, as long as the same version of Yarn is used. This can make it easier to reproduce builds across different environments.

Better security: Yarn uses checksums to verify the integrity of installed packages, and it allows you to configure the level of security you want to use when installing packages.

Improved performance: Yarn uses a network concurrency of 5, which can make installations faster than npm, which uses a network concurrency of 3.

Overall, Yarn can be a better choice for projects that require fast, reliable, and deterministic package management. However, npm is still the most widely used package manager for JavaScript, and it is regularly updated with new features and improvements. Ultimately, the choice between npm and Yarn will depend on your specific needs and preferences.

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
