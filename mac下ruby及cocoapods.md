mac下ruby及cocoapods

1、用rvm管理ruby

​	1、curl -Lhttps://get.rvm.io| bash -s stable

​	2、rvm -v

​	3、rvm install 2.2.1

​	4、rvm list

​	5、rvm --default use 2.2.1

​	6、rvm uninstall ruby-2.3.0

​	7、rvm use

2、安装cocoapods

​	gem install cocoapods -v '0.39.0'

3、消除警告信息

​	gem uninstall cocoapods-deintegrate

4、The `master` repo requires CocoaPods 1.0.0 - (currently using 0.39.0)
    http://blog.cocoapods.org/Sharding/
    add:
        source "https://github.com/CocoaPods/Old-Specs" 
    To the top of your Podfile, and CocoaPods will only use the archived repo, instead of using the new repo structure.source "https://github.com/CocoaPods/Old-Specs"
