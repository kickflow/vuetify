# @kickflow/vuetify

kickflowが使用するVuetifyのforkリポジトリです。

## 使用方法

package.json内のVuetifyのバージョン指定を以下のように変更後、`yarn install`を実行してください。

```
- "vuetify": "3.5.1"
+ "vuetify": "npm:@kickflow/vuetify@3.5.1-kickflow2"
```

## ブランチ

`kickflow`ブランチに必要なコミットを追加します。
`master`ブランチは本家に一致するように、コミットしないでください。

## バージョニング

ベースとなっているupstreamのVuetifyのバージョンの末尾に、`-kickflowN` を付与します。
例: `3.5.1-kickflow1`

## npmへの公開手順

```
cd packages/vuetify
yarn build
yarn publish
```

同時に、タグも打ちましょう。

```
git tag v3.5.1-kickflow2
```

---

<p align="center">
  <a href="https://vuetifyjs.com" target="_blank">
    <img alt="Vuetify Logo" width="100" src="https://cdn.vuetifyjs.com/images/logos/logo.svg">
  </a>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/vuetify">
    <img src="https://img.shields.io/npm/dt/vuetify.svg" alt="Downloads">
  </a>
  <a href="https://www.npmjs.com/package/vuetify">
    <img src="https://img.shields.io/npm/dm/vuetify.svg" alt="Downloads">
  </a>
  <br>
  <a href="https://github.com/vuetifyjs/vuetify/blob/master/LICENSE.md">
    <img src="https://img.shields.io/npm/l/vuetify.svg" alt="License">
  </a>
  <a href="https://community.vuetifyjs.com">
    <img src="https://discordapp.com/api/guilds/340160225338195969/widget.png" alt="Chat">
  </a>
  <br>
  <a href="https://www.npmjs.com/package/vuetify">
    <img src="https://img.shields.io/npm/v/vuetify.svg" alt="Version">
  </a>
  <a href="https://cdnjs.com/libraries/vuetify">
    <img src="https://img.shields.io/cdnjs/v/vuetify.svg" alt="CDN">
  </a>
</p>

### 💖 Supporting Vuetify

