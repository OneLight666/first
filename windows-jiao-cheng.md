---
description: 在 Windows PC/平板 上使用 ShadowsocksR 客户端接入流量中继服务
---

# Windows 教程



| 系统要求： | Windows XP 及以上 |
| :--- | :--- |
| 软件版本： | ShadowsocksR 最新版 |
| 设备要求： | Windows PC / Tablet |

### 配置及使用教程 <a id="pei-zhi-ji-shi-yong-jiao-cheng"></a>

完成以下简单配置步骤，即可享用Onelight云服务。\(阁下可能需要花5~10分钟左右的时间完成教程\)

### 1.请使用浏览器打开 OneLight 用户中心 - 查看快速添加节点 <a id="1-qing-shi-yong-liu-lan-qi-da-kai-hai-tun-wan-yong-hu-zhong-xin-cha-kan-kuai-su-tian-jia-jie-dian"></a>

![](.gitbook/assets/ping-mu-kuai-zhao-20190921-17.07.21min%20%281%29.png)

* 点击下载 Windows 客户端文件并安装。
* 复制订阅地址，配置客户端时需使用。

订阅地址包含您的订阅信息，阁下应当把它当做密码一样妥善保管，请勿泄露给他人！

### 2.打开 ShadowsocksR 客户端 <a id="2-da-kai-shadowsocksr-ke-hu-duan"></a>

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LHgUdk_QhV-zuTXQKHC%2F-LduLndLAczsC-RAJKUw%2F-Ldu5NrsJ3SEdAMmTwig%2Fimage.png?alt=media&token=36cbae2a-ba98-47c1-896e-2da62d7316d7)

* 根据系统.NET版本选择客户端。

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LHgUdk_QhV-zuTXQKHC%2F-LduLndLAczsC-RAJKUw%2F-Ldu4KhMxTy0zgNlHC2z%2Fimage.png?alt=media&token=022645e1-08aa-4c19-920a-50b1ea9db823)

* 右键点击托盘栏的纸飞机图标
* 关闭**「负载均衡」**
* 打开**「SSR服务器订阅设置」**

### 3.配置订阅地址 <a id="3-pei-zhi-ding-yue-di-zhi"></a>

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LHgUdk_QhV-zuTXQKHC%2F-LduLndLAczsC-RAJKUw%2F-LduHVo3qk_OJRi34CPa%2Fimage.png?alt=media&token=19ca378d-5f7c-46c6-b959-5c2e6a8c88cc)

* 点击「**Add**」按钮
* 右侧「**网址**」的「**输入框**」中粘贴刚才在官网复制的「**订阅地址**」
* 勾选「**自动更新**」并

### 4.更新订阅 <a id="4-geng-xin-ding-yue"></a>

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LHgUdk_QhV-zuTXQKHC%2F-LHju-C3DvSf03Duf6ia%2F-LHjwdN1jCAw7xF31pwM%2Fimage.png?alt=media&token=ca929e23-8005-426e-8584-b8e619f8386a)

* 再次右键点击托盘栏纸飞机图标，在「**服务器订阅**」选项卡中选择 **更新 SSR 服务器订阅（不通过代理）**

**​**

一小段时间后（具体时间取决于您的网络环境），您将会收到 **服务器订阅更新成功** 的通知消息，同时查看服务器列表也可以看到对应的 海豚湾 接入点。![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LHgUdk_QhV-zuTXQKHC%2F-LduV-qgB0twbT36DgTx%2F-LduV7erX4WRGY7XqDyN%2Fimage.png?alt=media&token=a345be46-83df-4a1d-9052-4c090522cef4)

* 提示「**更新成功**」
* 右键点击托盘栏的纸飞机图标 「**服务器**」**-** 「**海豚湾**」中选择节点使用

如果订阅失败，可尝试将本地DNS地址改为114.114.114.114 和 119.29.29.29 并重试更新。![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LHgUdk_QhV-zuTXQKHC%2F-LduLndLAczsC-RAJKUw%2F-LduKBR4Kg5-puxIshZ2%2Fimage.png?alt=media&token=f2fa6b87-f8b0-48c3-ae1e-4c71cd09329a)

使用 海豚湾 订阅节点是目前最推荐的做法，使用后您无需每次在 海豚湾 更新接入点后手动前往 海豚湾 用户中心更新配置，而是可以令客户端在每次启动是自动尝试更新配置文件，同时您也可以手动来立即更新接入点信息。

### 5.配置规则 <a id="5-pei-zhi-gui-ze"></a>

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LHgUdk_QhV-zuTXQKHC%2F-LHju-C3DvSf03Duf6ia%2F-LHjxV56a0ud3b0hrdVf%2Fimage.png?alt=media&token=7a666212-bdfc-4d13-a42b-08582a330fbf)

* 右键点击托盘栏纸飞机图标，在「**代理规则** 」菜单中选择**「绕过局域网和大陆」**。

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LHgUdk_QhV-zuTXQKHC%2F-LHju-C3DvSf03Duf6ia%2F-LHjxhUml0Lx85YlzPwo%2Fimage.png?alt=media&token=84afa9a1-e9b7-4c61-8dce-fdeccd560fcd)

* 再次右键点击托盘栏纸飞机图标，在**「系统代理模式」**菜单中选择**「全局」**。

> #### 现在您可以享受 onelight 云服务 接入点带来的全新国际网络访问体验。 <a id="xian-zai-nin-ke-yi-xiang-shou-hai-tun-wan-yun-fu-wu-jie-ru-dian-dai-lai-de-quan-xin-guo-ji-wang-luo-fang-wen-ti-yan"></a>



