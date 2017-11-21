# hm webshell scanner 1.3.0 release note

## new feature

    1. 特征库版本升级到7，修正了一个绕过
    2. 增加恶意挖矿程序检测
    3. 支持离线深度查杀

## bug fix

    1. 修正了部分目录内的文件无法扫描的BUG

## known issue

    1. 在某些系统下默认使用cgo导致程序崩溃，使用export GODEBUG=netdns=go可以解决


	
