# CHANGELOG


## v0.1.0 (2025-11-21)

### Bug Fixes

- Add cohere embeddings ([#26](https://github.com/TheTechOddBug/shraga/pull/26),
  [`cba6733`](https://github.com/TheTechOddBug/shraga/commit/cba6733608fdb285acc48ff6098c7ede98d96e15))

Co-authored-by: Dinor Nagar <dinornagar@Dinors-MacBook-Air.local>

- Add extra param to request ([#33](https://github.com/TheTechOddBug/shraga/pull/33),
  [`17956d5`](https://github.com/TheTechOddBug/shraga/commit/17956d51288d9e2bbf01a3256379d5762d625adc))

Co-authored-by: Dinor Nagar <dinornagar@Dinors-MacBook-Air.local>

- Add missing retriever config
  ([`2584b50`](https://github.com/TheTechOddBug/shraga/commit/2584b50f054e274e3699d855209ed40d1d8b1535))

- Add msg_id to user and system chat messages
  ([#27](https://github.com/TheTechOddBug/shraga/pull/27),
  [`8adb57c`](https://github.com/TheTechOddBug/shraga/commit/8adb57c68f5b022984d598b6a89720ab3ec8d342))

* chore: add uuid to user and system chat messages

* fix: msg_id

* chore: feedback

* perf: optimize chat history loading (#28)

* msg_id

---------

Co-authored-by: Liza Katz <lizka.k@gmail.com>

- Add nova support ([#24](https://github.com/TheTechOddBug/shraga/pull/24),
  [`31a9345`](https://github.com/TheTechOddBug/shraga/commit/31a9345a2ed229f5f2f81721e42866f05e5c9953))

* feat: Add nova support

* feat: remove duplicates

---------

Co-authored-by: Dinor Nagar <dinornagar@Dinors-MacBook-Air.local>

- Allow create user with cmd args ([#36](https://github.com/TheTechOddBug/shraga/pull/36),
  [`2154719`](https://github.com/TheTechOddBug/shraga/commit/21547196b082a06d001846ba2728894c6f7aa6ac))

- Auth security improvements ([#34](https://github.com/TheTechOddBug/shraga/pull/34),
  [`a57d2f3`](https://github.com/TheTechOddBug/shraga/commit/a57d2f3eb0f065cfb916cfa470f7a8f3b4337ad5))

* fix: - store password hashes - create basic auth user - improve basic auth backend (still supports
  raw password for backwards compatibility)

* chore: use ordered dicts

- Build
  ([`382d31a`](https://github.com/TheTechOddBug/shraga/commit/382d31a052dd1dfc2094b7b16b6de434a718b706))

- Build
  ([`94d4f08`](https://github.com/TheTechOddBug/shraga/commit/94d4f08a03f7f66dfabf9da541151c3825998317))

- Bump
  ([`c5d801a`](https://github.com/TheTechOddBug/shraga/commit/c5d801a3eaedfe62e61c39ee4ad45a2d77023bd8))

- Bump
  ([`27b9259`](https://github.com/TheTechOddBug/shraga/commit/27b9259dbcb4381c2c4a8c5908c988031e5b282c))

- Bump
  ([`d5b0672`](https://github.com/TheTechOddBug/shraga/commit/d5b06729667b5081a0e1492c9b78a27c39d06aca))

- Bump
  ([`80af422`](https://github.com/TheTechOddBug/shraga/commit/80af422dba09d27d0ffa98f243283a0b996563db))

- Bump ([#54](https://github.com/TheTechOddBug/shraga/pull/54),
  [`435b3b7`](https://github.com/TheTechOddBug/shraga/commit/435b3b7c5e95b028b60d466980717cb7c63bd45d))

- Convert function to static ([#49](https://github.com/TheTechOddBug/shraga/pull/49),
  [`1aa869d`](https://github.com/TheTechOddBug/shraga/commit/1aa869d11e63ef7ccc2f28892727d519764e9511))

Co-authored-by: Dinor Nagar <dinornagar@Dinors-MacBook-Air.local>

- Define chat_id in run flow
  ([`98653e2`](https://github.com/TheTechOddBug/shraga/commit/98653e267b5971d1033aee49cbd98c41f91a3c21))

- Don't upload to gh release if not released
  ([`e06f7e7`](https://github.com/TheTechOddBug/shraga/commit/e06f7e7ddd6f76e8dad3b55967dc68521bb81674))

- Dont use sonnet_3
  ([`be0dabc`](https://github.com/TheTechOddBug/shraga/commit/be0dabc99dc0b3e34642920738972093545abeb9))

- Expose create user script, improve readme ([#35](https://github.com/TheTechOddBug/shraga/pull/35),
  [`784f178`](https://github.com/TheTechOddBug/shraga/commit/784f17837ecf5e80b4a1cf32b5b0af7f3b8cf6b9))

- Fix chat logging ([#25](https://github.com/TheTechOddBug/shraga/pull/25),
  [`b6ea2ab`](https://github.com/TheTechOddBug/shraga/commit/b6ea2ab6958b770cb2368a01b64dad7bd92d3c17))

* fix: enable logging for chat messages without stats

* fix: handle empty stats

---------

Co-authored-by: Dinor Nagar <dinornagar@Dinors-MacBook-Air.local>

- Get_chat_messages count param
  ([`a6eca56`](https://github.com/TheTechOddBug/shraga/commit/a6eca56fcaf2a83812743c31b3cb0c8d20de8074))

- Git history disabled by default
  ([`5cf46c6`](https://github.com/TheTechOddBug/shraga/commit/5cf46c626676a80aa10bf9bdca65d3af9297a049))

- History
  ([`198de66`](https://github.com/TheTechOddBug/shraga/commit/198de660748a3fb42ade7b27cf43a5cd463e19ab))

- Improve readme, cleanup history service
  ([`5baebcb`](https://github.com/TheTechOddBug/shraga/commit/5baebcbc115e659cce5881f1af5d5a46279b03c2))

- Install poetry
  ([`da18535`](https://github.com/TheTechOddBug/shraga/commit/da18535cfce44e86a1fa003d80a5bfcd48c1e23f))

- Jwt metadata
  ([`d14dbb8`](https://github.com/TheTechOddBug/shraga/commit/d14dbb83cf4f4dff5123e3963e877bfd25a48fa8))

- Lock
  ([`3b83b71`](https://github.com/TheTechOddBug/shraga/commit/3b83b714e4fb537ae8c8e80a4fcca37838f489e9))

- Make index optional in os \ es connection
  ([`081294d`](https://github.com/TheTechOddBug/shraga/commit/081294d96e09abff42ce43164c8d7571b88002dc))

- Remove use_ssl
  ([`9ccdf66`](https://github.com/TheTechOddBug/shraga/commit/9ccdf6639e6a24af9ffc9f6d2549a957b1a5b0c5))

- Remove error log if user canceled a request
  ([#43](https://github.com/TheTechOddBug/shraga/pull/43),
  [`fdf7157`](https://github.com/TheTechOddBug/shraga/commit/fdf7157c6dd3c7ab6268dfd24a2b8e3054ece968))

- Resolve circular imports ([#30](https://github.com/TheTechOddBug/shraga/pull/30),
  [`1fe6e69`](https://github.com/TheTechOddBug/shraga/commit/1fe6e6984061be03c3f108b650b1f350decc1a7c))

- Restore semantic release config
  ([`fb3cb9d`](https://github.com/TheTechOddBug/shraga/commit/fb3cb9db623ebd12f7e3cf9061d2f934b97a90c2))

- Retrieveconfig in pydantic
  ([`34c20e7`](https://github.com/TheTechOddBug/shraga/commit/34c20e76e3f62951c1182d9222ed1f93d7291c04))

- Retriever config
  ([`0c34083`](https://github.com/TheTechOddBug/shraga/commit/0c34083d62932ec31b36877242de33331b987271))

- Retrieverconfig
  ([`af07d2f`](https://github.com/TheTechOddBug/shraga/commit/af07d2fcf96948b7ecb80cac0dc7e183bf8dd6f6))

- Return empty array of messages instead of code 404
  ([#29](https://github.com/TheTechOddBug/shraga/pull/29),
  [`2691823`](https://github.com/TheTechOddBug/shraga/commit/269182348e211323b27f7d5e47bc56ab10866db9))

- Support report filters ([#51](https://github.com/TheTechOddBug/shraga/pull/51),
  [`93847c0`](https://github.com/TheTechOddBug/shraga/commit/93847c0891393f92e0d47b2b57f2ea5f108e716e))

- Test
  ([`4aca46d`](https://github.com/TheTechOddBug/shraga/commit/4aca46dcbe17a9f8848e25a16a350f733a7daf3e))

- Test
  ([`1e7267b`](https://github.com/TheTechOddBug/shraga/commit/1e7267bd2d1f1ecdd9f3629e35dc1f2909a124de))

- Typo
  ([`668c53d`](https://github.com/TheTechOddBug/shraga/commit/668c53d93b607ef95ddb2640146c519b82ea5179))

- Use ssl by default!
  ([`4a80aba`](https://github.com/TheTechOddBug/shraga/commit/4a80aba637a8acd0d5d9d71322d338e4c3ae4b0d))

### Chores

- Add auth unit tests
  ([`44ba8f2`](https://github.com/TheTechOddBug/shraga/commit/44ba8f2bfa232772a1a6601244444923602cd9f6))

- Add eval metric ([#42](https://github.com/TheTechOddBug/shraga/pull/42),
  [`ce7a7bd`](https://github.com/TheTechOddBug/shraga/commit/ce7a7bd954a4d89747da02997b60701f004196bc))

Co-authored-by: Dinor Nagar <dinornagar@Dinors-MacBook-Air.local>

- Add gh release workflow
  ([`a2b9d2a`](https://github.com/TheTechOddBug/shraga/commit/a2b9d2a68552b910db95a409ba837c5d3f5e561c))

- Add region call and update fallback model
  ([`d0962da`](https://github.com/TheTechOddBug/shraga/commit/d0962da283145aacc11af6e857922e0135a2cd06))

- Bump
  ([`c785d32`](https://github.com/TheTechOddBug/shraga/commit/c785d321a00429bf773c5342eac88801c32b3868))

- Bump
  ([`a8e4a64`](https://github.com/TheTechOddBug/shraga/commit/a8e4a646aaacf0982a0739230b94541002d1e9bc))

- Bump
  ([`3e12757`](https://github.com/TheTechOddBug/shraga/commit/3e12757fd4e57b4061fcf94444f62ecfdaf7b961))

- Bump
  ([`ad526e1`](https://github.com/TheTechOddBug/shraga/commit/ad526e16f576ad2c303e99a414fe0bd851990d34))

- Cleanup
  ([`4c8957b`](https://github.com/TheTechOddBug/shraga/commit/4c8957b02621aa91a9e6ea81353a0e28eeb89d5c))

- Cleanup!
  ([`e45dafd`](https://github.com/TheTechOddBug/shraga/commit/e45dafd44094f3cd39c7af4138bd12090966e461))

- Cohere embed import
  ([`2429e23`](https://github.com/TheTechOddBug/shraga/commit/2429e23900798ace9038a25dd210e897a080fd01))

- Don't build if already published
  ([`4c7d14d`](https://github.com/TheTechOddBug/shraga/commit/4c7d14d698887354ae2ac6335e474056fe7e6da7))

- Fix docs
  ([`cd56d9c`](https://github.com/TheTechOddBug/shraga/commit/cd56d9c9f5d19700fc12e8f98fe85852466f7131))

- Ignore
  ([`7e9a507`](https://github.com/TheTechOddBug/shraga/commit/7e9a507089ad594279f1b7c6bdd19e33aa7f6f62))

- Log execution plan
  ([`5e502e5`](https://github.com/TheTechOddBug/shraga/commit/5e502e50eefd2f282945f68326b8d5352f743ca1))

- Pre commit hook message linter
  ([`7aa0a93`](https://github.com/TheTechOddBug/shraga/commit/7aa0a939a359b30b0825848bc6a42047b7232409))

- Read index name from config ([#47](https://github.com/TheTechOddBug/shraga/pull/47),
  [`aadd507`](https://github.com/TheTechOddBug/shraga/commit/aadd507f39e46b71118117daad866ddfc002ec86))

Co-authored-by: Dinor Nagar <dinornagar@Dinors-MacBook-Air.local>

- Release action
  ([`1e7585f`](https://github.com/TheTechOddBug/shraga/commit/1e7585f0c347fa751c22b4b8260c0fdd0cc42289))

- Split out auth providers
  ([`5f0d376`](https://github.com/TheTechOddBug/shraga/commit/5f0d376ee7fae29ed30d964c862a80201ed0f94d))

- Update MAP metric
  ([`ac725c0`](https://github.com/TheTechOddBug/shraga/commit/ac725c07353d989ed1e9b02d7a695df2c4a3a835))

- Use different model in fallback
  ([`0a4cd16`](https://github.com/TheTechOddBug/shraga/commit/0a4cd166f3a0be91a2e762a0744fbe9150ecf671))

### Features

- Add history enable field to config for FE ([#31](https://github.com/TheTechOddBug/shraga/pull/31),
  [`657f8bd`](https://github.com/TheTechOddBug/shraga/commit/657f8bda20002ab7758d5a6a0577523c862f23e5))

- Add retry on invoke error ([#48](https://github.com/TheTechOddBug/shraga/pull/48),
  [`0960629`](https://github.com/TheTechOddBug/shraga/commit/0960629b846d95ef960618d13f57b77833ec4db9))

* feat: add retry on invoke error

* chore: encapsulate logic to bedrock service

* chore: add tests

---------

Co-authored-by: Dinor Nagar <dinornagar@Dinors-MacBook-Air.local>

Co-authored-by: Liza Katz <lizka.k@gmail.com>

- Add user org in chat history ([#38](https://github.com/TheTechOddBug/shraga/pull/38),
  [`5077924`](https://github.com/TheTechOddBug/shraga/commit/50779244e1fcb266d3bc7808e1c7fc2a92e6de2c))

* feat: add user org in chat history

* fix: code refinements

* chore: update a bunch of tests + resolve circular imports

---------

Co-authored-by: Liza Katz <lizka.k@gmail.com>

- Get auth lifetime from config ([#37](https://github.com/TheTechOddBug/shraga/pull/37),
  [`4a5171a`](https://github.com/TheTechOddBug/shraga/commit/4a5171acc2d11bb41f28053beb95b13c71600353))

* feat: get auth lifetime from config

* fix: code refinements

* fix: change auth lifetime param name

- Release script
  ([`62bbc2c`](https://github.com/TheTechOddBug/shraga/commit/62bbc2c97150889dbdeaa60941454a037008c884))

- Replace chat history endpoint for Analytics with chat dialogs endpoint
  ([#39](https://github.com/TheTechOddBug/shraga/pull/39),
  [`8b9c77d`](https://github.com/TheTechOddBug/shraga/commit/8b9c77d6528b568cef207e5d07180303fe3c752f))

* feat: replace chat history endpoint for Analytics with chat dialogs endpoint

* fix: move get_chat_dialogs to analytics service

- Report service and export report endpoint ([#40](https://github.com/TheTechOddBug/shraga/pull/40),
  [`c8fe5f7`](https://github.com/TheTechOddBug/shraga/commit/c8fe5f7e763a456526aa2d4a3fb53a554170a12a))

* feat: report service and export report endpoint

* chore: readme update

* feat: replace get with post, return status 403 if user without permission

- Save chat preferences in chat history ([#44](https://github.com/TheTechOddBug/shraga/pull/44),
  [`1dca657`](https://github.com/TheTechOddBug/shraga/commit/1dca657ce742da94e1a1218a351eafc90c5f183a))

* feat: save chat preferences in chat history

* chore: ui.default_flow and ui.list_flows validation before starting the app

* shraga config tests

---------

Co-authored-by: Liza Katz <lizka.k@gmail.com>

### Performance Improvements

- Optimize chat history loading ([#28](https://github.com/TheTechOddBug/shraga/pull/28),
  [`1926ca7`](https://github.com/TheTechOddBug/shraga/commit/1926ca7ec9db798139e01712ed77f46dd26fb15f))
