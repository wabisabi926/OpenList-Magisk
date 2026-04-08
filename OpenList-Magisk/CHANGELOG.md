### &nbsp;&nbsp;&nbsp;🚨 Breaking Changes

- **ci**:
  - Update issue CI configuration [skip ci] &nbsp;-&nbsp; by @jyxjjj in https://github.com/OpenListTeam/OpenList/issues/2166 [<samp>(b5626)</samp>](https://github.com/OpenListTeam/OpenList/commit/b5626b27)
- **db**:
  - Replace SQLite Driver with glebarez/sqlite to avoid CGO &nbsp;-&nbsp; by @PIKACHUIM in https://github.com/OpenListTeam/OpenList/issues/2211 [<samp>(d598e)</samp>](https://github.com/OpenListTeam/OpenList/commit/d598ef75)
  - Replace SQLite Driver with glebarez/sqlite to avoid CGO &nbsp;-&nbsp; by @jyxjjj in https://github.com/OpenListTeam/OpenList/issues/2269 [<samp>(29447)</samp>](https://github.com/OpenListTeam/OpenList/commit/29447a41)
  - Migrate SQLite to pure-go and add mips compatibility switch &nbsp;-&nbsp; by @Suyunmeng in https://github.com/OpenListTeam/OpenList/pull/2296 [<samp>(7bea2)</samp>](https://github.com/OpenListTeam/OpenList/commit/7bea29c1)

### &nbsp;&nbsp;&nbsp;🚀 Features

- **drivers**: Add doubao_new driver &nbsp;-&nbsp; by @Elegant1E in https://github.com/OpenListTeam/OpenList/issues/2114 [<samp>(e41b6)</samp>](https://github.com/OpenListTeam/OpenList/commit/e41b683e)
- **drivers/123_open**: Support 123 official app api &nbsp;-&nbsp; by @PIKACHUIM in https://github.com/OpenListTeam/OpenList/issues/2293 [<samp>(9fdba)</samp>](https://github.com/OpenListTeam/OpenList/commit/9fdba3a7)
- **drivers/123open**: Support sha1 reuse api &nbsp;-&nbsp; by @gdm257 in https://github.com/OpenListTeam/OpenList/issues/2089 [<samp>(a121f)</samp>](https://github.com/OpenListTeam/OpenList/commit/a121f861)
- **drivers/thunder***: Implement GetDetails &nbsp;-&nbsp; by @xrgzs in https://github.com/OpenListTeam/OpenList/issues/2113 [<samp>(795a1)</samp>](https://github.com/OpenListTeam/OpenList/commit/795a18b5)
- **permissions**: Implement fine-grained permission control &nbsp;-&nbsp; by @Lanfei and **Claude Sonnet 4.5** in https://github.com/OpenListTeam/OpenList/issues/2145 [<samp>(d85f0)</samp>](https://github.com/OpenListTeam/OpenList/commit/d85f084a)
- **security**: Add SECURITY.md &nbsp;-&nbsp; by @xrgzs in https://github.com/OpenListTeam/OpenList/issues/2147 [<samp>(db0e2)</samp>](https://github.com/OpenListTeam/OpenList/commit/db0e2ec1)

### &nbsp;&nbsp;&nbsp;🐞 Bug Fixes

- **115_share**: Adjust 115 share driver for official API update &nbsp;-&nbsp; by @SheltonZhu in https://github.com/OpenListTeam/OpenList/issues/2068 [<samp>(5d9fc)</samp>](https://github.com/OpenListTeam/OpenList/commit/5d9fc835)
- **azure**: Remove properties and fix prefix &nbsp;-&nbsp; by @bzssm in https://github.com/OpenListTeam/OpenList/issues/2209 [<samp>(5eaef)</samp>](https://github.com/OpenListTeam/OpenList/commit/5eaef960)
- **deps**: Update go4.org digest to a507140 &nbsp;-&nbsp; in https://github.com/OpenListTeam/OpenList/issues/2095 [<samp>(8431c)</samp>](https://github.com/OpenListTeam/OpenList/commit/8431c1b1)
- **driver/wps**: Fetch all files via multiple API invocations &nbsp;-&nbsp; by @mkitsdts in https://github.com/OpenListTeam/OpenList/issues/2139 [<samp>(e0ee7)</samp>](https://github.com/OpenListTeam/OpenList/commit/e0ee7370)
- **drivers/cloudreve_v4**: Remove token check for share &nbsp;-&nbsp; by @xrgzs in https://github.com/OpenListTeam/OpenList/issues/2274 [<samp>(e11b8)</samp>](https://github.com/OpenListTeam/OpenList/commit/e11b8a82)
- **drivers/openlist**: Pass through frontend refresh flag &nbsp;-&nbsp; by @sevxn007 in https://github.com/OpenListTeam/OpenList/issues/2307 [<samp>(9e49a)</samp>](https://github.com/OpenListTeam/OpenList/commit/9e49adc3)
- **drivers/teldrive**: Enhance file listing and upload functionality with pagination and random chunk naming &nbsp;-&nbsp; by @totza2010 and **Copilot** in https://github.com/OpenListTeam/OpenList/issues/2034 [<samp>(f5421)</samp>](https://github.com/OpenListTeam/OpenList/commit/f5421876)
- **net**: Honor proxy settings when uploading to 115/115 Open/PikPak OSS &nbsp;-&nbsp; by @Copilot and **jyxjjj** in https://github.com/OpenListTeam/OpenList/issues/2222 [<samp>(f3428)</samp>](https://github.com/OpenListTeam/OpenList/commit/f3428e65)
- **offline_download**: Prevent infinite retry on status update failure &nbsp;-&nbsp; by @sdvcrx in https://github.com/OpenListTeam/OpenList/issues/2294 [<samp>(12c9b)</samp>](https://github.com/OpenListTeam/OpenList/commit/12c9bdbd)
- **server**: Add missing return after error responses &nbsp;-&nbsp; by @Lanfei in https://github.com/OpenListTeam/OpenList/issues/2150 [<samp>(9a2ba)</samp>](https://github.com/OpenListTeam/OpenList/commit/9a2ba1da)

##### &nbsp;&nbsp;&nbsp;&nbsp;[View changes on GitHub](https://github.com/OpenListTeam/OpenList/compare/v4.1.10...v4.2.0)
