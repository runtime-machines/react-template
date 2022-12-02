# React Repository Template

[![GitHub issues](https://img.shields.io/github/issues/runtime-machines/react-template.svg)](https://github.com/runtime-machines/react-template/issues)
[![GitHub last commit](https://img.shields.io/github/last-commit/runtime-machines/react-template.svg)](https://github.com/runtime-machines/react-template/commits/master)
[![Build Status](https://github.com/runtime-machines/react-template/actions/workflows/ci.yml/badge.svg)](https://github.com/runtime-machines/react-template/actions)
[![codecov](https://codecov.io/github/runtime-machines/react-template/branch/master/graph/badge.svg?token=ML6UOZQGV7)](https://codecov.io/github/runtime-machines/react-template)

⭐ `Star` this repository if you find it valuable and worth maintaining.

👁 `Watch` this repository to get notified about new releases, issues, etc.

## Description

This is a GitHub repository template for a React website.
You can use it:

- to create a new repoisitory with automation and environment setup,
- as reference when improving automation for an existing repository.

It includes:

- continuous integration via [GitHub Actions](https://github.com/features/actions),
- build automation via [Yarn](./package.json),
- dependency management using [NPM Packages](https://docs.npmjs.com/),
- code formatting and linting using [eslint](https://eslint.org/docs/latest/),
- code coverage [HTML report](https://create-react-app.dev/docs/running-tests/)
- dependencies scanning and updating thanks to [Dependabot](https://dependabot.com),
- security code analysis using [CodeQL Action](https://docs.github.com/en/github/finding-security-vulnerabilities-and-errors-in-your-code/about-code-scanning),

## Usage

1. Sign up on [Codecov](https://codecov.io/) and configure
   [Codecov GitHub Application](https://github.com/apps/codecov) for all repositories.
1. Click the `Use this template` button (alt. clone or download this repository).
1. Replace all occurrences of `runtime-machines/react-template` to `your_org/repo_name` in all files.
1. Update the following files:
   - [CHANGELOG.md](CHANGELOG.md)
   - [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
   - [LICENSE](LICENSE) (when defined)
   - [README.md](README.md)

## Install

```sh
yarn
```

## Develop

```sh
yarn start

```

## Build

```sh
yarn build

```

## Lint

```sh
yarn lint

```

## Test

```sh
yarn test

```

## Test Coverage

```sh
yarn test:coverage

```

## Details

## Folder Structure

```
.
├── public                        # Express server static path and Webpack bundles output
│   ├── favicon.ico               # App favicon
│   ├── logo192.png               # App logo small
│   ├── logo512.png               # App logo large
│   └── manifest.json             # App favicon and logo manifest
├── src                           # App source code
│   ├── config                    # App configuration by environments
│   ├── app                    	  # App root component
│   ├── components                # Reusable components
│   ├── pages                     # Page components
│   ├── layouts                   # Layouts available to the whole project (e.g. footer etc.)
│   ├── utils                     # App-wide utils (e.g. mock store creator for testing etc.)
│   ├── static                    # Static assets (e.g. images, fonts etc.)
│   └── routes                    # Routes configuration for both client-side and server-side
├── webpack*                      # Webpack configurations
├── tsconfig.json                 # TypeScript configuration
└── .eslintrc.*                   # ESLint configuration
```

## Supported Browsers

This setup uses [Browserslist](https://github.com/browserslist/browserslist) to target browsers.

The default list of supported browsers is listed in the `package.json` file:

```json
{
  "browserslist": {
    "production": [">0.2%", "not dead", "not op_mini all"],
    "development": ["last 1 chrome version", "last 1 firefox version", "last 1 safari version"]
  }
}
```

This means that supported browsers vary based on current usage data.

## License

This project license

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the license, shall be
licensed as above, without any additional terms or conditions.

See [CONTRIBUTING.md](CONTRIBUTING.md).
