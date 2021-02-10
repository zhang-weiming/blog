---
layout: post
title:  "Solutions of error"
date:   2021-01-31 22:22:09 +0800
categories: app
---
In these days, I was learning vue & electron. So when I meet the error, I will record my searching result of the solutions. Hope this is helpful to you!

## my project composition

- @vue/cli (cli@v4.x, Vue@2.x)
- vue-cli-electron-builder

## solutions

### App/Tray Icon is not getting loaded

See [Github issues](https://github.com/nklayman/vue-cli-plugin-electron-builder/issues/49).

### typescript can't use __static variable

See [Github issues](https://github.com/electron-userland/electron-webpack/issues/172).

### vue-cli-plugin-electron-builder open child component in a new window

See [Stackoverflow](https://stackoverflow.com/questions/59546249/vue-cli-plugin-electron-builder-open-child-component-in-a-new-window) and [`Noah Klayman`'s example](https://github.com/nklayman/electron-multipage-example).
