---
title: How to deploy GO HUGO to Firebase
date: "2020-07-01T22:12:03.284Z"
tags: ['hugo', 'firebase']
published: true
---

## Setting up Google Analitycs


```shell
npm install --save gatsby-plugin-google-analytics
```

Then open `gatsby-config.js` and edit inside the plugin the path gatsby-plugin-google-analytics resolver:

```shell
module.exports = {
  plugins: [
    {
      resolve: `gatsby-plugin-google-analytics`,
      options: {
        // replace "UA-XXXXXXXXX-X" with your own Tracking ID
        trackingId: "UA-XXXXXXXXX-X",
      },
    },
  ],
}
```