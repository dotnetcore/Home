<p>
    <a href="https://www.dotnetcore.xyz" target="_blank" title="Home of .NET Core Community">
        <img width="100" src="./img/dotnetcore.png" />
    </a>
</p>

<p align="center">
    <a href="README.md">English</a> |   
    <span>中文</span>
</p>

# .NET Core Community Home

.NET Core Community(NCC) 是一个基于并围绕着 .NET Core 技术栈展开组织和活动的开源社区，由 [Alex LEWIS](https://github.com/alexinea)、[LIU Haoyang](https://github.com/liuhaoyang)、[HE Zhenxi](https://github.com/utilcore)、 [XIE Yang](https://github.com/kiler398) 和 LOU Yu 创建于 2016 年年中。我们希望通过我们 NCC 社区的努力，能为 .NET Core 生态注入更多活力。

- Github: https://github.com/dotnetcore
- 官方网站: https://www.dotnetcore.xyz
- QQ 群: 436035237
- 微信群组: _二维码请在 QQ 群里询问_

## 我们的历史

我们成立于 2016 年年中，原先名为「.NET Core 中文学习组（.NET Core China Studying Group）」，并在同一时间创建了我们的 QQ 群组「dotNET Core Studying Group」，且至今未更名。

NCC 最初的目标是翻译微软 ASP.NET Core（时名 ASP.NET 5）的官方文档。我们得到了许多人的帮助和鼓励（[2016 年翻译计划贡献者名单](./docs/history/people-who-translated-in-2016.md)），并在 Twitter 上获得了官方的点赞。我们的[翻译成果](https://github.com/dotnetcore/aspnetcore-doc-cn)也为第一批接触 ASP.NET Core 的中文开发者们提供了巨大的便利。

经历两年的挑战和考验，NCC 逐渐演变为一个开源社区组织，拥有了十多个成员项目和团队。

在这期间我们得到了许多人和组织的帮助，包括 JetBrains 公司对我们的赞助。

2019 年年初，我们向 [.NET 中文社区联席会议（.NET China Community Joint Meeting, NCJM）](https://github.com/dotnet-china)提供了 NCC 域名资产「dotnet-china.com」，并启用全新域名「[dotnetcore.xyz](https://www.dotnetcore.xyz)」。我们 NCC 将同联席会议（NCJM）一道，让 .NET 再现魅力。

## 仓库与项目

我们的成员项目分为两阶段：_沙盒阶段（NCC Sandbox Projects phase）_ 和 _顶级项目阶段（NCC Top-Level Projects phase）_。当新项目申请加入 NCC 并完成评审和加入前的全部流程（包括预备工作）后，项目将自动进入 _沙盒阶段_。申请加入 NCC 请查阅[如何加入我们](#如何加入我们)一节。

### 顶级项目

_顶级项目阶段 NCC Top-Level Projects phase_ 的项目可用于生产环境。

- **[AspectCore](https://github.com/dotnetcore/AspectCore-Framework)**，.NET Standard 跨平台 AOP 框架。
- **[CAP](https://github.com/dotnetcore/CAP)**，基于最终一致性的微服务分布式事务解决方案，具有 Outbox 模式的事件总线。
- **[DotnetSpider](https://github.com/dotnetcore/DotnetSpider)**，类似 WebMagic 与 Scrapy 的 .NET Standard 轻量级、高效且高速的高级爬虫库。
- **[NPOI](https://github.com/dotnetcore/NPOI)**，用于读写 Microsoft Office 二进制文件和 OOXML 文件格式的 .NET 类库。
- **[Surging](https://github.com/dotnetcore/Surging)**，分布式微服务引擎，提供高性能的 RPC 远程服务调用。

### 沙盒项目

_沙盒阶段 NCC Sandbox Projects phase_ 的项目依旧处于快速发展阶段，且尚需时间和项目来检验其设计。

- **[Alipay SDK](https://github.com/dotnetcore/Alipay.AopSdk.Core)**，基于 .NET Standard 2.0 开发的第三方支付宝服务端 SDK，提供比官方更可靠的设计，但仍与官方 apis 保持一致。
- **[CanalSharp](https://github.com/dotnetcore/CanalSharp)**，[Alibaba Canal](https://github.com/alibaba/canal) 的开源 .NET 客户端，Alibaba Canal 是一个基于 MySQL `binlog` 的增量发布与订阅组件。更多信息请查阅 [https://github.com/alibaba/canal/wiki](https://github.com/alibaba/canal/wiki)。
- **[EasyCaching](https://github.com/dotnetcore/EasyCaching)**，开源缓存库，包含基本用法和缓存的高级用法，可助我们更轻松地处理缓存。
- **[FlubuCore](https://github.com/dotnetcore/FlubuCore)**，跨平台构建与部署自动化系统，基于 C# 代码构建项目和执行部署脚本。（[FlubuCore 的示例](https://github.com/dotnetcore/FlubuCore.Examples)）
- **[KoobooJson](https://github.com/dotnetcore/KoobooJson)**，更小更快的 C# JSON 序列化工具（基于表达式树构建）。
- **[Natasha](https://github.com/dotnetcore/Natasha)**，简化 IL 操作，优化 IL 编程流程，并编写具有高性能的动态缓存。
- **[SmartCode](https://github.com/dotnetcore/SmartCode)**，优秀的开源代码生成器（不仅仅是生成代码），它基于执行流程，支持 ETL 模式，高度灵活和可扩展，还支持自定义模板和多种模板样式，以及多种数据库。
- **[SmartSql](https://github.com/dotnetcore/SmartSql)**，通过简单的连接字符串来运行，解析 SQL 的 XML 配置和各种性能观察方法，使性能问题一目了然。 SmartSql 具有与 Dapper 相似的性能水平，并提供许多特性：动态代理存储、分布式缓存、类型处理器、自动生成 CUD 代码、分布式 Id 生成器、性能诊断、AOP 级别的事务/缓存（内存，分布式缓存）、读/写分离、代码生成器、高性能的批量插入等。
- **[Util](https://github.com/dotnetcore/Util)**，.NET Core 平台下的开源应用程序，旨在提高小型团队的开发效率。 它由通用帮助程序，分层体系结构设计，UI 组件，第三方组件和服务接口包组成。
- **[WebApiClient](https://github.com/dotnetcore/WebApClient)**，基于 HttpClient 的开源项目，只需通过定义 C# 接口并修改一些细节便可异步调用远程 http 接口。
- **[WTM](https://github.com/dotnetcore/WTM)**，针对中小规模后台管理系统的开发利器，基于 .NET Core，实现零编码创建项目、零编码生成业务模块。框架严格遵循 MVVM 的开发模式，经过数十个真实项目检测，可以极大提高开发效率，降低开发成本。
- **[ZKWeb](https://github.com/zkweb-framework/ZKWeb)**，NCC 外部项目。ZKWeb 是一个灵活的适用于 .NET 和 .NET Core 的带有[插件系统](http://github.com/zkweb-framework/ZKWeb.Plugins)和模板系统框架。

想加入我们么？下一个 NCC 成员项目非你莫属！[下一节](#如何加入我们)将介绍如何加入我们。

## 如何加入我们

### 要求

- 项目基于 .NET Core（包括 .NET Standard 和 .NETCoreApp）；
- 具有清晰的提交记录（git commit log）
- 具有单元测试（且覆盖率在 65% 以上）
- 具有适当的跑分数据（benchmark info），对于基础项目这是必须的；
- 项目创建时间至少有三个月；
- 作者或核心贡献者对项目的最后一次更新在一个月内；
- 项目至少有 50 颗星；
- 具有详细的项目描述、且带有项目示例、文档和 Wiki；
- 没有商业组织和公司的赞助，也未有为项目开发者支付薪资的；
- 不存在版权问题或纠纷；
- 具有开源许可。

※ 在特殊情况下，可适当降低某要求

[（完整版要求...）](./docs/rules/project-requirements-for-joining-ncc.md)

### 步骤

#### 第一步 申请

在 [dotnetcore/Home](https://github.com/dotnetcore/Home/issues/new) 提交申请，并确保申请中包含以下项：

1. 项目描述；
2. 项目官档（GitHub）地址；
3. 项目官网地址；
4. 项目文档/Wiki 的地址；
5. 作者和核心贡献者信息；
6. 许可证。

#### 第二步 初步评审与技术评审

将由 NCC 开源项目管理委员会处理这两部分的评审工作

#### 第三步 投票

将由 NCC 开源项目管理委员会发起内部投票。

投票将在 72 小时内完成。投票后，将公示结果。

#### 第四步 加入前预备工作

NCC 工作人员将与项目作者讨论加入前的最后工作。

[（完整版步骤...）](./docs/rules/project-steps-for-joining-ncc.md)

## 财资管理

### 捐赠

<img height=200 src="./img/ncc-donation-qrcode.png" title="Scan and donate"/>

When you donate, **PLEASE TELL US YOUR NAME AND TO MARK "NCC"**, thank you.

当你捐赠时，**请标注「NCC」，并留下你的名字**，万分感激。

资金将由 LIU Haoyang 托管，并由 Alex Lewis 登记在册。

**万分感谢您的捐赠**

## 支持与赞助

<a href="https://www.jetbrains.com/?from=.NETCoreCommunity(NCC)" target="_blank">
    <img src="./img/jetbrains.svg" title="JetBrains" />
</a>

## 反馈

- 在使用 [NCC 成员项目](#仓库与项目)遇到问题，请到相应项目下提交 issue；
- 对 NCC 的建议和意见，可以[在此创建 issue](https://github.com/dotnetcore/Home/issues/new)，与我们取得联系；
- 也可以通过 QQ 群（号码 436035237）反馈。
  这个群是个 3000 人大群，感谢 XIE Yang 每年为这个群续费。
