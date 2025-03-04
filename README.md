# Kagura @ PLCT Kagura 在 PLCT 的工作
所属小队: [RevyOS 小队测试实习生](https://github.com/plctlab/weloveinterns/blob/master/open-internships.md#j143-revyos%E5%B0%8F%E9%98%9F%E6%B5%8B%E8%AF%95%E5%AE%9E%E4%B9%A0%E7%94%9F20241111%E5%BC%80%E6%94%BE100%E5%90%8D)

# 工作内容

## 2024年12月
- PR/Merged: [revyos/.github](https://github.com/revyos/.github) 修复 DeadLink [Link](https://github.com/revyos/.github/pull/1)
- PR/Merged: [revyos/docs](https://github.com/revyos/docs) 根据拿到的开发板对原有的安装流程文档进行了修改，并修改了 `docker` 使用文档 [Link](https://github.com/revyos/docs/pull/9)，共 3 个 commit
- Issue: [FIFCC/revyos-test issue#1](https://github.com/FIFCC/revyos-test/issues/1) 找到最新镜像在 LicheePi4A 上无线模块不可用
- PR/Merged: [revyos/docs](https://github.com/revyos/docs)增加了 ROS2 的安装教程 [Link](https://github.com/revyos/docs/pull/9)，共 2 个 commit
- Issue: [FIFCC/revyos-test issue#2](https://github.com/FIFCC/revyos-test/issues/2) Chromium 浏览媒体较多的网页时出现 BUG: Bad page state in process Media 以及短时严重卡顿

## 2025年1月
- PR/Merged: [revyos/docs](https://github.com/revyos/docs)修改了刷写文档，详见PR内说明 [Link](https://github.com/revyos/docs/pull/18)
- PR/Merged: [revyos/docs](https://github.com/revyos/docs)翻译刷写文档 [Link](https://github.com/revyos/docs/pull/20)
- 测试20250123镜像（以AIC8800 Wifi 驱动为主），测试结论: [revyos/discussions/83](https://github.com/orgs/revyos/discussions/83#discussioncomment-12185520)

## 2025年2月
[revyos/docs](https://github.com/revyos/docs) 将文档页面转移到 docusaurus 框架  
  PRs:
  - [Init docusaurus](https://github.com/revyos/docs/pull/24)
    - 切换至docusaurus
    - 添加本地搜索
    - 添加统一管理最新版本镜像链接
    - 添加根据语言切换图片
    - 使用 mdx 特性实现ROS选择版本，显示对应命令
    - 添加 README 帮助之后编写文档

  - [Add links to PLCT Lab, Fix deadlink in lpi4a install page](https://github.com/revyos/docs/pull/25)
    - 添加到 PLCT 的链接
    - 消除死链

  - [Fix titles, add title writing hints in readme](https://github.com/revyos/docs/pull/26)
    - 修改部分文章标题
    - 为之后编写文档提供了标题撰写提示
  
  - [Homepage: replace logo with right arrangement, add night version](https://github.com/revyos/docs/pull/27)
    - 更新主页
    - 修复原 logo 没有对齐

  - [Add win-linux doc link, by-ua redir, mention uboot var may cause problem](https://github.com/revyos/docs/pull/31)
    - 在 Windows 和 Linux 刷写页面更明确提到对方系统刷写
    - intro 位置刷写教程现在会根据 User Agent 跳转
    - 提到 fastboot usb 0 可能会导致问题

  - [fix ghpage always add shash at end of url](https://github.com/revyos/docs/pull/32)
    - 解决一些 ghpages 导致的问题
  
  - [Add project lists](https://github.com/revyos/docs/pull/35)
    - 添加了项目[列表页面](https://docs.revyos.dev/projects/)

