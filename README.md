# Awesome MDN

> A curated list of awesome things related to MDN Web Docs.

MDN is an open-source, collaborative project by Mozilla in partnership with a global community of volunteers and partners.
This repository lists resources and projects, highlighting official and community-built tools for MDN authors, and a list of projects that incorporate data from MDN.

**Contents:**

- [Official Resources](#official-resources)
- [Contributor tools](#contributor-tools)
- [Projects using BCD](#projects-using-bcd)
- [Community](#community)
- [License](#license)

## Official resources

- [About MDN](https://developer.mozilla.org/en-US/about) - MDN's mission, team, partners, and projects.
- [Curriculum](https://mdn.dev/curriculum) - Structured learning resources and modules for web development education.
- [Content Repo](https://github.com/mdn/content) - Source repository for MDN's (en-US) documentation and examples.
- [Yari](https://github.com/mdn/yari) - MDN's React-based frontend, including tools for building the site.
- [BCD](https://github.com/mdn/browser-compat-data) - Browser compatibility data for web technologies used on MDN and other projects.
- [Firefox release notes for developers](https://developer.mozilla.org/en-US/docs/Mozilla/Firefox/Releases) - Changes in Firefox releases that developers can target in their projects.
- [MDN Blog](https://developer.mozilla.org/en-US/blog) - Official blog with updates, news, and insights from the MDN team.

## Contributor tools

Please open a PR to have your tools featured in this list.

- [skyclouds2001/mdn-tool](https://github.com/skyclouds2001/mdn-tools) - A tool focusing on maintaining [mdn/data](https://github.com/mdn/data) repo, using feature information from [content repo](https://github.com/mdn/content), [bcd](https://github.com/mdn/browser-compat-data) to keep data consistent with latest browser support.
- [OnkarRuikar/markdownlint-rule-search-replace](https://github.com/OnkarRuikar/markdownlint-rule-search-replace) - A [markdownlint](https://github.com/DavidAnson/markdownlint) plugin built to handle [custom linting needs](https://github.com/mdn/content/blob/cebc05cfe508d5cd8c6a98359a3913cf19a707d3/.markdownlint.jsonc#L122-L235) of the MDN content.

## Projects using BCD

Here are some projects using data from BCD as an [npm module](https://www.npmjs.com/browse/depended/@mdn/browser-compat-data) or directly:

- [Add-ons Linter](https://github.com/mozilla/addons-linter) - NPM package that checks add-ons for features that aren't supported by the targeted Firefox version. Used by [addons.mozilla.org](https://addons.mozilla.org/) and the [web-ext](https://github.com/mozilla/web-ext/) tool.
- [ast-metadata-inferer](https://www.npmjs.com/package/ast-metadata-inferer) - NPM package that annotates JavaScript AST nodes with metadata derived from BCD data. Used by [eslint-plugin-compat](https://www.npmjs.com/package/eslint-plugin-compat).
- [BCD Watch](https://bcd-watch.igalia.com/) - Website that shows a weekly report of BCD changes.
- [caniuse](https://caniuse.com/) - Website that shows browser support tables based on caniuse and BCD data.
- [caniuse-lite](https://github.com/browserslist/caniuse-lite) - NPM package that republishes BCD data in the caniuse format.
- [CanIUse Embed](https://caniuse.bitsofco.de/) - Service that allows embedding caniuse (including BCD data) into any website.
- [css-declaration-sorter](https://www.npmjs.com/package/css-declaration-sorter) - NPM package that sorts CSS properties alphabetically.
- [csstype](https://www.npmjs.com/package/csstype) - NPM package that publishes strict TypeScript/Flow types for CSS.
- [Compat Report](https://addons.mozilla.org/en-US/firefox/addon/compat-report/) - Firefox Add-on that shows BCD data for the current site in the developer tools.
- [compat-tester](https://github.com/SphinxKnight/compat-tester) - NPM package that scans HTML, CSS, and JS files for compatibility issues.
- [JetBrains WebStorm](https://www.jetbrains.com/webstorm/) - IDE that uses BCD data to [check browser support of used CSS properties](https://www.jetbrains.com/guide/javascript/tips/browser-compatibility-css/) (see [2019.1 releasenotes](https://web.archive.org/web/20190524063428/http://www.jetbrains.com/webstorm/whatsnew/#:~:text=Browser%20compatibility%20check%20for%20CSS)) by [generating feature lists with support data](https://github.com/JetBrains/intellij-community/blob/master/xml/xml-psi-impl/mdn-doc-gen/src/GenerateMdnDocumentation.kt).
- [JSR](https://jsr.io/) - Package registry that uses BCD data to [generate a list of web builtins](https://github.com/jsr-io/jsr/blob/main/tools/generate_web_symbols.ts).
- [Mozilla Firefox](https://www.mozilla.org/firefox/) - Web browser that uses BCD data in the DevTools to show [CSS property compatibility data](https://searchfox.org/mozilla-central/source/devtools/shared/compatibility/README.md) mapped against a [list of non-retired browsers](https://github.com/firefox-devtools/remote-settings-mdn-browser-compat-data/).
- [TypeScript](https://www.typescriptlang.org/) - A programming language that uses BCD data to [generate DOM typings](https://github.com/microsoft/TypeScript-DOM-lib-generator).
- [Visual Studio Code](https://code.visualstudio.com) - IDE that uses BCD to show compatibility information for [CSS features](https://github.com/microsoft/vscode-custom-data/blob/c008a80baa3c6ea9d6757d2640eaab215b28f9a6/web-data/css/generateData.js#L349) (see [VSCode 1.25 release notes](https://code.visualstudio.com/updates/v1_25#_improved-accuracy-of-browser-compatibility-data)), and to [extract MDN urls for HTML elements](https://github.com/microsoft/vscode-custom-data/blob/c008a80baa3c6ea9d6757d2640eaab215b28f9a6/web-data/html/generateData.js#L53-L67).
- [web-features](https://www.npmjs.com/package/web-features) - NPM package that publishes web feature groups with Baseline statuses based on BCD data.
- [web-features-explorer](https://web-platform-dx.github.io/web-features-explorer/) - Website that visualizes web features by Baseline status and month.
- [`webhint.io`](https://webhint.io/docs/user-guide/hints/hint-compat-api/) - Tool that uses BCD to checks CSS and HTML for unsupported features (see [`@hint/utils-compat-data` package](https://github.com/webhintio/hint/tree/main/packages/utils-compat-data)).
- [World Wide Web Consortium (W3C)](https://github.com/w3c) - An international community that develops web standards uses BCD [to link MDN documents](https://github.com/w3c/mdn-spec-links#mdn-spec-links) to the features in the published web standards.

## Community

Here are some quick links to MDN community channels:

- [Discord](https://mdn.dev/discord)
- [GitHub](https://github.com/mdn)
- [X](https://x.com/MozDevNet)
- [Mastodon](https://mastodon.com/@MDN)

## License

MDN's resources are freely available under various open-source licenses.
For detailed information on reusing MDN content, check our [Attribution and copyright licensing](https://developer.mozilla.org/en-US/docs/MDN/Writing_guidelines/Attrib_copyright_license) page.
