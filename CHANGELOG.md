# Changelog

## [0.8.4] - 2024-07-27


### features

- Install dependencies before git init

- Add next steps to the home page

- switch from kysely-codegen to prisma-kysely

- Tailwind is no longer optional

- Add support for Svelte 5 and Cloudflare D1

- Use sveltekit emulation for D1 support

- Add Auth option using Lucia

- Don't default install dependencies if using npm

- add auth-protected trpc middleware

- sort package.json keys

- Insert app name in app.html and wrangler.toml

- Update to eslint v9

- Bring template to parity with the official svelte template

- Use svelte 5 syntax in svelte 5 template

- Don't default create a new git repo if inside one

- Automatically run svelte-kit sync

- Add Turso support

- add compatibility_date to wrangler.toml

- Initialize Sidecar worker template (additional Cloudflare worker with a websocket server)

- Enable/disable telemetry

- Add "cookies" for storing config on disk

- Create telemetry server

- Optionally report telemetry

- Use wrangler typegen

- Github action to deploy sidecar worker

- Improve build workflow




### fixes

- add readme

- install binary-install dependency for npm package

- compress rust binaries

- Update readme

- switch from gnu to musl on Linux

- Add a leading newline for pnpm

- Print the correct package manager for next steps if the user didn't install dependencies

- Use dunce to fix UNC paths on windows

- Update kysely link in readme

- remove extra whitespace on home page

- revert to rust nightly 1.71.0

- disable local SQLite on edge

- Silence initial git commit message

- Fix auth types

- remove printlns

- change getMe to public TRPC procedure that returns nullable

- Fix sveltekit redirects inside try blocks

- user -> username

- format mjs files too

- improve error handling for d1

- use typescript-eslint beta

- Install wrangler on all edge templates

- Update app.d.ts files to match Svelte's offical template

- Fix no-unused-vars lint rule

- Fix regression in D1 migration script




### refactor

- Set default features in the template config




### docs

- Add changelog link to readme




### performance

- remove dependency on binary-install

- remove axios dependency

- Use a smaller HTTP client to optimize binary size




### internal

- Allow option features to be conditionally hidden




### misc

- update packages, including trpc-svelte-query

- Update dependencies

- Update dependencies

- Update dependencies

- Update dependencies

- Update dependencies

- Fix formatting

- clean up unused imports

- Update dependencies

- Update npm installer dependencies

- Update dependencies

- Update dependencies

- Update dependencies

- Update Rust dependencies, improve e2e tests

- clean up gitignore

- Update dependencies

- remove unused imports

- fix prettier formatting

- clean up lucia boilerplate

- fix formatting

- Update Rust dependencies

- Update rust dependencies

- Update readme

- Fix clippy suggestions

- Update workers compatibility_date to 2024-07-01

- Fix clippy issues




<br/>

