---
description: 在 Android 设备上使用 ShadowsocksR(R) App 接入流量中继服务
---

# Android 教程

| 系统 | 软件版本 |
| :--- | :--- |
| Android4.4+ | ShadowsocksR 最新版 |

## 配置订阅节点及使用教程

_完成以下简单配置步骤，即可享用Onelight云服务。\(阁下可能需要花5~10分钟左右的时间完成教程\)_

### 一 .请使用浏览器打开 _OneLight_ 用户中心 - 下载软件并复制订阅地址

#### [传送onelight官网](https://onelight.cloud/user):[https://onelight.cloud/user](https://onelight.cloud/user)

![](.gitbook/assets/ping-mu-kuai-zhao-20190921-17.19.43min.png)

1. 点击下载 Android apk 并安装。
2. 复制订阅地址，配置客户端时需使用

{% hint style="info" %}
订阅地址包含您的订阅信息，阁下应当把它当做密码一样妥善保管，请勿泄露给他人！
{% endhint %}

### 二. 打开安装的 ShadowsocksR 应用程序

![&#x70B9;&#x51FB;&#x9876;&#x90E8;shadowsockes R](.gitbook/assets/assets_-lhgudk_qhv-zutxqkhc_-le3sndclyemz4pavhau_-le3vtf8tc-pbum53jwg_2019-05-05-at-4.21-am.png)

* 然后点击顶部的**「ShadowsocksR」**区域进入接入点列表。

![](.gitbook/assets/assets_-lhgudk_qhv-zutxqkhc_-le3sndclyemz4pavhau_-le3xvmg67lxp5i3bjb8_2019-05-05-at-4.27-am.png)

* 默认有一个**「Android SSR Default」**的无效连接信息，向右滑动将其删除。
* 点击在接入点列表页面底部的**「+」**按钮，并选择**「添加/升级 SSR 订阅」**

![](.gitbook/assets/assets_-lhgudk_qhv-zutxqkhc_-le3sndclyemz4pavhau_-le3_lghqybqhiardu41_2019-05-05-at-4.43-am.png)

* 订阅列表中默认有一个**「FreeSSR-public」**订阅，向右滑动将其删除。
* 在弹出的对话框中点击**「与节点一起删除」**。

![](.gitbook/assets/assets_-lhgudk_qhv-zutxqkhc_-le3sndclyemz4pavhau_-le3bbfdjnw0jxni_8ho_2019-05-05-at-4.47-am.png)

* 再次点击接入点列表页面底部的**「+」**按钮，选择**「添加/升级 SSR 订阅」**，在订阅列表中点击**「添加订阅地址」**。

![](.gitbook/assets/assets_-lhgudk_qhv-zutxqkhc_-le3sndclyemz4pavhau_-le3cnzamqfx9ne_6cox_2019-05-05-at-4.52-am.png)

* 长按文本框空白区域，选择**「粘贴」**，将第一步复制的订阅地址粘贴到文本框中。点击**「确定」**
* ShadowsocksR 应用程序显示**「处理中」**。这可能需要一小段时间，具体根据网络情况而定

{% hint style="warning" %}
更新失败与网络环境有关，多次失败建议 4G、WIFI 环境都尝试更新一下。
{% endhint %}

![](.gitbook/assets/assets_-lhgudk_qhv-zutxqkhc_-le3sndclyemz4pavhau_-le3eya5n0o2wacpchjz_2019-05-05-at-5.01-am%20%281%29.png)

* 勾选 **自动更新**。
* 点击**「确定并升级」**就可以导入最新的 Onelight 接入点信息并自动更新了。

![&#x5728;&#x8282;&#x70B9;&#x5217;&#x8868;&#x4E2D;&#x9009;&#x62E9;&#x9002;&#x5408;&#x60A8;&#x7684;&#x8282;&#x70B9;](.gitbook/assets/assets_-lhgudk_qhv-zutxqkhc_-le3sndclyemz4pavhau_-le3ftjnhj0cgmxue-2v_image.png)

{% hint style="info" %}
选择任意带有地区名字的节点使用（到期时间等信息提示节点无法使用）
{% endhint %}

### 三.分流设置

![](.gitbook/assets/assets_-lhgudk_qhv-zutxqkhc_-le3sndclyemz4pavhau_-le3i5dvdlug-k2qivb2_2019-05-05-at-5.18-am.png)

1. 设置**「路由」**为**「绕过局域网和中国大陆地址」**。
2. 更改**「China DNS」**选项为 **119.29.29.29:53,223.5.5.5:53**
3. 更改**「DNS」**选项为 **8.8.8.8:53,8.8.4.4:53**
4. 将**「IPv6路由」「分应用代理」「UDP转发」**关闭。
5. 全部完成后点击右上角**「纸飞机」**图标连接。

![&#x5982;&#x679C;&#x662F;&#x9996;&#x6B21;&#x8FDE;&#x63A5;&#xFF0C;&#x5219;&#x7CFB;&#x7EDF;&#x4F1A;&#x5F39;&#x51FA;&#x5982;&#x4E0A;&#x7684;&#x63D0;&#x793A;&#x6846;&#xFF0C;&#x8BF7;&#x70B9;&#x51FB;&#x300C;&#x786E;&#x5B9A;&#x300D;](.gitbook/assets/assets_-lhgudk_qhv-zutxqkhc_-le3sndclyemz4pavhau_-le3jytcwmi91pulvnvl_2019-05-05-at-5.28-am%20%281%29.png)

* 如果是首次连接，则系统会弹出如上的提示框，请点击**「确定」**



> #### 现在您可以享受 Onelight云服务 接入点带来的全新国际网络访问体验。

