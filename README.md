# Awesome MDN
> A curated list of awesome things related to MDN.

MDN is an open-source, collaborative project by Mozilla in partnership with a global community of volunteers and partners.

### Contents
- [Official Resources](#official-resources)
- [Contributor tools](#contributor-tools)
- [Projects using BCD data](#projects-using-bcd-data)
- [Community](#community)
- [License](#license)

### Official Resources
- [About MDN](https://developer.mozilla.org/en-US/about)
- [Curriculum](https://mdn.dev/curriculum)
- [Content Repo](https://github.com/mdn/content)
- [Platform Repo](https://github.com/mdn/yari)
- [BCD](https://github.com/mdn/browser-compat-data)
- [Firefox Release Notes](https://developer.mozilla.org/en-US/docs/Mozilla/Firefox/Releases)
- [MDN Blog](https://developer.mozilla.org/en-US/blog)

### Contributor tools
- Please don't hesitate to create a PR if you have more resources to share.

### Projects using BCD data
Here are some projects using the data, as an [npm module](https://www.npmjs.com/browse/depended/@mdn/browser-compat-data) or directly:

- [Add-ons Linter](https://github.com/mozilla/addons-linter) - NPM package that checks add-ons for features that aren't supported by the targeted Firefox version. Used by [addons.mozilla.org](https://addons.mozilla.org/) and the [web-ext](https://github.com/mozilla/web-ext/) tool.
- [ast-metadata-inferer](https://www.npmjs.com/package/ast-metadata-inferer) - NPM package that annotates JavaScript AST nodes with metadata derived from BCD data. Used by [eslint-plugin-compat](https://www.npmjs.com/package/eslint-plugin-compat).
- [BCD Watch](https://bcd-watch.igalia.com/) - Website that shows a weekly report of BCD changes.
- [caniuse](https://caniuse.com/) - Website that shows browser support tables based on caniuse and BCD data.
- [caniuse-lite](https://github.com/browserslist/caniuse-lite) - NPM package that republishes BCD data in the caniuse format.
- [CanIUse Embed](https://caniuse.bitsofco.de/) - Service that allows embedding caniuse (including BCD data) into any website.
- [css-declaration-sorter](https://www.npmjs.com/package/css-declaration-sorter) - NPM package that sorts CSS properties alphabetically.
- [csstype](https://www.npmjs.com/package/csstype) - NPM package that publishes strict TypeScript/Flow types for CSS.
- [Compat Report](https://addons.mozilla.org/en-US/firefox/addon/compat-report/) - Firefox Add-on that shows BCD data for the current site in the developer tools.
- [compat-tester](https://github.com/SphinxKnight/compat-tester) - NPM package that scans HTML, CSS and JS files for compatibility issues.
- [JetBrains WebStorm](https://www.jetbrains.com/webstorm/) - IDE that uses BCD data to [check browser support of used CSS properties](https://www.jetbrains.com/guide/javascript/tips/browser-compatibility-css/) (see [2019.1 releasenotes](https://web.archive.org/web/20190524063428/http://www.jetbrains.com/webstorm/whatsnew/#:~:text=Browser%20compatibility%20check%20for%20CSS)) by [generating feature lists with support data](https://github.com/JetBrains/intellij-community/blob/master/xml/xml-psi-impl/mdn-doc-gen/src/GenerateMdnDocumentation.kt).
- [JSR](https://jsr.io/) - Package registry that uses BCD data to [generate a list of web builtins](https://github.com/jsr-io/jsr/blob/main/tools/generate_web_symbols.ts).
- [Mozilla Firefox](https://www.mozilla.org/firefox/) - Web browser that uses BCD data in the DevTools to show [CSS property compatibility data](https://searchfox.org/mozilla-central/source/devtools/shared/compatibility/README.md) mapped against a [list of non-retired browsers](https://github.com/firefox-devtools/remote-settings-mdn-browser-compat-data/).
- [TypeScript](https://www.typescriptlang.org/) - Programming language that uses BCD data to [generate DOM typings](https://github.com/microsoft/TypeScript-DOM-lib-generator).
- [Visual Studio Code](https://code.visualstudio.com) - IDE that uses BCD to show compatibility information for [CSS features](https://github.com/microsoft/vscode-custom-data/blob/c008a80baa3c6ea9d6757d2640eaab215b28f9a6/web-data/css/generateData.js#L349) (see [VSCode 1.25 release notes](https://code.visualstudio.com/updates/v1_25#_improved-accuracy-of-browser-compatibility-data)), and to [extract MDN urls for HTML elements](https://github.com/microsoft/vscode-custom-data/blob/c008a80baa3c6ea9d6757d2640eaab215b28f9a6/web-data/html/generateData.js#L53-L67).
- [web-features](https://www.npmjs.com/package/web-features) - NPM package that publishes web feature groups with Baseline statuses based on BCD data.
- [web-features-explorer](https://web-platform-dx.github.io/web-features-explorer/) - Website that visualizes web features by Baseline status and month.
- [`webhint.io`](https://webhint.io/docs/user-guide/hints/hint-compat-api/) - Tool that uses BCD to checks CSS and HTML for unsupported features (see [`@hint/utils-compat-data` package](https://github.com/webhintio/hint/tree/main/packages/utils-compat-data)).

### Community
- [Discord](https://mdn.dev/discord)
- [GitHub](https://github.com/mdn)
- [X](https://x.com/MozDevNet)
- [Mastodon](https://mastodon.com/@MDN)

### License
MDN's resources are freely available under various open-source licenses. For detailed information on reusing MDN content, check out our Attribution and Copyright Licensing page.

