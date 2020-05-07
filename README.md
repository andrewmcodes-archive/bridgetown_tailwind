[coc]: /CODE_OF_CONDUCT.md
[contributing]: /CONTRIBUTING.md
[license]: /LICENSE.md

# Bridgetown + TailwindCSS

[![Netlify Status](https://api.netlify.com/api/v1/badges/2cd7d245-da99-45bd-98fc-5b393eaeac32/deploy-status)](https://app.netlify.com/sites/bridgetown-tailwind/deploys)

A Bridgetown blog with TailwindCSS

## Installation

### Prerequisites

Make sure you have Ruby, Bundler, Node, and Yarn installed.

```sh
➜ ruby -v
ruby 2.6.6p146 (2020-03-31 revision 67876) [x86_64-darwin19]

➜ bundler -v
Bundler version 2.1.4

➜ node -v
v13.11.0

➜ yarn -v
1.22.4
```

### Clone

```sh
git clone https://github.com/andrewmcodes/bridgetown_tailwind.git
cd bridgetown_tailwind
bundle install && yarn install
```

### Start

To start the blog, run:

```sh
yarn start
```

and navigate to `http://localhost:4000`.

## Deployment

### Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/andrewmcodes/bridgetown_tailwind)

## Community

### Contributing

[Contributing Guide][contributing]

### Code of Conduct

[Code of Conduct][coc]

### License

[MIT][license]
