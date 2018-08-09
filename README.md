[![Build Status](https://travis-ci.org/MicheleBertoli/css-in-js.svg?branch=master)](https://travis-ci.org/MicheleBertoli/css-in-js)

# CSS in JS

React: [CSS in JS](https://speakerdeck.com/vjeux/react-css-in-js) techniques comparison.

## Usage

Inside each package folder, run:

```bash
npm i
npm run build && open index.html
```

## Features

**How to read the table**

More ticks doesn't mean "better", it depends on your needs.
For example, if a package supports the css file extraction you can run the autoprefixing at build time.

| Package | Version | Automatic Vendor Prefixing | Pseudo Classes | Media Queries | Styles As Object Literals | Extract CSS File | Package Stats |
| :------ | :-----: | :------------------------: | :------------: | :-----------: | :-----------------------: | :--------------: | :------------ |
| [styled-components](https://github.com/styled-components/styled-components)<div><sub><a href="https://www.npmjs.com/package/styled-components" target="_blank" title="npm version"><img src="./ReadmeSrc/img/tag.svg" width="12" alt="tag" /></a> 3.3.3</sub> <sub><a href="https://github.com/styled-components/styled-components/stargazers" target="_blank" title="stars on Github"><img src="./ReadmeSrc/img/star.svg" width="12" alt="star" /></a> 17306</sub></div> | 3.2.6 | ✓ | ✓ | ✓ |  |  | <div><sub><a href="https://github.com/styled-components/styled-components/issues" target="_blank" title="open / closed issues"><img src="./ReadmeSrc/img/info.svg" width="12" alt="info" /></a> 104/1092</sub></div><div><sub><a href="https://www.npmjs.com/package/styled-components" target="_blank" title="monthly downloads"><img src="./ReadmeSrc/img/download.svg" width="12" alt="download" /></a> 1085338</sub></div> |
| [react-native-web](https://github.com/necolas/react-native-web)<div><sub><a href="https://www.npmjs.com/package/react-native-web" target="_blank" title="npm version"><img src="./ReadmeSrc/img/tag.svg" width="12" alt="tag" /></a> 0.8.6</sub> <sub><a href="https://github.com/necolas/react-native-web/stargazers" target="_blank" title="stars on Github"><img src="./ReadmeSrc/img/star.svg" width="12" alt="star" /></a> 9653</sub></div> | 0.0.11 | ✓ |  |  | ✓ | ✓ | <div><sub><a href="https://github.com/necolas/react-native-web/issues" target="_blank" title="open / closed issues"><img src="./ReadmeSrc/img/info.svg" width="12" alt="info" /></a> 21/739</sub></div><div><sub><a href="https://www.npmjs.com/package/react-native-web" target="_blank" title="monthly downloads"><img src="./ReadmeSrc/img/download.svg" width="12" alt="download" /></a> 51794</sub></div> |
| [radium](https://github.com/FormidableLabs/radium)<div><sub><a href="https://www.npmjs.com/package/radium" target="_blank" title="npm version"><img src="./ReadmeSrc/img/tag.svg" width="12" alt="tag" /></a> 0.24.0</sub> <sub><a href="https://github.com/FormidableLabs/radium/stargazers" target="_blank" title="stars on Github"><img src="./ReadmeSrc/img/star.svg" width="12" alt="star" /></a> 6372</sub></div> | 0.13.5 | ✓ | ✓ | ✓ | ✓ |  | <div><sub><a href="https://github.com/FormidableLabs/radium/issues" target="_blank" title="open / closed issues"><img src="./ReadmeSrc/img/info.svg" width="12" alt="info" /></a> 84/475</sub></div><div><sub><a href="https://www.npmjs.com/package/radium" target="_blank" title="monthly downloads"><img src="./ReadmeSrc/img/download.svg" width="12" alt="download" /></a> 857067</sub></div> |
| [react-css-modules](https://github.com/gajus/react-css-modules)<div><sub><a href="https://www.npmjs.com/package/react-css-modules" target="_blank" title="npm version"><img src="./ReadmeSrc/img/tag.svg" width="12" alt="tag" /></a> 4.7.3</sub> <sub><a href="https://github.com/gajus/react-css-modules/stargazers" target="_blank" title="stars on Github"><img src="./ReadmeSrc/img/star.svg" width="12" alt="star" /></a> 4641</sub></div> | 3.0.2 |  | ✓ | ✓ |  | ✓ | <div><sub><a href="https://github.com/gajus/react-css-modules/issues" target="_blank" title="open / closed issues"><img src="./ReadmeSrc/img/info.svg" width="12" alt="info" /></a> 47/152</sub></div><div><sub><a href="https://www.npmjs.com/package/react-css-modules" target="_blank" title="monthly downloads"><img src="./ReadmeSrc/img/download.svg" width="12" alt="download" /></a> 172299</sub></div> |
| [aphrodite](https://github.com/Khan/aphrodite)<div><sub><a href="https://www.npmjs.com/package/aphrodite" target="_blank" title="npm version"><img src="./ReadmeSrc/img/tag.svg" width="12" alt="tag" /></a> 2.2.2</sub> <sub><a href="https://github.com/Khan/aphrodite/stargazers" target="_blank" title="stars on Github"><img src="./ReadmeSrc/img/star.svg" width="12" alt="star" /></a> 4175</sub></div> | 1.2.3 | ✓ | ✓ | ✓ | ✓ | ✓ | <div><sub><a href="https://github.com/Khan/aphrodite/issues" target="_blank" title="open / closed issues"><img src="./ReadmeSrc/img/info.svg" width="12" alt="info" /></a> 63/133</sub></div><div><sub><a href="https://www.npmjs.com/package/aphrodite" target="_blank" title="monthly downloads"><img src="./ReadmeSrc/img/download.svg" width="12" alt="download" /></a> 358386</sub></div> |
| [emotion](https://github.com/tkh44/emotion)<div><sub><a href="https://www.npmjs.com/package/emotion" target="_blank" title="npm version"><img src="./ReadmeSrc/img/tag.svg" width="12" alt="tag" /></a> 9.2.4</sub> <sub><a href="https://github.com/tkh44/emotion/stargazers" target="_blank" title="stars on Github"><img src="./ReadmeSrc/img/star.svg" width="12" alt="star" /></a> 4101</sub></div> | 6.0.3 | ✓ | ✓ | ✓ | ✓ | ✓ | <div><sub><a href="https://github.com/tkh44/emotion/issues" target="_blank" title="open / closed issues"><img src="./ReadmeSrc/img/info.svg" width="12" alt="info" /></a> 73/306</sub></div><div><sub><a href="https://www.npmjs.com/package/emotion" target="_blank" title="monthly downloads"><img src="./ReadmeSrc/img/download.svg" width="12" alt="download" /></a> 260249</sub></div> |
| [glamorous](https://github.com/paypal/glamorous)<div><sub><a href="https://www.npmjs.com/package/glamorous" target="_blank" title="npm version"><img src="./ReadmeSrc/img/tag.svg" width="12" alt="tag" /></a> 4.13.1</sub> <sub><a href="https://github.com/paypal/glamorous/stargazers" target="_blank" title="stars on Github"><img src="./ReadmeSrc/img/star.svg" width="12" alt="star" /></a> 3607</sub></div> | 4.12.5 | ✓ | ✓ | ✓ | ✓ | ✓ | <div><sub><a href="https://github.com/paypal/glamorous/issues" target="_blank" title="open / closed issues"><img src="./ReadmeSrc/img/info.svg" width="12" alt="info" /></a> 1/183</sub></div><div><sub><a href="https://www.npmjs.com/package/glamorous" target="_blank" title="monthly downloads"><img src="./ReadmeSrc/img/download.svg" width="12" alt="download" /></a> 795853</sub></div> |
| [styled-jsx](https://github.com/zeit/styled-jsx)<div><sub><a href="https://www.npmjs.com/package/styled-jsx" target="_blank" title="npm version"><img src="./ReadmeSrc/img/tag.svg" width="12" alt="tag" /></a> 2.2.7</sub> <sub><a href="https://github.com/zeit/styled-jsx/stargazers" target="_blank" title="stars on Github"><img src="./ReadmeSrc/img/star.svg" width="12" alt="star" /></a> 3275</sub></div> | 0.0.7 | ✓ | ✓ | ✓ |  | ✓ | <div><sub><a href="https://github.com/zeit/styled-jsx/issues" target="_blank" title="open / closed issues"><img src="./ReadmeSrc/img/info.svg" width="12" alt="info" /></a> 21/284</sub></div><div><sub><a href="https://www.npmjs.com/package/styled-jsx" target="_blank" title="monthly downloads"><img src="./ReadmeSrc/img/download.svg" width="12" alt="download" /></a> 186617</sub></div> |
| [glamor](https://github.com/threepointone/glamor)<div><sub><a href="https://www.npmjs.com/package/glamor" target="_blank" title="npm version"><img src="./ReadmeSrc/img/tag.svg" width="12" alt="tag" /></a> 2.20.40</sub> <sub><a href="https://github.com/threepointone/glamor/stargazers" target="_blank" title="stars on Github"><img src="./ReadmeSrc/img/star.svg" width="12" alt="star" /></a> 3196</sub></div> | 2.1.0 | ✓ | ✓ | ✓ | ✓ | ✓ | <div><sub><a href="https://github.com/threepointone/glamor/issues" target="_blank" title="open / closed issues"><img src="./ReadmeSrc/img/info.svg" width="12" alt="info" /></a> 79/206</sub></div><div><sub><a href="https://www.npmjs.com/package/glamor" target="_blank" title="monthly downloads"><img src="./ReadmeSrc/img/download.svg" width="12" alt="download" /></a> 842621</sub></div> |
| [css-loader](https://github.com/webpack/css-loader)<div><sub><a href="https://www.npmjs.com/package/css-loader" target="_blank" title="npm version"><img src="./ReadmeSrc/img/tag.svg" width="12" alt="tag" /></a> 0.28.11</sub> <sub><a href="https://github.com/webpack/css-loader/stargazers" target="_blank" title="stars on Github"><img src="./ReadmeSrc/img/star.svg" width="12" alt="star" /></a> 2770</sub></div> | 0.15.6 |  | ✓ | ✓ |  | ✓ | <div><sub><a href="https://github.com/webpack/css-loader/issues" target="_blank" title="open / closed issues"><img src="./ReadmeSrc/img/info.svg" width="12" alt="info" /></a> 59/496</sub></div><div><sub><a href="https://www.npmjs.com/package/css-loader" target="_blank" title="monthly downloads"><img src="./ReadmeSrc/img/download.svg" width="12" alt="download" /></a> 7442704</sub></div> |
| [styletron-react](https://github.com/rtsao/styletron)<div><sub><a href="https://www.npmjs.com/package/styletron" target="_blank" title="npm version"><img src="./ReadmeSrc/img/tag.svg" width="12" alt="tag" /></a> 3.0.4</sub> <sub><a href="https://github.com/rtsao/styletron/stargazers" target="_blank" title="stars on Github"><img src="./ReadmeSrc/img/star.svg" width="12" alt="star" /></a> 2485</sub></div> | 2.1.2 | ✓ | ✓ | ✓ | ✓ | ✓ | <div><sub><a href="https://github.com/rtsao/styletron/issues" target="_blank" title="open / closed issues"><img src="./ReadmeSrc/img/info.svg" width="12" alt="info" /></a> 59/82</sub></div><div><sub><a href="https://www.npmjs.com/package/styletron" target="_blank" title="monthly downloads"><img src="./ReadmeSrc/img/download.svg" width="12" alt="download" /></a> 5709</sub></div> |

> This list has been auto-updated ([?](https://github.com/albinotonnina/mmarkdown)) on June 29, 2018

## Testimonials

> ["Wow, this totally makes my week!"](https://twitter.com/dan_abramov/status/604260877622202368) - Dan Abramov

> ["nice compilation of css-in-js techniques"](https://twitter.com/tjholowaychuk/status/739812614239195136) - TJ Holowaychuk

[SurviveJS / Styling React](http://survivejs.com/webpack_react/styling_react/) by Juho Vepsäläinen

[The Case for CSS Modules](http://markdalgleish.github.io/presentation-the-case-for-css-modules) by Mark Dalgleish

[First Class Styles](https://markdalgleish.github.io/presentation-first-class-styles) by Mark Dalgleish

[Styling React.JS applications](https://www.youtube.com/watch?v=19gqsBc_Cx0) by Max Stoiber

## Contributing

If your package is not listed here, feel free to add it.

1.  Create a new folder named `package-name` in the root folder.
2.  Implement the red button example using the package.
3.  Add a new entry to [data.json](webpage/src/data.json).
4.  Rename `ReadmeSrc/.env_example` to `ReadmeSrc/.env` and set a [Github access token](https://github.com/settings/tokens) to retrieve data from Github.
5.  Re-generate the data with: `cd ReadmeSrc && yarn && yarn update-data && yarn generate-readme`.
