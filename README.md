# README

## Instructions

### Prerequisites

Make sure you have Ruby and Node installed

```sh
➜ ruby -v
ruby 2.6.6p146 (2020-03-31 revision 67876) [x86_64-darwin19]

➜ node -v
v13.11.0
```

### Install gem

```sh
gem install bundler bridgetown -N
```

### Create new project

```sh
bridgetown new bridgetown_tailwind
cd bridgetown_tailwind
yarn start
```

You can now view your site live at http://localhost:4000/

### Tailwind

```sh
yarn add -D tailwindcss postcss-import postcss-loader
./node_modules/.bin/tailwind init
```

```
{
  test: /\.(s[ac]|c)ss$/,
  use: [
    {
      loader: "postcss-loader",
      options: {
        ident: "postcss",
        plugins: [
          require("postcss-import"),
          require("tailwindcss"),
          require("autoprefixer"),
        ],
      },
    },
  ],
},
```

```css
@import 'tailwindcss/base';
@import 'tailwindcss/components';
@import 'tailwindcss/utilities';
```

### Deployment with Netlify

1. Login to Netlify
2. Select `New Site from Git`
3. Choose your Git provider
4. Select your repo
5. Set your `Build Command` to `yarn deploy`
6. Set your `Publish directory` to `output/`
7. Click `Deploy site`

Your site will deploy and you should be able to view it at the preview link that Netlify provides!
