## 使用
```shell
#添加到第一行
sed -i '1i\src-git packages_up https://github.com/eearphon/packages_up' feeds.conf.default

./scripts/feeds uninstall -a
rm -rf tmp/

./scripts/feeds update -a
./scripts/feeds install -a
```

## 相关链接

- [GitHub - coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)

- [OpenWrt · GitHub](https://github.com/openwrt)

- [GitHub - messense/aliyundrive-webdav](https://github.com/messense/aliyundrive-webdav)
