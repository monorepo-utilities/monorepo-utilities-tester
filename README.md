# Monorepo Utilities Tester 🧱

This monorepo repository is constructed to test each [Monorepo Utility](https://github.com/monorepo-utilities/monorepo-utilities). 👌

---

## Why

This monorepo repository consists of packages in more than 1 directory, written mainly in TypeScript (ignoring config). 

It is built to provide end-to-end testing of [Monorepo Utilities](https://github.com/monorepo-utilities/monorepo-utilities). 

## Setup

#### Install

```sh
git clone git@github.com:monorepo-utilities/monorepo-utilities-tester.git 
cd monorepo-utilities-tester
```

#### Configure

```sh
nvm i && yarn
```

---

## Scripts

#### Start dev servers

```sh
yarn start
# concurrently runs all apps
# ---
# => app-bar => http:0.0.0.0:3001
# => app-foo => http:0.0.0.0:3000
# => service-bar => http:0.0.0.0:3002
# => service-foo => http:0.0.0.0:3003
```

#### Run tests

```sh
yarn test
# => runs all tests
```

#### Build

```sh
yarn build
# => builds src to dist
```

---

## Tech and Cites

This project was constructed using [Lerna](https://lerna.js.org/) for monorepo capabilities, [Create React App's TypeScript template](https://create-react-app.dev/), and [Express TypeScript Starter](https://github.com/seanpmaxwell/express-generator-typescript). 

## Help

This repository is built using 2 different starters. The rapid progress  that using starters provided leaves tests and linting out of alignment. 

Help with those updates would be grately appreciated! 🙏
