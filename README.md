# ban-ads-hosts
用于屏蔽大部分的赚钱软件的广告，建议配合着 Bolkada或DNS66或Adaway食用（Adaway是通过修改安桌系统 /system/etc/hosts 的方式来达到屏蔽广告的目的，需要root，前两者则是以本地VPN的形式过滤广告，支持多个hosts同时作为过滤规则）
(可能会存在误杀，并不能保证100%屏蔽，部分软件是直接连接ip下载广告的)🤓

Blokada下载地址：https://f-droid.org/packages/org.blokada.alarm/

DNS66下载地址：https://f-droid.org/packages/org.jak_linux.dns66/

使用方法：

Blokada添加此规则方法：下载并运行Blokada--->屏幕下方三根横线--->广告过滤--->主机列表---> Add a new host list --->粘贴地址： https://gitee.com/jlili/ban-ads-hosts/raw/master/main.txt --->继续--->名称随意起一个（你也可以点击“生成”按钮）--->继续--->回到主界面，打开开关，等到开关下方出现“Blokada is active”字样，基本上就算是成功了🤗🤗

DNS66添加此规则方法：下载并运行DNS66--->点击主界面中的域名过滤器，记得启用域名过滤，并开启每日更新--->右下角 + --->位置，粘贴URL：
https://gitee.com/jlili/ban-ads-hosts/raw/master/main.txt --->行为 拒绝--->√ --->回到 “启动/停止”，点击启动，屏幕中间出现√，则为成功🤗

补充：项目中 的 Adguard-simple-domain.txt 基于Adguard规则--简化域名过滤器，由于Adguard在开启“屏蔽应用中广告”和“HTTPS过滤”后会使加载速度变慢（可能是开了很多过滤器的原因吧），所以临时抛弃Adguard，转行至hosts屏蔽广告，另外补充一下Adaway官方提供的Hosts：https://adaway.org/hosts.txt
 
 本人是一位高中学生，所以该项目在节假日之时才可能会更新，若觉得项目不错，别忘了Star，Watch，Fork,别忘了提供Issues，以便完善规则哦！

国内用户：https://gitee.com/jlili/ban-ads-hosts
国际用户：https://github.com/zhangxiaohua1001/ban-ads-hosts

