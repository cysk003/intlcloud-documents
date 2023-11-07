MFA，Multi-FactorAuthentication，即多因子认证，是一种简单有效的安全认证方法。它能够在用户名和密码之外，再增加一层保护。MFA 设备，又叫动态口令卡或 Token 卡，是提供这种安全认证方法的设备。目前腾讯云仅提供虚拟 MFA 设备 。


## 虚拟 MFA 设备
虚拟 MFA 设备是一个产生动态安全码的应用程序，它遵循基于时间的一次性密码（TOTP）标准（RFC 6238）。腾讯云的虚拟 MFA 目前仅支持 Google Authenticator。


### 绑定虚拟 MFA 设备
1. 登录 [腾讯云控制台](https://console.tencentcloud.com)，单击右上角账号名称，单击【安全设置】。
2. 进入安全设置页面后，选择【基本设置】>【MFA 设备】，单击【绑定】。
3. 在弹出的身份验证页面中，根据页面提示，完成身份验证。
4. 选择虚拟 MFA 设备，依照页面指引进行绑定操作。
![](https://staticintl.cloudcachetci.com/yehe/backend-news/Fy6U618_MFA1.png)
![](https://staticintl.cloudcachetci.com/yehe/backend-news/8uSA551_MFA2.png)
5. 单击【提交】，即可完成虚拟 MFA 设备绑定。


### 解绑虚拟 MFA 设备
1. 登录 [腾讯云控制台](https://console.tencentcloud.com)，单击右上角账号名称，单击【安全设置】。
2. 进入安全设置页面后，选择【基本设置】>【MFA 设备】，单击【解绑】。
3. 在弹出提示框页面，单击【确定解绑】。
4. 在弹出的身份验证页面中，输入6位数动态安全码，单击【确定】，完成解绑。
