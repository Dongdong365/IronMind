## IronMind
# 漫漫铁锈路 开服第亿步

</div>

> [!注意]
> 我们找到了引擎入口 GameEe，但从代码片段看，引擎的初始化依赖于 RW-HPS 的完整网络框架（HessMain），直接移植到 Rukkit 相当于重写一个 RW-HPS。本项目关闭，于此公式。 Eve

> A Rukkit fork focused on vanilla mechanics, extensibility, and configurability.
> 基于 Rukkit 的分支，专注原版游戏机制、可拓展性与高度自定义配置。
> 铁锈战争第三方独立服务端 | Custom Rusted Warfare Server

IronMind 是 Rukkit 的衍生分支，目标为铁锈战争服务端打造类似 [Leafmc](https://github.com/Winds-Studio/Leaf) 流畅易用的开服体验。

本项目移植并参考 RW-HPS 的 AI 引擎（`AddAI` / `GameEe` / `AbstractGameModule` 实现），让原生 Rukkit 服务端拥有完整建造、生产、战术进攻逻辑，解决原版AI“木桩”问题。

完成Rukkit服务端的高度可配置

支持http代理

支持 上列表..?(未完善，需插件支持)

## ✨ 特性

- **原版级 AI**  
  服务端直接运行 AI 决策循环，AI 会自动建造基地、采集资源、生产单位、编队进攻，无需依赖客户端房主。

- **完全可扩展**  
  保留 Rukkit 插件体系，任何Rukkit插件在IronMind都能加载。制作一系列的拓展 API，可以搭配 IronMind 的 插件一起使用。
</div>

> [!注意]
> 因为IronMind在Rukkit的基础上改动调整。所以Rukkit的大部分插件可以使用，但IronMind的大部分插件不能在Rukkit使用。 Eve
- **支持http代理**
  可以与云服务器搭配使用，极端情况下可以与部分免费云服供应商搭配。具体教程蓄势待发。

- **一直维护**  
  我们将持续推动该项目的崭新，为了各种玩家也能“自开自给自足”。

- **AGPL v3 开源**  
  继承上游许可证，所有修改保持开放。


## 🚀 快速开始

1. 下载最新的 `IronMind.jar`（或自行编译）
2. 放入你的 Rusted Warfare 服务器目录
3. 使用以下命令启动：
   ```bash
   java -jar IronMind.jar
## 📖 许可证
IronMind 是 Rukkit 的衍生作品，根据 GNU Affero General Public License v3.0 发布。
完整许可证文本见 LICENSE。
本项目基于 RW-HPS 相关能力整理与扩展。
源代码许可请以发布仓库附带的 LICENSE 文件、源码头部声明以及上游 RW-HPS 许可为准。

上游项目：

RW-HPS: https://github.com/LuoBoLong/RW-HPS
Rukkit：https://github.com/RukkitDev/Rukkit

## 具体模块
AI模块使用以及参考了RW-HPS的设计

## 🙏 致谢
[RukkitDev Team](https://github.com/RukkitDev/Rukkit) — 原始服务端框架
[RW-HPS](https://github.com/LuoBoLong/RW-HPS) — RW-HPS 的 AI 实现
Rusted Warfare 社区 — 逆向分析与测试支持

## ⚠️ 注意事项 及 重要声明
1. 本项目为社区第三方开源服务端，**与 Corroding Games（铁锈战争官方）无任何关联**；
2. 项目源代码遵循 AGPLv3 协议，源代码本身允许商业使用；
3. 但基于原作游戏知识产权限制，**禁止将本项目用于搭建盈利性私服、商业联机服务**，仅可用于学习、研究、非盈利测试；
4. 任何修改、公开部署的衍生版本，依据 AGPLv3 协议要求完整开源。








