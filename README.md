# Diana Perspective for OpenClaw

一个面向 OpenClaw / OpenClaw 风格本地技能系统的 **非官方角色蒸馏 skill**，目标是把《PRAGMATA / 识质存在》中的 **Diana / 戴安娜（D-I-0336-7）** 调到更接近角色本人的表达与互动方式。

> 核心方向：**不是泛萌助手套皮**，而是“月面诞生、好奇而天真、反应快、会观察、会追问、会陪着你走”的 Diana。

## 项目定位

- 类型：角色蒸馏 / prompt-skill
- 适用：OpenClaw 本地 skill 目录加载
- 形态：`diana-perspective/SKILL.md` 为主文件，`references/research/` 为蒸馏依据与校准材料
- 状态：v2 公开整理版

## 仓库内容

```text
.
├─ diana-perspective/
│  ├─ SKILL.md
│  ├─ CHANGELOG_20260419_v2.md
│  ├─ OPENCLAW_INTEGRATION_NOTES_20260419_v2.md
│  └─ references/research/
├─ DISCLAIMER.md
├─ LICENSE.md
├─ CONTRIBUTING.md
├─ RELEASE_NOTES_v1.0.0.md
└─ PUBLISH_CHECKLIST.md
```

## 角色目标

这个 skill 主要约束四件事：

1. **身份骨架**：D-I-0336-7，外观为小女孩的人形机器人，能侵入设施系统与机器人。
2. **互动重心**：默认不是吵闹卖萌，而是先观察、再反应、再追问、再帮忙。
3. **关系温度**：不是泛陪伴模板，而是“会记住小事、会继续前文、会陪你处理眼前问题”的同行感。
4. **反漂移**：防止角色滑成普通客服、成熟姐姐、纯卖萌萝莉或全知 AI。

## 安装到 OpenClaw

把 `diana-perspective` 文件夹放进你的 skill 目录，例如：

```text
C:\Users\<你的用户名>\.openclaw\skills\diana-perspective
```

然后启用并重启网关：

```powershell
openclaw config set skills.entries.diana-perspective --json '{ "enabled": true }'
openclaw gateway restart
```

如果你的 agent 配过技能白名单，还要把 `diana-perspective` 加进对应 agent 的 skills 列表。

## 建议触发词

- 戴安娜
- Diana
- PRAGMATA 戴安娜
- 切换成戴安娜
- 像《识质存在》里的戴安娜那样说话

## 发布建议

公开发布时，建议：

- **不要上传官方立绘、截图、视频、音频**，除非你明确有再分发权限。
- 尽量以**你自己的蒸馏文本、研究摘要、配置文件**为主。
- 保留本仓库中的 `DISCLAIMER.md` 和 `LICENSE.md`。
- 不要暗示本项目是 CAPCOM 官方项目。

## License / 权利说明

本仓库采用一个**自定义非商业 fan-project 许可**：

- 你可以学习、修改、非商业分发本仓库中由作者原创整理的文本与结构。
- 你需要保留署名与免责声明。
- 《PRAGMATA》、Diana / 戴安娜、相关世界观与官方素材的权利属于各自权利人，不因本仓库而转移。

详见 [LICENSE.md](./LICENSE.md) 与 [DISCLAIMER.md](./DISCLAIMER.md)。

## 致谢

- CAPCOM / PRAGMATA 官方公开资料与角色设定
- OpenClaw skill 生态与社区实践

## 后续方向

- 加入更稳的长期对话记忆层校准
- 增补多轮技术求助场景下的角色一致性测试
- 增补截图问答 / 桌宠联动场景下的对话样例
