<p align="center">
  <a href="http://nestjs.com/" target="blank">
    <img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" />
  </a>
</p>

<p align="center">
  A mailer module for Nest framework (node.js) using <a href="https://nodemailer.com/">Nodemailer</a> library,
  this was created from a fork of an existing package but was not updated, <a href="https://www.npmjs.com/package/@nestjs-modules/mailer">LINK</a>,
  the main contributor here is the github user AnhNg6262 who made these fixes <a href="https://github.com/nest-modules/mailer/pull/1242"> GIT PULL </a>,
  i did not know i he made a package already, but i did for my project. It should work haha, all my test did pass.

  Do not use in production
</p>

<p align="center">
  <a href="https://www.npmjs.com/org/nestjs-modules"><img src="https://img.shields.io/npm/v/@nestjs-modules/mailer.svg" alt="NPM Version" /></a>
  <a href="https://www.npmjs.com/org/nestjs-modules"><img src="https://img.shields.io/npm/l/@nestjs-modules/mailer.svg" alt="Package License" /></a>
  <a href="https://www.npmjs.com/org/nestjs-modules"><img src="https://img.shields.io/npm/dm/@nestjs-modules/mailer.svg" alt="NPM Downloads" /></a>
  <a href="https://opencollective.com/nest-modules#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
</p>

### Installation

```sh
npm install --save @nestjs-modules/mailer nodemailer
npm install --save-dev @types/nodemailer
#or
yarn add @nestjs-modules/mailer nodemailer
yarn add -D @types/nodemailer
```

**Hint:** handlebars and pug is an optional dependency, if you want to use the template, you must install it.

#### with npm
```sh
npm install --save handlebars
#or
npm install --save pug
#or
npm install --save ejs
#or
npm install --save mjml
```

#### with yarn
```sh
yarn add handlebars
#or
yarn add pug
#or
yarn add ejs
#or
yarn add mjml
```

### Documentation

you can find all the documentation [here](https://nest-modules.github.io/mailer/) for the email module

### Starter kit

- [Sending email-template with outlook](https://github.com/yanarp/nestjs-mailer) - Starter kit, nestjs mailer implementation on outlook smtp with email-template

### Contributing

* [Cristiam Diaz](https://github.com/cdiaz)
* [Eduardo Leal](https://github.com/eduardoleal)
* [Juan Echeverry](https://github.com/juandav)
* [Pat McGowan](https://github.com/p-mcgowan)
* [Paweł Partyka](https://github.com/partyka95)
* [Wasutan Kitijerapat](https://github.com/kitimark)
* [Alexandre Titeux](https://github.com/GFoniX)

### License

MIT
