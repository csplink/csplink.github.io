---
title: 开始上手
date: 2022-09-25
---

## 环境搭建

1. 下载安装 [Visual Studio 2022 Community](https://visualstudio.microsoft.com/zh-hans/vs/)

   ![image-20220821184828961](../assets/start/image-20220821184828961.png)

2. 打开后选择此项安装

   ![image-20220821185308486](../assets/start/image-20220821185308486.png)

3. 安装完毕之后，即可进行正常编译。

   ![image-20220821185653176](../assets/start/image-20220821185653176.png)

4. 能够编译并不代表能够正常运行，软件运行需要数据库的支持，在app.xaml.cs中指定了debug下的数据库路径，即与csp同级路径下
   - 数据库链接: [csp_mcu_db](https://github.com/xqyjlj/csp_mcu_db)

   - 芯片包：[csp_hal_apm32f1](https://github.com/xqyjlj/csp_hal_apm32f1)

   ![image-20220821185931551](../assets/start/image-20220821185931551.png)

   ![image-20220821190046606](../assets/start/image-20220821190046606.png)

5. 由此，软件便可正常运行。

   ![image-20220821190417107](../assets/start/image-20220821190417107.png)

6. 因目前暂无一个稳定版本，所以编译时请采用最新分支。

**可能碰到的错误**

1. 可查看nuget是否设置正确

   ![image-20220821191121598](../assets/start/image-20220821191121598.png)

2. 如果没有此项，请手动设置

   ![image-20220821191257245](../assets/start/image-20220821191257245.png)