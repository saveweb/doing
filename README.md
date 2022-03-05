# Save The Web (Doing)

本仓库为 [saveweb/rss-list](https://github.com/saveweb/rss-list) 和 [saveweb.othing.xyz](https://saveweb.othing.xyz) 对应的维护仓库。

## Issue 发布及编辑规范草案

- 每个博客事件请单独发一个 Issue
    - Issue重用例外情况：
        > 网站出现的状况与先前的 issue 相同（问题复现），比如，只是出现了简单的SSL到期这样的问题，可重用（reopen）之前的 issue 。对于**完全相同**的问题，用相同的 issue 可以减少 issues 数量以及让后期表格整理更容易。但需要注**保留 issue 的标签（tags），不到万不得已不能乱撤下标签并放上新标签**。
        > 
        > 假如是不同类型的问题。如先前是`ssl错误`而现在是`网站数据库错误`。则另开一个 issue。如果后续还出现了第二次的数据库出错，就 reopen 贴了`数据库错误`标签的 issue。

- 博客 ID 可前往 [box.othing.xyz](https://box.othing.xyz) 获取，如：<https://box.othing.xyz/i/?get=f_1> 的 ID 是 1，<https://box.othing.xyz/i/?get=f_410> 的 ID 是 410。对于没有 ID 的博客，说明即可。
- 如果博客有对应的上游列表，如 [timqian/chinese-independent-blogs](https://github.com/timqian/chinese-independent-blogs)，还需向上游发起 Pull Request 同步更改。

## 维护流程

> 本部分内容最后更新于 2021 年 6 月 20 日。

1. 寻找问题内容
    1. 简单的找出 RSS 损坏，RSS 失效，网站证书错误，网站域名问题等问题方向
    2. 使用 [测试工具](https://github.com/saveweb/tools) 进行问题诊断
    3. 记录问题
2. 尝试寻找问题原因
    1. 查阅博文，寻找更换域名、博客系统之类的内容
    2. 寻找博主的社交网络，比如推特，查看博主是否知道网站问题
3. 判断是否与博主联系<br>
   参考博文内容与社交网络中的博主意愿，来选择帮助博主的方式：
    - 提醒博主网站错误
    - 给博主推荐 [Save The Web Project](https://saveweb.othing.xyz)
4. 联系博主
    1. 获取网站关于页面以及其他信息中的联系方式
    2. 以 Save The Web Project 的身份联系博主
5. 等待<br>
   在此期间可以处理其他网站相关的工作。
6. 最后
    1. 检查是否有上游目录需要提交修改
    2. 修改 [box.othing.xyz](https://box.othing.xyz) 里的分类或其他信息
