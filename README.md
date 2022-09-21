# Welcome to ig.news 👋

### RocketSeat :fire: Ignite ReactJS 

<p align="center">
  <img alt="ignews" width="200px" src="https://user-images.githubusercontent.com/57726726/191607785-08feb71d-ab97-423c-ab32-ee1f421f1e03.svg"/>
</p>

A subscription content platform for React developers.

> The blog has a monthly subscription system integrated with the Stripe payment platform. After making payment, the user will be able to see the full blog content, if he is not a subscriber he will only be able to see a preview of the content.

![preview](https://user-images.githubusercontent.com/57726726/191609578-5e114a60-3595-4314-9a6a-a73f7c77998d.png)

## Technologies

- [NextJS](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [FaunaDB](https://fauna.com/)
- [Stripe](https://stripe.com/br)
- [Prismic CMS](https://prismic.io/)
- [Sass](https://sass-lang.com/)

## Installation

Use the package manager [yarn](https://yarnpkg.com/) to install or NPM.

```bash
$ yarn
```

```
cp .env.local.example .env.local
```

## Usage

```bash
yarn dev
```
Visit localhost:3000 in your browser

#### Run stripe to listen for webhook events
```
stripe listen --forward-to localhost:3000/api/webhooks
```

## Checkout tests

- Successful payment: 4242 4242 4242 4242
- Payment failure: 4000 0000 0000 9995
- Need authentication: 4000 0025 0000 3155

## Author

:technologist: **Luiz Moura**

* Github: [@luiz-moura](https://github.com/luiz-moura)
* LinkedIn: [@luiz-moura](https://linkedin.com/in/luiz-moura)

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2022 [Luiz Moura](https://github.com/luiz-moura).

This project is [MIT License](https://opensource.org/licenses/MIT) licensed.