Vuetify is a [MIT licensed](http://opensource.org/licenses/MIT) project that is developed and maintained full-time by [John Leider](https://github.com/johnleider) and [Heather Leider](https://github.com/heatherleider); with support from the entire [Core Team](https://vuetifyjs.com/about/meet-the-team/). Sponsor Vuetify and receive some **awesome perks** and support Open Source Software at the same time! 🎉

<ul>
  <li>
    <a href="https://github.com/users/johnleider/sponsorship">Become a backer or sponsor on GitHub</a>
    or <a href="https://www.patreon.com/vuetify">Patreon</a> <small>(supports John and Heather)</small>
  </li>
  <li>
    <a href="https://opencollective.com/vuetify">Become a backer or sponsor on Open Collective</a>
    <strong><small>(supports the Core team)</small></strong>
  </li>
  <li>
    <a href="https://tidelift.com/subscription/request-a-demo?utm_source=npm-vuetify&utm_medium=referral&utm_campaign=enterprise">Become a subscriber on Tidelift</a>
  </li>
  <li>
    <a href="https://paypal.me/vuetify">Make a one-time payment with Paypal</a>
  </li>
  <li>
    <a href="https://support.vuetifyjs.com/">Book time with the Team</a>
  </li>
</ul>

### What's the difference between GitHub Sponsors, Patreon, and OpenCollective?

Funds donated through GitHub Sponsors and Patreon go directly to support John and Heather's full-time work on Vuetify. Funds donated via Open Collective are managed with transparent expenses and will be used for compensating work and expenses for Core team members. Your name/logo will receive proper recognition and exposure by donating on either platform.

<h3><b>Special Sponsor</b></h3>

<table>
  <tbody>
    <tr>
      <td>
        <a href="https://www.teamwork.com/" target="_blank">
          <img height="35px" src="https://cdn.cosmicjs.com/4fbb7ab0-612e-11ed-af1a-0faa4245afee-teamwork.png">
        </a>
      </td>
    </tr>
  </tbody>
</table>

<h3><b>Diamond Sponsors</b></h3>

<table>
  <tbody>
    <tr>
      <td>
        <a href="https://github.com/sponsors/johnleider" target="_blank">
          Your Logo Here
        </a>
      </td>
    </tr>
  </tbody>
</table>

<h3><b>Platinum Sponsors</b></h3>

<table>
  <tbody>
    <tr>
      <td>
        <a href="https://careers.lmax.com/?utm_source=vuetify&utm_medium=github-link&utm_campaign=lmax-careers">
          <img height="30px" src="https://cdn.vuetifyjs.com/images/backers/lmax-exchange.png">
        </a>
      </td>
      <td>
        <a href="http://intygrate.com/?ref=vuetify-github">
          <img height="30px" src="https://cdn.vuetifyjs.com/images/backers/intygrate.png">
        </a>
      </td>
      <td>
        <a href="http://vuemastery.com/?ref=vuetify-github">
          <img height="30px" src="https://cdn.vuetifyjs.com/images/backers/vuemastery.svg">
        </a>
      </td>
      <td>
        <a href="http://crossword-solver.io/">
          <img height="35px" src="https://cdn.cosmicjs.com/098aa4e0-9749-11eb-bf6a-1ffd0f06b0f7-crossword-solver-logo-light.svg">
        </a>
      </td>
    </tr>
    <tr></tr>
    <tr>
      <td>
        <a href="https://www.slim.ai/">
          <img height="30px" src="https://cdn.cosmicjs.com/e7d53ff0-4ca5-11ec-9940-53a088b36636-slim-ai.svg">
        </a>
      </td>
      <td>
        <a href="https://crosswordanswers911.net/">
          <img height="30px" src="https://cdn.cosmicjs.com/ef6ea2a0-7ee1-11ed-8730-d9eebcd39d9f-crossword-answers-911.jpg">
        </a>
      </td>
      <td style="text-align: center;">
        <a href="https://www.muenchen.de/">
          <img height="40px" src="https://imgix.cosmicjs.com/af2ce530-eaa2-11ed-ba82-019c4666da06-itm-logo.png">
        </a>
      </td>
      <td>
        <a href="https://justanotherpanel.com/">
          <img height="30px" src="https://cdn.cosmicjs.com/8d038320-6382-11ee-b975-cb0cfadd93ad-jap.png">
        </a>
      </td>
    </tr>
  </tbody>
</table>

<br>

### ⚡ Quick Start

Getting started with Vuetify is easy. To create a new project, choose your package manager and run one of the following commands:

Using [yarn](https://yarnpkg.com/)

```bash
yarn create vuetify
```

Using [npm](https://npmjs.com/)

```bash
npm create vuetify
```

Using [pnpm](https://pnpm.io/)

```bash
pnpm create vuetify
```

Using [bun](https://bun.sh/)

```bash
bun create vuetify
```

For more information on how to get started, such as using Nuxt or Laravel, check out the official [Installation guide](/getting-started/installation/).

### 🚀 Introduction

Vuetify is a no design skills required UI Library with beautifully handcrafted Vue Components. No design skills required — everything you need to create amazing applications is at your fingertips. Vuetify has a massive API that supports any use-case. Some highlights include:

- **Customizable:** Extensive customization options with [SASS/SCSS](https://vuetifyjs.com/features/sass-variables/) and [Default configuration](https://vuetifyjs.com/features/presets/) and [Blueprints](https://vuetifyjs.com/features/blueprints/)
- **Responsive Layout:** The default configuration of Vuetify components is responsive, allowing your application to adapt to different screen sizes.
- **Theme System:** A powerful color system that makes it easy to style your application with a consistent color palette.
- **Vite Support:** _Smaller_ bundle sizes with **automatic** tree-shaking
- **18 months** Long-term support for [Major releases](https://vuetifyjs.com/introduction/long-term-support/)
- **Internationalization:** 42+ supported languages

#### Browser Support

Vuetify supports all **modern browsers**, including Safari 13+ (using [polyfills](https://vuetifyjs.com/getting-started/browser-support)). Components are designed for a minimum width of _320px_.

### 🌎 Vuetify Ecosystem

#### Resources

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://support.vuetifyjs.com/?ref=github">
          💫&nbsp;Enterprise&nbsp;Support
        </a>
      </td>
      <td>Let the experts at Vuetify help you get the most out of your application with a customized support plan from the the team behind the framework</td>
    </tr>
    <tr>
      <td>
        <a href="https://community.vuetifyjs.com/?ref=github">
          💭&nbsp;Discord&nbsp;Community
        </a>
      </td>
      <td>Our massive and inclusive Discord server where you can ask questions, share feedback, and connect with other Vuetify developers</td>
    </tr>
    <tr>
      <td>
        <a href="https://play.vuetifyjs.com/?ref=github">
          🎮&nbsp;Vuetify&nbsp;Play
        </a>
      </td>
      <td>A Vuetify 3 playground built using <a href="https://github.com/vuejs/repl">vuejs/repl</a> where you can play with our components</td>
    </tr>
    <tr>
      <td>
        <a href="https://issues.vuetifyjs.com/?ref=github">
          🐛&nbsp;Vuetify&nbsp;Issues
        </a>
      </td>
      <td>A web application for reporting bugs and issues with Vuetify, Documentation, or one of our other packages</td>
    </tr>
    <tr>
      <td>
        <a href="https://store.vuetifyjs.com/?ref=github">
          🛒&nbsp;Vuetify&nbsp;Store
        </a>
      </td>
      <td>The official Vuetify Store where you can download free digital products, purchase pre-made themes, and more</td>
    </tr>
  </tbody>
</table>

#### Packages

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Version</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/create-vuetify">
          🛠️ create-vuetify
        </a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vue-cli-plugin-vuetify">
          <img src="https://img.shields.io/npm/v/create-vuetify.svg" alt="Version">
        </a>
      </td>
      <td>
        Quickly spin up applications with a simple command.
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vuetify-loader/tree/master">
          📦 vuetify-loader
        </a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vuetify-loader">
          <img src="https://img.shields.io/npm/v/vuetify-loader.svg" alt="Version">
        </a>
      </td>
      <td>
        Compiler plugins for autoloading Vuetify components
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/eslint-plugin-vuetify">
          📄 eslint-plugin-vuetify
        </a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/eslint-plugin-vuetify">
          <img src="https://img.shields.io/npm/v/eslint-plugin-vuetify.svg" alt="Version">
        </a>
      </td>
      <td>
       An opinionated eslint-plugin for Vuetify
      </td>
    </tr>
  </tbody>
</table>

### 🖥️ Documentation

To check out the docs, visit [vuetifyjs.com](https://vuetifyjs.com).

![Crowdin Uploads](https://github.com/vuetifyjs/vuetify/workflows/Crowdin%20Uploads/badge.svg?branch=master)

### 🙋‍♂️ Questions

For help and support questions, please use our [Discord community](https://community.vuetifyjs.com). This issue list of this repo is **exclusively** for bug reports and feature requests.

### 🐛 Issues

Use our [Issue generator](https://issues.vuetifyjs.com) to report bugs and request new features.

Please make sure to read the [Important Information](https://github.com/vuetifyjs/vuetify/blob/master/.github/CONTRIBUTING.md#important-information) before opening an issue. Issues not confirming to the guidelines may be closed immediately.

### 📝 Changelog

Detailed changes for each release are documented in the [release notes](https://vuetifyjs.com/getting-started/release-notes/).

### 💁‍♂️ Contributing

Developers interested in contributing should read the [Code of Conduct](./CODE_OF_CONDUCT.md) and the [Contribution Guide](https://vuetifyjs.com/getting-started/contributing/).

> Please do **not** ask general questions in an issue. Issues are only to report bugs, suggest
  enhancements, or request new features. For general questions and discussions, ask in the [community chat](https://community.vuetifyjs.com/).

To help you get you familiar with our contribution process, we have a list of [good first issues](https://github.com/vuetifyjs/vuetify/labels/good%20first%20issue) that contain bugs which have a relatively limited scope. This is a great place to get started. If you have any questions, please join us on the [community chat](https://community.vuetifyjs.com).

We also have a list of [help wanted](https://github.com/vuetifyjs/vuetify/labels/help%20wanted) issues that you might want to check.

### 📑 License

Vuetify is available under the [MIT](http://opensource.org/licenses/MIT) software license.

Copyright (c) 2016-present Vuetify, LLC

----

This project exists thanks to all the people who contribute 😍!

<a href="https://github.com/vuetifyjs/vuetify/graphs/contributors"><img src="https://opencollective.com/vuetify/contributors.svg?width=890&button=false" /></a>
