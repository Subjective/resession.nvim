# Changelog

## [1.1.0](https://github.com/stevearc/resession.nvim/compare/v1.0.0...v1.1.0) (2023-07-17)


### Features

* defer loading extensions until needed ([6ec6f20](https://github.com/stevearc/resession.nvim/commit/6ec6f20cf2cf3dc9c23a06deba36e1d2de9c75a4))

## 1.0.0 (2023-06-26)


### Features

* add a delete function ([71f45fd](https://github.com/stevearc/resession.nvim/commit/71f45fdbfb6f48defb95edcc9423b578c8090227))
* add fitting kind to vim.ui.select ([2cf9577](https://github.com/stevearc/resession.nvim/commit/2cf957753e28bf2b11e7d79322398240b1cc28bf))
* add hooks ([350abfc](https://github.com/stevearc/resession.nvim/commit/350abfcec2002cda3a7bf3d26c116a8cb83b5445))
* API for loading extensions after setup() ([1bf118f](https://github.com/stevearc/resession.nvim/commit/1bf118f77760311c3a6ef5fc9b2f189ea0ff3fe0))
* autosave in background ([9e6b70f](https://github.com/stevearc/resession.nvim/commit/9e6b70f7234b4cd32405bdecf1e8a5ce34842505))
* autosave will save session on exit ([4a7cbc3](https://github.com/stevearc/resession.nvim/commit/4a7cbc3f3ee4fef6c1568390758700f1d8537ba3))
* basic working API ([b1985da](https://github.com/stevearc/resession.nvim/commit/b1985da4f93424911739c8a77e1cdd3d5fd3fd1d))
* can set extension config to  to disable ([5218d25](https://github.com/stevearc/resession.nvim/commit/5218d250be2c97e1b5cd1bd06c9a4d2d98b82809))
* can specify session dir in API calls ([0ad0ec7](https://github.com/stevearc/resession.nvim/commit/0ad0ec7591367b8b23e7292392abc3c26112a4e5))
* display more information when selecting a session to load ([8abb1b9](https://github.com/stevearc/resession.nvim/commit/8abb1b97fc43c8d97da4396b102c4cbf881703dc))
* extensions can support special windows ([867c830](https://github.com/stevearc/resession.nvim/commit/867c83002b1c0e74edc356dd32ad96036edd8e7f))
* open session into current tab if it's empty ([f1374dc](https://github.com/stevearc/resession.nvim/commit/f1374dcb94c6ae7ec96101a061265814edcd8ee7))
* pre and post save/load hooks ([1ea6209](https://github.com/stevearc/resession.nvim/commit/1ea6209a2bae01fd37cfc0c450b12db647bb7b56))
* quickfix extension ([7446f89](https://github.com/stevearc/resession.nvim/commit/7446f8980deb272242f55df92c641f34835ee79f))
* save/load current win and cursor positions ([1b6268f](https://github.com/stevearc/resession.nvim/commit/1b6268fe82dde0ec51db469a3729b10f22611274))
* support autosave on exit ([a383c7f](https://github.com/stevearc/resession.nvim/commit/a383c7fd4685bd264033984d3b2b83eab4c85959))
* support window options and sizes ([adaa2ba](https://github.com/stevearc/resession.nvim/commit/adaa2ba1cd0b7f8119ee909fee3861d162cc22e5))
* tab-scoped sessions ([555875a](https://github.com/stevearc/resession.nvim/commit/555875a55db4b19a8cfba8663037060fa63ef713))


### Bug Fixes

* better support for handling swapfiles on load ([8c553c7](https://github.com/stevearc/resession.nvim/commit/8c553c796ef54c5fecb2cc7a071bd0ec27fdddc0))
* better support for saving/loading options ([84e89c0](https://github.com/stevearc/resession.nvim/commit/84e89c0458fee4c473f7c834b2736ae6baee3dac))
* catch extension errors when configuring ([a1dd2f8](https://github.com/stevearc/resession.nvim/commit/a1dd2f889c7cd907701b4901c49f35054b27337c))
* don't save or load empty buffers ([#4](https://github.com/stevearc/resession.nvim/issues/4)) ([53b742a](https://github.com/stevearc/resession.nvim/commit/53b742afd41057045a3598440c72fad072e62701))
* error in help doc generation ([d8d725a](https://github.com/stevearc/resession.nvim/commit/d8d725a433f9d840eb1f5de2622db2035c6ffbd1))
* issue with syntax highlighting after load ([e3460f4](https://github.com/stevearc/resession.nvim/commit/e3460f4b2408ba0b5703219c18aec2eea8a12a7b))
* luacheck error ([3eb9bc5](https://github.com/stevearc/resession.nvim/commit/3eb9bc5ae5aea5054c1625fca6c70f0b1ad7d487))
* luacheck errors ([156752b](https://github.com/stevearc/resession.nvim/commit/156752b05cf17733fe6fcca50ad22d193a83b161))
* luacheck warnings ([6b35039](https://github.com/stevearc/resession.nvim/commit/6b350393cc2f09632d4ee192dcb5ff4cb4c83ef8))
* potential stack overflow during setup ([6bda7fd](https://github.com/stevearc/resession.nvim/commit/6bda7fdebd5d685e7b45da408df1842c947d02f5))
* prevent double-edit of current buffer after load ([12a7d39](https://github.com/stevearc/resession.nvim/commit/12a7d39d357a9cb4fa417638c9b2c73556123b15))
* prune tab-scoped sessions for closed tabs ([a0eaa81](https://github.com/stevearc/resession.nvim/commit/a0eaa81d977356869b54b3b4f28a059cf08f5e0f))
* remove hidden dependency on overseer ([#3](https://github.com/stevearc/resession.nvim/issues/3)) ([0fb1a53](https://github.com/stevearc/resession.nvim/commit/0fb1a53761ff15fcdb017ab968cc7b1b6546b96a))
* remove unused function ([1c350a6](https://github.com/stevearc/resession.nvim/commit/1c350a6023c1af2a47f4c620bd8e9c4bd30a3f7b))
* restore correct tab on load ([29ba485](https://github.com/stevearc/resession.nvim/commit/29ba485a781eca1db9d176141726cd6f7cfc3961))
* restore last cursor position for hidden buffers ([#2](https://github.com/stevearc/resession.nvim/issues/2)) ([1f30aa2](https://github.com/stevearc/resession.nvim/commit/1f30aa2dccd8e4390992c0b7864660e1e4801aed))
* save cmdheight per-tabpage ([#7](https://github.com/stevearc/resession.nvim/issues/7)) ([c57ff6f](https://github.com/stevearc/resession.nvim/commit/c57ff6fdcd4d9ea9a109bad23aa856be0a75232c))
* save help buffers by default ([5a7037c](https://github.com/stevearc/resession.nvim/commit/5a7037c1bf0d108d4b9b4122e2b5f10f928a79f7))
* save/load dir argument works with save_all ([347e63d](https://github.com/stevearc/resession.nvim/commit/347e63d3ca8f2980d7666f58c2e558881c33b36d))
* saving tab session ([e45b8fe](https://github.com/stevearc/resession.nvim/commit/e45b8fe09d1f787b85458e1478a3d6b42273341c))
* stop using vim.wo to set window options ([3eae3bb](https://github.com/stevearc/resession.nvim/commit/3eae3bbf25f44b6c97ecc819009d541d97520d8e))
* tab_buf_filter shouldn't exclude buffers that are open in the tab ([9ca1175](https://github.com/stevearc/resession.nvim/commit/9ca1175a0347bb1a7857de80fd76ea063a20a1b6))
* tests ([da94cdc](https://github.com/stevearc/resession.nvim/commit/da94cdce4ee224947abf81b7e2b3c1248d1cb653))


### Performance Improvements

* disable most autocmds when saving/loading a session ([10ce835](https://github.com/stevearc/resession.nvim/commit/10ce8356569de78c91f3b6353e94c8abd20ca96a))
