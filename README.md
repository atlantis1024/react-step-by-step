# 前端技术指南

## :bulb: 引言

初学 React 的时候，相信大部分人都有这样的体会：React 技术栈水太深，涉及的技术点太多了。

如今网上有不少 React 相关的教程，但多的是是完整的 React 项目，少的是庖丁解牛式的、一步步的搭建 React 项目框架的教程。而且，React 涉及的技术点很多，常常让人有种无从入手的感觉。

如果，你也有这样的困惑，不妨阅读一下 [如何学习 React(react-howto)](https://github.com/petehunt/react-howto/blob/master/README-zh.md) 。这篇文章提出了一个合理的学习 React 技术栈的顺序，我认为很有道理。

本教程采用 react-howto 中提出的 React 技术栈学习路线，由浅入深，循序渐进的为你一一讲解 React 。

如果，你有任何疑问或建议，欢迎在 Issues 中提出。

## :memo: 内容

![react-stack](https://raw.githubusercontent.com/dunwu/frontend-tutorial/master/docs/assets/images/react-stack.jpg)

- [**_前端基础 - Html, Css, JavaScript_**](docs/base/README.md)
  - [Html 入门](docs/base/html.md) - 关键词： `标签`, `元素`, `属性`
  - [Css 入门](docs/css)
  - [JavaScript 入门](docs/js)
- [**_Chapter02 - Node, Npm, Yarn_**](docs/nodejs/README.md)
  - [Node.js 入门](docs/nodejs/nodejs.md)
  - [Npm 入门](docs/nodejs/npm.md) - 关键词： `nodejs`, `包管理`, `npm`, `cnpm`
  - [Yarn 入门](docs/nodejs/yarn.md) - 关键词： `nodejs`, `包管理`, `yarn`
- [**_Chapter03 - Webpack_**](docs/chapter03/README.md)
  - [如何学习 Webpack](docs/chapter03/webpack/webpack-howto.md)
  - [Webpack 概念](docs/chapter03/webpack/concept.md)
  - [Webpack 入门](docs/chapter03/webpack/webpack-tutorial.md)
  - [Webpack 资源管理](docs/chapter03/webpack/asset-management.md)
  - [Webpack 代码分离](docs/chapter03/webpack/code-splitting.md)
  - [Webpack 开发工具](docs/chapter03/webpack/development.md)
- [**_Chapter04 - ES6, Babel, ESLint_**](docs/chapter04/README.md)
  - [Babel 入门](docs/chapter04/babel/babel-tutorial.md)
  - [ES6 入门](docs/chapter04/es6/es6-tutorial.md)
  - [ESLint 快速入门](docs/chapter04/eslint/eslint-quickstart.md)
  - [ESLint 配置](docs/chapter04/eslint/eslint-configuration.md)
  - [ESLint 命令](docs/chapter04/eslint/eslint-command.md)
- [**_Chapter01 - React_**](docs/chapter01/README.md)
- [**_Chapter05 - React Router_**](docs/chapter05/README.md)
  - [React Router v4 简介](docs/chapter05/react-router-v4/react-router-introduction.md)
  - [React Router v4 基础](docs/chapter05/react-router-v4/react-router-basic.md)
  - [React Router v4 进阶](docs/chapter05/react-router-v4/react-router-advanced.md)
  - [React Router v4 API](docs/chapter05/react-router-v4/react-router-api.md)
- [**_Chapter06 - Flux, Redux_**](docs/chapter06/README.md)
  - [Flux 入门](docs/chapter06/flux/Flux入门.md)
  - [Redux 入门](docs/chapter06/redux/Redux入门.md)

**Editing...**

## :pushpin: 说明

- **docs** ：所有文档存放于 `docs` 目录。
- **codes** ：所有示例代码存放于 `codes` 目录。

我在学习 React 过程中，发现网上大部分示例动不动就是一大堆 React 技术整合在一起。这让初学者经常感觉很无力：一个技术还没搞懂，就要学另外一个技术，立不动心啊。

所以，我建立了一个连续性项目: `jigsaw（拼图）` 。之所以叫连续性项目，是因为它是一步步引入 React 技术。

每个 `jsgsaw` 目录，都是基于前面 chapter 的基础上，引入本 chapter 重点学习的技术。我觉得，通过这种方式，能更加晰的理解，如何搭建一个完整的 React 项目。
