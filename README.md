# usage

1. 编辑 `PKGBUILD` , 修改 `pkgver` 为想要编译的版本, 注意 `config` 要与大版本号对应
1. 运行 `updpkgsums` , 自动更新 `PKGBUILD` 里面的 `md5sums`
1. 运行 `makepkg -s` 编译
