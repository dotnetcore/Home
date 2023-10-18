<p>
    <a href="https://www.dotnetcore.xyz" target="_blank" title="Home of .NET Core Community">
        <img width="100" src="./img/ncc-logo.png" />
    </a>&nbsp;
    <img height="100" src="./img/ncc-name.png" />
</p>

<p align="center">
    <a href="README.md">English</a> |   
    <span>中文</span>
</p>

# .NET Core Community Home

.NET Core Community （.NET 中心社区，简称 NCC）是一个基于并围绕着 .NET 技术栈展开组织和活动的非官方、非盈利性的民间开源社区，她诞生于 2016 年年中，由[刘浩杨](https://github.com/liuhaoyang)先生、[何镇汐](https://github.com/utilcore)先生、[谢炀](https://github.com/kiler398)先生、娄宇先生和[刘怡](https://github.com/alexinea)先生联合发起、近百名 .NET 开发者共同成立。我们希望通过我们 NCC 社区的努力，与各个开源社区一道为 .NET 生态注入更多活力。

- Github: https://github.com/dotnetcore
- 官方网站: https://www.dotnetcore.xyz
- CORE QQ 群: 436035237
- PURE QQ 群：邀请制
- 微信群组: _二维码请在 CORE QQ 群里询问_

## 我们的历史

我们成立于 2016 年年中，原先名为「.NET Core 中文学习组（.NET Core China Studying Group）」，并在同一时间创建了我们的 QQ 群组「dotNET Core Studying Group」，且至今未更名。

NCC 最初的目标是翻译微软 ASP.NET Core（时名 ASP.NET 5）的官方文档。我们得到了许多人的帮助和鼓励（[2016 年翻译计划贡献者名单](./docs/history/people-who-translated-in-2016.md)），并在 Twitter 上获得了官方的点赞。我们的[翻译成果](https://github.com/dotnetcore/aspnetcore-doc-cn)也为第一批接触 ASP.NET Core 的中文开发者们提供了巨大的便利。

经历两年的挑战和考验，NCC 几经易名，逐渐演变为一个开源社区组织，拥有了十多个成员项目和团队。

在这期间我们得到了许多人和组织的帮助，包括 JetBrains 公司对我们的支持。

2019 年年初，我们尝试与中国各地区 .NET 技术社区合作，联合发起了 [.NET 中文社区联席会议（.NET China Community Joint Meeting, NCJM）](https://github.com/dotnet-china)，并为该社区提供了 NCC 域名资产「dotnet-china.com」，我们则启用了全新域名「[dotnetcore.xyz](https://www.dotnetcore.xyz)」。

2019 年年末，我们通过并正式启用[《组织成员行为准则》](code-of-conduct.zh-CN.md)，由[社区修订与起草工作组（2019）](docs/history/revision-and-drafting-working-group-2019.md)负责修订和起草的四部新规定通过 NCC PMC 的投票，并于 2020 年 1 月 1 日起生效。

2020 年，这个特殊的年份，我们更新了社区规则，并经受住了多重巨大考验，成员项目取得长足发展，Surging 为了更广阔的前景完成了 NCC 的孵化，并成立了独立社区。FlubuCore 成为社区第一个 .NET 基金会成员；晓晨的 Alipay SDK 也完成了全部历史使命，进入归档状态。

2021 年，我们期待社区得到更大的发展。

## 我们的行为准则

为了建设开放、创新、包容和热情的社区，我们制定了[组织成员行为准则](code-of-conduct.zh-CN.md)。

## 仓库与项目

我们的成员项目分为两阶段：_沙盒阶段（NCC Sandbox Projects phase）_ 和 _顶级项目阶段（NCC Top-Level Projects phase）_。当新项目申请加入 NCC 并完成评审和加入前的全部流程（包括预备工作）后，项目将自动进入 _沙盒阶段_。申请加入 NCC 请查阅[如何加入我们](#如何加入我们)一节。

### Data

- **[CanalSharp](https://github.com/dotnetcore/CanalSharp)**，[Alibaba Canal](https://github.com/alibaba/canal) 的开源 .NET 客户端，Alibaba Canal 是一个基于 MySQL `binlog` 的增量发布与订阅组件。更多信息请查阅 [https://github.com/alibaba/canal/wiki](https://github.com/alibaba/canal/wiki)。
- **[DotnetSpider](https://github.com/dotnetcore/DotnetSpider)** *(顶级项目)*，类似 WebMagic 与 Scrapy 的 .NET Standard 轻量级、高效且高速的高级爬虫库。
- **[EasyCaching](https://github.com/dotnetcore/EasyCaching)**，开源缓存库，包含基本用法和缓存的高级用法，可助我们更轻松地处理缓存。
- **[EntityFrameworkCore.GaussDB](https://github.com/dotnetcore/EntityFrameworkCore.GaussDB)** *(incubation)*，华为 GaussDB 的 Entity Framework Core 驱动。
- **[EntityFrameworkCore.KingbaseES](https://github.com/dotnetcore/EntityFrameworkCore.KingbaseES)** *(incubation)*，人大金仓 KingbaseES 的 Entity Framework Core 驱动。
- **[FreeSql](https://github.com/dotnetcore/FreeSql)**，一款功能强大的 ORM 组件，支持 .NET Core、.NET Framework 和 Xamarin。目前 FreeSql 支持以下数据库：[MySQL](https://www.mysql.com)、[PostgreSQL](https://www.postgresql.org/)、[SqlServer](https://www.microsoft.com/en-us/sql-server/)、[Oracle](https://www.oracle.com/database/)、[Sqlite](https://www.sqlite.org)、[Firebird](https://firebirdsql.org/)、[ODBC](https://baike.baidu.com/item/%E5%BC%80%E6%94%BE%E6%95%B0%E6%8D%AE%E5%BA%93%E4%BA%92%E8%BF%9E/10418782)、[微软 Access](https://www.microsoft.com/en-us/microsoft-365/access) 以及国产数据库[达梦](http://www.dameng.com/)、[人大金仓](https://www.kingbase.com.cn/)、[神通](http://www.shentongdata.com/)、[瀚高](http://www.highgo.com/content.php?catid=40)、[华为 GaussDB](https://e.huawei.com/cn/products/cloud-computing-dc/gaussdb)。
- **[Magicodes Exporter and Importer](https://github.com/dotnetcore/Magicodes.IE)**，导入导出通用库，支持 Excel、Word、PDF 与 HTML。
- **[NPOI](https://github.com/dotnetcore/NPOI)** *([已存档，查看**存档通告**](https://github.com/dotnetcore/NPOI/blob/master/README.zh-CN.md))*，用于读写 Microsoft Office 二进制文件和 OOXML 文件格式的 .NET 类库。
- **[ShardingCore](https://github.com/dotnetcore/sharding-core)**，一款 EFCore 下高性能、轻量级针对分表分库读写分离的解决方案，具有零依赖、零学习成本、零业务代码入侵。
- **[SmartCode](https://github.com/dotnetcore/SmartCode)**，优秀的开源代码生成器（不仅仅是生成代码），它基于执行流程，支持 ETL 模式，高度灵活和可扩展，还支持自定义模板和多种模板样式，以及多种数据库。
- **[SmartSql](https://github.com/dotnetcore/SmartSql)**，通过简单的连接字符串来运行，解析 SQL 的 XML 配置和各种性能观察方法，使性能问题一目了然。 SmartSql 具有与 Dapper 相似的性能水平，并提供许多特性：动态代理存储、分布式缓存、类型处理器、自动生成 CUD 代码、分布式 Id 生成器、性能诊断、AOP 级别的事务/缓存（内存，分布式缓存）、读/写分离、代码生成器、高性能的批量插入等。

### Application Library

- **[AspectCore](https://github.com/dotnetcore/AspectCore-Framework)** *(顶级项目)*，.NET Standard 跨平台 AOP 框架。
- **[Natasha](https://github.com/dotnetcore/Natasha)**，简化 IL 操作，优化 IL 编程流程，并编写具有高性能的动态缓存。
  - [Natasha Docs](https://github.com/dotnetcore/Natasha.Docs)，Natasha 的文档项目。
- **[NCC Collection Extensions](https://github.com/dotnetcore/Collections)**，包括分页组件在内的集合扩展。
- **[WebApiClient](https://github.com/dotnetcore/WebApiClient)**，基于 HttpClient 的开源项目，只需通过定义 C# 接口并修改一些细节便可异步调用远程 HTTP 接口。
  - [WebApiClient Core](https://github.com/dotnetcore/WebApiClient) - .NET Core 版本的 WebApiClient, 集高性能高可扩展性于一体的声明式 HTTP 客户端库，特别适用于微服务的 RESTful 资源请求，也适用于各种畸形 HTTP 接口请求。
  - [WebApiClient.JIT/AOT](https://github.com/dotnetcore/WebApiClient/tree/WebApiClient.JITAOT) - 一款声明式的 HTTP 客户端库，只需要定义 C# 接口并修饰相关特性，即可异步调用远程 HTTP 接口。
  - [WebApiClient.Extensions](https://github.com/xljiulang/WebApiClient.Extensions) - **WebApiClient.JIT 扩展**, 包括对 [Autofac](https://github.com/autofac/Autofac), [DependencyInjection](https://github.com/aspnet/DependencyInjection), [HttpClientFactory](https://github.com/aspnet/HttpClientFactory), [SteeltoeOSS.Discovery](https://github.com/SteeltoeOSS/Discovery), [MessagePack](https://github.com/neuecc/MessagePack-CSharp), [Protobuf](https://github.com/mgravell/protobuf-net) 和 [Json-Rpc](https://www.jsonrpc.org/specification) 的扩展。
  - [WebApiClient.Tools](https://github.com/xljiulang/WebApiClient.Tools) - **WebApiClient.JI 工具集T**, 包括 [Swagger](https://github.com/domaindrivendev/Swashbuckle.WebApi) 工具。

### Development Framework

- **[OSharp](https://github.com/dotnetcore/OSharp)**，全称 OSharp Framework with .NetStandard2.x，是一个基于 .NetStandard2.x 开发的一个 .NetCore 快速开发框架。这个框架使用最新稳定版的 .NetCore SDK（当前是.NET Core 3.1），对 AspNetCore 的配置、依赖注入、日志、缓存、实体框架、Mvc(WebApi)、身份认证、权限授权等模块进行更高一级的自动化封装，并规范了一套业务实现的代码结构与操作流程，使 .Net Core 框架更易于应用到实际项目开发中。
- **[Util](https://github.com/dotnetcore/Util)**，.NET Core 平台下的开源应用程序，旨在提高小型团队的开发效率。 它由通用帮助程序，分层体系结构设计，UI 组件，第三方组件和服务接口包组成。
- **[WTM](https://github.com/dotnetcore/WTM)**，针对中小规模后台管理系统的开发利器，基于 .NET Core，实现零编码创建项目、零编码生成业务模块。框架严格遵循 MVVM 的开发模式，经过数十个真实项目检测，可以极大提高开发效率，降低开发成本。

### Environment & Tools

- **[Alipay SDK](https://github.com/dotnetcore/Alipay.AopSdk.Core)** *(已存档)*，基于 .NET Standard 2.0 开发的第三方支付宝服务端 SDK，提供比官方更可靠的设计，但仍与官方 APIs 保持一致。
- **[FastGithub](https://github.com/dotnetcore/FastGithub)**，GitHub 加速神器，解决 GitHub 打不开、用户头像无法加载、`releases` 无法上传下载、`git-clone` `git-pull` `git-push` 失败等问题。
- **[FlubuCore](https://github.com/dotnetcore/FlubuCore)** *(顶级项目)*，跨平台构建与部署自动化系统，基于 C# 代码构建项目和执行部署脚本。（[FlubuCore 的示例](https://github.com/dotnetcore/FlubuCore.Examples)）
  - [FlubuCore.CakePlugin](https://github.com/flubu-core/FlubuCore.CakePlugin) - Cake 插件。
  - [FlubuCore.TeamsPlugin](https://github.com/flubu-core/FlubuCore.TeamsPlugin) - Microsoft Teams 插件。
- **[KoobooJson](https://github.com/kooboo/Json)** *(外部项目)*，更小更快的 C# JSON 序列化工具（基于表达式树构建）。
- **[NCC Compile Environment](https://github.com/dotnetcore/Compile.Environment)**，使用 Roslyn 库进行动态编译时，可以引入该库提供动态编译的环境。

### Infra & Middleware

- **[AgileConfig](https://github.com/dotnetcore/AgileConfig)**, 一个基于.NET Core 的轻量级配置中心。
  - [AgileConfig Client](https://github.com/kklldog/AgileConfig_Client) - AgileConfig 客户端程序，基于 .NET Standard 2.0 开发，故能运行于 nfx 和 core 应用中。
- **[CAP](https://github.com/dotnetcore/CAP)** *(顶级项目)*，基于最终一致性的微服务分布式事务解决方案，具有 Outbox 模式的事件总线。
- **[HttpReports](https://github.com/dotnetcore/HttpReports)**, 是一款基于 .NET Core 的轻量级 APM 系统，可在 .NET Core 环境下快速搭建统计、分析、图标、监控和分布式跟踪一体化的站点，适用于 ASP.NET Core MVC/WebAPI。HttpReports 上手简单，适合在微服务中使用。
- **[Mocha](https://github.com/dotnetcore/mocha)** *(incubation)*，一款基于[OpenTelemetry](https://opentelemetry.io/) 的应用程序性能监控工具，为可观测性数据分析和存储提供了可扩展的平台。

### UI 组件

- **[BootstrapBlazor](https://github.com/dotnetcore/BootstrapBlazor)**, 基于 Bootstrap 的 Blazor 企业级 UI 组件库。

### 翻译项目

- **[ASP.NET Core 文档翻译计划](https://github.com/dotnetcore/aspnetcore-doc-cn)**，由 .NET China Foundation（已更名为 NCC）发起的微软 ASP.NET Core 文档翻译计划。

### 已完成孵化的项目

- **BotSharp**，开源的 AI 聊天机器人构建平台。
- **Surging**，分布式微服务引擎。
- **ZKWeb**，一个灵活的带有插件系统和模板系统框架。

想加入我们么？下一个 NCC 成员项目非你莫属！[下一节](#如何加入我们)将介绍如何加入我们。

## 如何加入我们

- 项目要求：[关于申请加入 NCC 的项目的规定（Community Project Accession Reg, 2020）](./docs/rules/community-project-accession-reg-2020.md)
- 加入步骤：[project-steps-for-joining-ncc.md](./docs/rules/project-steps-for-joining-ncc.md) _该规定将进行修订_

## 财资管理

### 捐赠

<img height=200 src="./img/ncc-donation-qrcode.png" title="扫码，并赞助我们"/>

When you donate, **PLEASE TELL US YOUR NAME AND TO MARK "NCC"**, thank you.

当你捐赠时，**请标注「NCC」，并留下你的名字**，万分感激。

资金将由 LIU Haoyang 托管，并由 Alex Lewis 登记造册。

**万分感谢您的捐赠**

## 商业与政治相关的排除性规定

- [社区商业阻隔条例（Community Commercial Barriers Reg, 2020）](./docs/rules/community-commercial-barriers-reg-2020.md)
- [社区政治阻隔条例（Community Political Barriers Reg, 2020）](./docs/rules/community-political-barriers-reg-2020.md)

## 社区合作伙伴和赞助商

<a href="https://www.jetbrains.com/?from=.NETCoreCommunity(NCC)" target="_blank">
<img src="./img/jetbrains.png" title="JetBrains" width=130 />
</a>
<span>&nbsp;&nbsp;&nbsp;&nbsp;</span>
<a href="https://www.myget.org/" target="_blank">
<img src="./img/myget.png" title="MyGet" width=130 />
</a>
<span>&nbsp;&nbsp;&nbsp;&nbsp;</span>
<a href="https://www.oreilly.com/pub/cpc/323206" target="_blank">
<img src="./img/oreilly.png" title="O'REILLY" width=130 />
</a>
<span>&nbsp;&nbsp;&nbsp;&nbsp;</span>
<a href="https://www.material-theme.com/" target="_blank">
<img src="./img/material-theme.png" title="Material Theme UI Plugin for JetBrains" width=130 />
</a>

## 微信公众号

在 2019 年，我出门创建了 NCC 社区微信公众号「NCC 开源社区」，欢迎诸位订阅。

<img height=200 src="./img/OpenNCC.jpg" title="扫码并关注"/>

NCC 微信公众号内的广告所得将用于公众号的日常运营、社区活动和支付稿酬。

## 反馈

<a href="https://dotnetcore.xyz"><img src="./img/ncc-badge-blue.png" width="300" height="360" align="right" /></a>

- 在使用 [NCC 成员项目](#仓库与项目)遇到问题，请到相应项目下提交 issue；
- 对 NCC 的建议和意见，可以[在此创建 issue](https://github.com/dotnetcore/Home/issues/new)，与我们取得联系；
- 以下方式都是可以接受的：
  - 在我们微信公众号的后台留言：OpenNCC；
  - 关注我们的推特：[@ncc_community](https://twitter.com/ncc_community)
  - 关注我们的电报频道：[@ncc_radio](https://t.me/nccradio)
- 最后，你可以通过邮件与我们取得联系：`dotnet-community#outlook.com` （将 `#` 改为 `@`）
