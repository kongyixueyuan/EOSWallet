# EOSWallet
使用NodeJS基于本地网络，最后升级为测试网络开发的EOS钱包，包含钱包模块、账户模块、转账模块，重难点是账户的权限管理与网络资源管理，另外使用了cleos配置账号权限。

项目介绍

钱包种类非常多，主流的有以太坊钱包、比特币钱包、EOS钱包以及其他类型的虚拟货币钱包。在咱们这次课程中是来开发EOS钱包，以太坊钱包可以在博主的主页查看，在后面的课程也会陆续推出比特币钱包、XRP钱包、TRC钱包、ADA钱包等。

本教程围绕以太坊钱包项目开发逐步进行讲解，该项目以NodeJS语言编写后端，使用web前端演示。内容包含：视频、文档、源码。

EOS作为一个广泛使用的区块链开发平台，被称作为区块链3.0，包含的数字货币资产的转移和投资必然需要使用到钱包，因此钱包是区块链领域必需掌握的知识，另外也是交易所开发的核心。目前企业对钱包开发的需求较大，很少有成熟的钱包开发教程，因此特推出此教程满足企业与市场上对钱包的需求，以帮助大家快速全面的掌握EOS钱包理论与开发实践。



本教程能学到什么

- 彻底搞清楚EOS账户系统的权限配置
- 搞清楚RAM、Network BandWidth、CPU BandWidth它们的关系与重要作用
- 对网络资源进行买卖、抵押、赎回等以满足你对EOS操作的需求
- 使用RPC轻松访问EOS区块链数据
- 使用EOSJS库轻松访问EOS区块链数据
- 安全管理和转移你的Token数字资产



教程大纲

1. 不得不说的一些概念
2. EOS开发环境搭建
3. EOS钱包项目整体架构设计
4. 使用keosd服务开发钱包模块
5. 使用cleos工具管理账号权限
6. 深入浅出EOSJS：连接到主网、测试网、交易
7. 创建账号与查看账号权限配置
8. EOS代币转账交易
9. 基于测试网络进行开发
10. 详解与获取ARM、NET、CPU资源数据



项目路线

项目的路线规划是：

- 介绍以太坊钱包中涉及的重点理论知识。

- EOS本地开发环境搭建。

- 项目架构搭建：以NodeJS开发后端，使用了Koa与相关框架，前端以web进行交互。

- cleos辅助工具配置账户权限。

- 使用RPC与EOS区块链进行交互一步步实现钱包、账号、转账模块各个功能，另外也使用了eosjs库执行交易。

- 最后连接到测试网络进行测试并管理您的网络资源


---


**完整文档请查看原文：http://chaindesk.cn/columnlist.html?id=2**

版权声明：博客中的文章版权归博主所有，未经授权禁止转载，转载请联系作者（微信：lixu1770105）取得同意并注明出处。

