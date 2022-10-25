## Publish
1. Login
```bash
pnpm login --scope @viettelco-public --registry=http://npm.pkg.github.com
#> Username: USERNAME
#> Password: TOKEN
#> Email: PUBLIC-EMAIL-ADDRESS
#
```
2. Change package nname to `@viettelco-public/swiper`
3. `@viettelco-public:registry=https://npm.pkg.github.com` >> .npmrc

## Install
1.  `@viettelco-public:registry=https://npm.pkg.github.com` >> .npmrc
2. pnpm install `@viettelco-public/swiper@0.0.0`
