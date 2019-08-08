<p align="center"><img width="15%" src="icons/icon-128.png" /></p>
<h1 align="center">谷歌访问助手优化破解版</h1>

**本软件已破解，可永久免费使用！**

<table align="center">
  </tr>
  <tr>
    <td align="center">Google搜索</td>
    <td align="center">Chrome商店</td>
    <td align="center">Gmail邮箱</td>
    <td align="center">Google+</td>
  </tr>
</table>



## 重要
```javascritpt
路易
```


## 祝贺
祝贺 【靳蒙蒙】 七月六日新婚！




## 优化说明
  ```javascript
 1.可直接拖拽安装
 2.提高速度
 3.更多+
  ```


## 安装说明

由于新版本Chrome已禁止安装第三方应用，且本破解版无法上传至chrome商店，所以：
第一种安装方式
1. 克隆本仓库到本地或下载后解压
2. 打开Chrome扩展程序管理器 `chrome://extensions`
3. 勾选`开发者模式`
4. 点击`加载已解压的扩展程序`，选择本扩展所在目录
第二种安装方式
1.先把拓展程序的开发者按钮打开
2.把crx拖进去
3.双击运行reg


## 破解说明

- 该插件的核心代码为[bg.js](bg.js)。该文件已做代码混淆和压缩，本破解版已对该文件进行格式化。

- 该插件在Chrome启动时会检测打开的标签页是否包含推广网站，以此判断用户是否将推广网站设置为首页。因此，只需在检测标签页网址的代码上强行加入推广网站的地址，即可让该插件认为已将其添加为首页，不受12小时试用时间的限制。

  ```javascript
  a.links.push("http://360.hao245.com");
  a.links.push("http://123.hao245.com");
  ```

- 该插件通过代理服务器访问Google，代理服务器的地址和密码以及PAC脚本均由插件动态获取。研究发现，即使将PAC脚本替换掉，依然只能访问Google和GMail，其余网站无法打开，表明服务器端已进行了限制。