**Dependency Updates:** [1,](https://github.com/ottomated/create-o7-app/commit/545755ba7ecc4abf48e640c21824877f253b3806) [2,](https://github.com/ottomated/create-o7-app/commit/984deb43626f0abae1dbf2ff4c880330ced13b68) [3,](https://github.com/ottomated/create-o7-app/commit/c62deb7691a71ea244b24b6708f354c982500c26) [4,](https://github.com/ottomated/create-o7-app/commit/b59f3140ed4640ac892519ca8792cdf3810bfcdb) [5,](https://github.com/ottomated/create-o7-app/commit/4cda1b3ef4f8791fdc4ea723daecd85be1b067c5) [6,](https://github.com/ottomated/create-o7-app/commit/be05ef01c605bd7d39291310c9451a83aa8cd2f8) [7,](https://github.com/ottomated/create-o7-app/commit/c2102c9a8bebf5f34779119f38d07fc1c7205f39) [8,](https://github.com/ottomated/create-o7-app/commit/8e4a2f59224390d4c9c64bb30ebb386ba7bda3f3) [9,](https://github.com/ottomated/create-o7-app/commit/39b941618886b545c44876009ae9a9ec9ce57887) [10,](https://github.com/ottomated/create-o7-app/commit/78f3a01f3e1023d9638690f154c0e27ec91a86f3) [11,](https://github.com/ottomated/create-o7-app/commit/a1aeaa56ad47891497cb7fe2ab8e45129a56e214) [12,](https://github.com/ottomated/create-o7-app/commit/c4466cc2ae3029cd85c8e8369507e030b34bf57b) [13,](https://github.com/ottomated/create-o7-app/commit/ee2c4c1d0c25062d187cdc6177a747442c46ee98) [14,](https://github.com/ottomated/create-o7-app/commit/e4158fe88cdfc87826818febbbee6b2b17723509) [15,](https://github.com/ottomated/create-o7-app/commit/bcf09f7ffc7fc01887a65b6c25e916e1b4dfcf64) [16,](https://github.com/ottomated/create-o7-app/commit/bd53bb47786635ad9a78b23fb24368ab4c4c0ff9) [17,](https://github.com/ottomated/create-o7-app/commit/f50065c241773ca79936c1f5d966f4c3b499ac53) [18,](https://github.com/ottomated/create-o7-app/commit/6e9ebeaa90f44480443d226577f9cab3b6d20302) [19,](https://github.com/ottomated/create-o7-app/commit/5d864e49ab5765aa361b118a7e20898bf6db828b) [20,](https://github.com/ottomated/create-o7-app/commit/6a96fde1733de14474ffbed550d9032af1a67458) [21,](https://github.com/ottomated/create-o7-app/commit/1ba821925cd2d683305ff2f718295617fc9cdf24) [22,](https://github.com/ottomated/create-o7-app/commit/ca7ed446f7e0c3be4d4d7c63850896558b7ae171) [23,](https://github.com/ottomated/create-o7-app/commit/b2cbc351ef325466453d18fed59aa7815df4bf9a) [24,](https://github.com/ottomated/create-o7-app/commit/06c7f2989b220a16cf59f5e8586571d555c9caaa) [25,](https://github.com/ottomated/create-o7-app/commit/32d2de271828a41c11c9a996c3c5bc9829579ce1) [26,](https://github.com/ottomated/create-o7-app/commit/57e0beb6cef009c6db3624fd9c39f6ebf73ca131) [27,](https://github.com/ottomated/create-o7-app/commit/5c887c889a6cd954f2d801904ab76c3b95a0c861) [28,](https://github.com/ottomated/create-o7-app/commit/5a442e6554797ea399f17be930b05d6e1fa03b94) [29,](https://github.com/ottomated/create-o7-app/commit/a83e6a5a98c2ad057e310f00a78c1cf21fede426) [30,](https://github.com/ottomated/create-o7-app/commit/42fba8d8007258eb7c58c539b3039b0a7e654515) [31,](https://github.com/ottomated/create-o7-app/commit/2b01de049088ed23fab31f1eb387667bbd98af02) [32,](https://github.com/ottomated/create-o7-app/commit/01cd216f054b4a950b2982c708aba6c077f5946d) [33,](https://github.com/ottomated/create-o7-app/commit/b1c200be388be8fa18be8870f872e890e6e4149a) [34,](https://github.com/ottomated/create-o7-app/commit/26446e7bf19e4a2b5b50ae22f695329d57760802) [35,](https://github.com/ottomated/create-o7-app/commit/522c3f6607cfc057ca3f51382f31b350fbd91748) [36,](https://github.com/ottomated/create-o7-app/commit/e43de3b0bbd1b66e6a47523680c340b90954f00d) [37,](https://github.com/ottomated/create-o7-app/commit/d3714687566ae66dd8fdb65c676dbdf25b888b83) [38,](https://github.com/ottomated/create-o7-app/commit/63d8c3d64893f73f1070900c17a64b57b4a1bfc1) [39,](https://github.com/ottomated/create-o7-app/commit/d7104ab5bd35299ef55fc018a1e2eab7efa6f87b) [40,](https://github.com/ottomated/create-o7-app/commit/40620250e7a56d4eccb186744f624bc906fb3917) [41,](https://github.com/ottomated/create-o7-app/commit/7c8152a217607289de4eaa846dd335d16265e899) [42,](https://github.com/ottomated/create-o7-app/commit/8ecd4f13903a0c5ac308ecbb6b81b31b251d4692) [43,](https://github.com/ottomated/create-o7-app/commit/15b3e358a7a8aa47de695a670057d6734728b519) [44,](https://github.com/ottomated/create-o7-app/commit/0200c10052e9122d15a0b3a2323c05d458a02921) [45,](https://github.com/ottomated/create-o7-app/commit/69f05c9136e4ce207d0b822fb02a3f8b6a70e5c3) [46,](https://github.com/ottomated/create-o7-app/commit/2599ac0ccc17280208645f85fec93fe9636c71bd) [47,](https://github.com/ottomated/create-o7-app/commit/fd401b287f071a175027537e0f1093384405b4d6) [48,](https://github.com/ottomated/create-o7-app/commit/68ddf43eadb583bbae250613d59924dd4d66b819) [49,](https://github.com/ottomated/create-o7-app/commit/c7d1b6ec5b7d1a467e68aa449d5ee58646610629) [50,](https://github.com/ottomated/create-o7-app/commit/b3c333943dda2fa7a85bba3c370ace5908fcd9e9) [51,](https://github.com/ottomated/create-o7-app/commit/53d0536ec95d4acb6d307b91e7b557d7b647d537) [52,](https://github.com/ottomated/create-o7-app/commit/6ed780938e2d93eab2d991340641364be1446121) [53,](https://github.com/ottomated/create-o7-app/commit/33cdf06fb5a1164435b81ee55082a30448cc3810) [54,](https://github.com/ottomated/create-o7-app/commit/a1271cb6ecfe9f2e9a89b25b13f5cd0dbd189120) [55,](https://github.com/ottomated/create-o7-app/commit/180aadbccb5040122b796a19ba40f01d5e1974b2) [56](https://github.com/ottomated/create-o7-app/commit/e89ee9d84aa4adcf9e3d50bc18b54125f00048f1)



### See the [full changelog](https://github.com/ottomated/create-o7-app/blob/main/CHANGELOG.md)

<!-- generated by git-cliff -->
