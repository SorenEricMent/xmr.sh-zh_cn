# xmr.sh

**xmr.sh** 脚本能够用Docker安装运行一个新的门罗节点服务器，您可以自己选择域名和配套的SSL证书，节点运行于的网络，暗网服务，Grafana监控面板，还有更多。

## 发行版支持

与如下发行版兼容并且已经经过测试：

- Debian 11
- Ubuntu Focal
- Fedora 36

其他预先安装了Docker的发行版一般也能兼容。

## Demo

[![asciicast](https://asciinema.org/a/1gL7tNhb3XgPUr26losgZaeCJ.svg)](https://asciinema.org/a/1gL7tNhb3XgPUr26losgZaeCJ)

## FAQ

请du [wiki](https://github.com/vdo/xmr.sh/wiki/FAQ)

## ToDo

- [x] Add wizard for DNS domain selection.
- [x] Status and node info at finish.
- [x] Mainnet / Stagenet / Testnet selection
- [x] Pruning enabled
- [x] Clearnet TLS port selection
- [x] Uninstall script
- [x] Make tor service optional
- [x] Block explorer (disabled)
- [x] Grafana dashboard
- [x] arm64 support for all images
- [x] monerod-lws support (experimental)
- [ ] Shellcheck via Github Actions
- [ ] Documentation
- [ ] monerod-proxy support for random node forwarding
- [ ] i2p service
- [ ] p2pool mining

# 作者

[@cirocosta](https://github.com/cirocosta) 提供了指标导出器和Grafana监控面板支持

[@sethforprivacy](https://github.com/sethforprivacy) 提供并维护Docker镜像

# 给原作者捐赠 XMR 🍕

86GwmtuKWtjJBWT8Srn4oqZHbP41k2kpG79xXKKgauJzCmZkFJ5ihwjVnRodVbVjAx64JeB7VyGbF6hEdwpcPcR7Go8x2YZ

# 翻译
由Winslow SorenEricMent(@SorenEricMent) 汉化