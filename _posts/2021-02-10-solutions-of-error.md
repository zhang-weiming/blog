---
layout: post
title:  "vue-cli-electron-builder solutions of error"
date:   2021-02-10 14:31:09 +0800
categories: programming, vue, electron, front-end
---
In these days, I was learning vue & electron. So when I meet the error, I will record my searching result of the solutions. Hope this is helpful to you!

## my project composition

- @vue/cli (cli@v4.x, Vue@2.x)
- vue-cli-electron-builder

My project was created by following this [article](https://itnext.io/electron-application-with-vue-js-and-vuetify-f2a1f9c749b8).

And yarn is recommended than npm.

## solutions

### App/Tray Icon is not getting loaded

See [Github issues](https://github.com/nklayman/vue-cli-plugin-electron-builder/issues/49).

### typescript can't use __static variable

See [Github issues](https://github.com/electron-userland/electron-webpack/issues/172).

### vue-cli-plugin-electron-builder open child component in a new window

See [Stackoverflow](https://stackoverflow.com/questions/59546249/vue-cli-plugin-electron-builder-open-child-component-in-a-new-window) and [`Noah Klayman`'s example](https://github.com/nklayman/electron-multipage-example).
