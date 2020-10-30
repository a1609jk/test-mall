---
description: 本次测试为2020/10/30服务器版本
---

# 综合性问题

**测试地址：**

* PC端：[http://www.sohomall.jp/](http://www.sohomall.jp/)
* H5端：[http://m.sohomall.jp/](http://m.sohomall.jp/)
* 商家端：[http://seller.sohomall.jp/](http://seller.sohomall.jp/)
* 平台端：[http://admin.sohomall.jp/](http://admin.sohomall.jp/)

1. PID码的设定，PID码为商品编码标准品+非标准品的商品统称，且PID码在商品商品页面展示（该部分页面已有但无内容），PID码由英数大小写8位数组成，发布商品时可搜索PID码和商品编码进行。

   商品编码在系统中统一更名为：  JAN\(EAN\)/UPC/ISBN

   非标准品的编码前方hanye统一更改为SOHO

   ![20201030135815](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030135815.png)

   ![20201030134119](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030134119.png)

   ![20201030171119](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030171119.png)

2. 商品编码（JAN\(EAN\)/UPC/ISBN）输入编码时未限制位数，登录商品信息后则发布不成功，提示位数不正确（位数修改后依旧如此）。

   ![20201030154853](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030154853.png)

   ![20201030140559](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030140559.png)

3. 编辑器问题，原编辑器发布商品时，文字不能居左，图片不能并排排版失效等。现在编辑框内输入内容，控制栏不显示，无法调整内容。

   ![20201030142217](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030142217.png)

   ![20201030141011](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030141011.png) 

   ![20201030141114](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030141114.png)  

4. pid页面问题，当商品图片不规范时，页面布局失效，商品的文字内容过多时显示不正常，店铺标识显示不正常。

   ![20201030142104](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030142104.png)

   ![20201030142143](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030142143.png)

   ![20201030142259](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030142259.png)

5. 商城首页分类，二级目录展示区域过窄，无法展示全日文名称，最低宽度示例或为自适应【レディースファッション】

   ![20201030142744](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030142744.png)

6. 设置运费模板、发货地区时，仍有中国、日本字样

   ![20201030142837](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030142837.png)

   ![20201030142920](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030142920.png)

7. 表头设置问题，列表中默认显示了SKU，但是表头中为未勾选，选中sku显示时，显示异常，且无法恢复。（遗留问题）

   ![20201030143201](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030143201.png)

   ![20201030143227](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030143227.png)

   ![20201030143302](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030143302.png)

8. 从平台后台产品库管理中点击商品名称，进入商品页面异常。

   ![20201030144118](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030144118.png) 

   ![20201030144140](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030144140.png)

9. 纳品流程问题，计划中的纳品商品（商家未发货至仓库）时，公共仓首页已计算入今日纳品。

   ![20201030144345](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030144345.png)

   ![20201030144356](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030144356.png)

10. 一些特殊标识，或是背景图片的更改方法需要说明

    ![20201030144433](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030144433.png)

11. 支付问题，信用卡支付，信用卡有效期选择过去的时间可以通过？

    ![20201030144816](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030144816.png)

    ![20201030144836](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030144836.png)

12. 支付问题，选择便利店支付时未收到便利店的支付通知邮件。该功能以前已实现。
13. 个人中心检索按钮显示不正常。

    ![20201030145514](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030145514.png)

    ![20201030145552](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030145552.png)

    ![20201030145626](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030145626.png)

14. 电话号码问题仍有残留，平台后台添加操作员时输入日本手机号显示不正确，或只校验位数11位就行。目前服务器版本创建失败。

    ![20201030150331](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030150331.png)

    ![20201030150454](https://raw.githubusercontent.com/a1609jk/Typora-Picgo/master/imgs/20201030150454.png)

15. 部分字段既无中文展示也无日文字段展示，流程中会详细标注。

