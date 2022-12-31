# gatsby-plugin-squadwe
![Package](https://github.com/squadwe/gatsby-plugin-squadwe/workflows/Package/badge.svg?branch=master)
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

Quickly add the [Squadwe](https://www.squadwe.com/) live chat widget to your Gatsby site.

## Install

`npm install --save gatsby-plugin-squadwe`
or
`yarn add gatsby-plugin-squadwe`

## How to use

```javascript
// In your gatsby-config.js
plugins: [
    {
        resolve: `gatsby-plugin-squadwe`,
        options: {
            baseUrl: 'BASE_URL', // Required
            websiteToken: 'WEBSITE_TOKEN', // Required
            includeInDevelopment: false, // Optional
            squadweSettings: {} // Optional
        },
    },
];
```

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):


This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
