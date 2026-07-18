## IronMind
# 漫漫铁锈路 开服第亿步

</div>

> [!注意]
> 此端以及其文档目前未经完善，会有大量的bug以及不可名状的事情出现。距离正式版还有很大的距离。目前尽量不要用 Eve

A Rukkit fork focused on vanilla mechanics, extensibility, and configurability.

IronMind 是 [Rukkit](https://github.com/RukkitDev/Rukkit) 的一个分支，
致力于在 Rusted Warfare（铁锈战争）服务端中**还原如同[Leafmc](https://github.com/Winds-Studio/Leaf)般流畅开服体验**。
通过移植来自 [RW-HPS](https://github.com/deng-rui/RW-HPS) 的 AI 引擎，
IronMind 让 Rukkit 服务端也能运行完整的建造、生产、进攻逻辑，使 AI 不再是“木桩”。
通过豆包,TraeAI,DeepSeek的强力驱动。
完成Rukkit服务端的高度可配置
支持http代理
支持 上列表..?(未完善，需要插件支持)

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
  我们将持续推动该项目的崭新，为了平民玩家也能自开自给自足。

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

## 🙏 致谢
[RukkitDev Team](https://github.com/RukkitDev/Rukkit) — 原始服务端框架
[RW-HPS](https://github.com/LuoBoLong/RW-HPS) — RW-HPS 的 AI 实现
Rusted Warfare 社区 — 逆向分析与测试支持

## ⚠️ 注意事项
本项目非官方，与 Corroding Games 无关。
仅用于个人学习和研究。
修改后的代码必须遵循 AGPL v3 协议开源。
