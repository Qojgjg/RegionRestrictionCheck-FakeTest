

## 脚本介绍
本脚本基于[lmc999/RegionRestrictionCheck](https://github.com/lmc999/RegionRestrictionCheck)代码进行修改


脚本默认提示全解锁-无广告-仅供娱乐,不代表最终实际解锁结果

ALL check is Fake ！
## 使用方法

**使用脚本前请确认curl已安装**

````bash
bash <(curl -L -s https://github.com/oneg1/RegionRestrictionCheck-FakeTest/raw/main/check.sh)
````

##### 只检测IPv4结果：
````bash
bash <(curl -L -s https://github.com/oneg1/RegionRestrictionCheck-FakeTest/raw/main/check.sh) -M 4
````

##### 只检测IPv6结果：
````bash
bash <(curl -L -s https://github.com/oneg1/RegionRestrictionCheck-FakeTest/raw/main/check.sh) -M 6
````

##### 指定检测的网卡名称：
````bash
bash <(curl -L -s https://github.com/oneg1/RegionRestrictionCheck-FakeTest/raw/main/check.sh) -I eth0
````

##### 选择脚本语言为英文：
````bash
bash <(curl -L -s https://github.com/oneg1/RegionRestrictionCheck-FakeTest/raw/main/check.sh) -E
````

