# T3–Claude

**中文** | [English](#english)

把 **Claude Code 老桌面版** 的温暖感觉带回 T3 Code。

Claude 改版之后，很多人怀念原来那种暖色调、纸一样质感的使用体验——这个主题就是照着老版本复刻的：暖纸底色、衬线正文、圆润的输入框，还有一只更活泼的像素小 Clawd，趴在输入框上方陪你工作（待机、张望、思考、跳舞、招手、撒花，还会沿着输入框巡逻）。

## 安装（完整版）

**只需要一个文件**：`t3-claude.json` 已内嵌字体和小 Clawd 雪碧图，下载后直接导入即可，不需要手动复制 png。

1. 从 [Releases](../../releases) 下载 `t3-claude.json`
2. 打开 T3 Code → **Settings → Appearance → Import theme file**，选择下载的文件
3. 在主题列表里选择 **T3–Claude**（看不到小 Clawd 就切换一下主题或重启 T3）

Release 同时附带 `t3-claude.png`，仅供旧版 T3 或需要外部背景图的用户使用；当前版本不必安装它。

## 包含什么

- 老 Claude 桌面版的暖纸色板（浅色 / 深色两套）
- 对话与输入框使用 Anthropic Serif（字体已内嵌，无需安装），界面使用 Georgia
- 复刻老版的输入框与发送按钮：打字时变成回车符号 ↵，悬停浮现陶土色
- 输入框上方的像素小 Clawd：响应式多路点巡逻，Agent 工作时换成跑步，悬停原地招手，按下活动区撒花，按下发送时兴奋，中途还会思考和跳舞（脚步与位移同步，纯 CSS 实现）
- 发送 / steering / 排队 / 停止按钮统一为 Clawd 陶土色 `#d97757`

## 关于 Open VSX 精简版

`openvsx/` 里是**仅配色**的精简版（VS Code 扩展格式），方便在 T3 的 Settings → Appearance → 社区主题搜索里直接安装。受格式限制，它不含字体、输入框样式和小 Clawd——完整体验请使用上面的主题文件。

## 说明

- 小 Clawd 的原始素材与动作数据来自 Claude Code 桌面版的 Clawd's Quest，仅供学习交流
- 主题交互是纯 CSS 实现：悬停/按下反应以输入框上方的活动区域为单位；精确像素命中和视线跟随仍保留在可选的预览 runtime
- 本主题与 Anthropic 无关，仅为粉丝作品

## License

MIT（主题代码）；Clawd 像素素材版权归 Anthropic 所有

---

# English

Brings back the warm feel of the **old Claude Code desktop app** to T3 Code.

After Claude's redesign, many people missed the warm, paper-like experience of the original. This theme recreates it: warm paper palette, serif conversation text, a rounded composer, and a livelier pixel Clawd living above the input box (idling, looking around, thinking, dancing, waving, celebrating, and taking a responsive patrol).

## Install (full version)

**One file is enough**: `t3-claude.json` embeds the fonts and Clawd sprite sheet. Download and import it directly — no manual PNG copy required.

1. Download `t3-claude.json` from [Releases](../../releases)
2. In T3 Code, open **Settings → Appearance → Import theme file** and pick the file
3. Select **T3–Claude** in the theme list (if the Clawd doesn't show, switch themes or restart T3)

The release also includes `t3-claude.png` for older T3 builds or users who prefer an external background file; it is not needed by the current package.

## What's inside

- The old Claude desktop warm palette (light & dark)
- Anthropic Serif for conversation and composer (embedded, no install needed), Georgia for the interface
- The old-style composer and send button: a return symbol ↵ while typing, clay on hover
- A pixel Clawd above the composer with a responsive multi-stop patrol, running gait while the agent works, and in-place reactions (hover to wave, press to celebrate or react to send, thinking, dancing)
- Send / steer / queue / stop buttons unified in Clawd clay `#d97757`

## Open VSX lite version

`openvsx/` holds a **colors-only** build (VS Code extension format) for one-click install from T3's community theme search. The format can't carry fonts, composer styling, or the Clawd — use the theme file above for the full experience.

## Notes

- Clawd's pixel art and motion data come from Claude Code desktop's Clawd's Quest, shared for learning purposes
- The theme's interactions are CSS-only: hover/active reactions are lane-level, while exact pixel hit testing and gaze tracking remain in the optional preview runtime
- Unofficial fan work, not affiliated with Anthropic

## License

MIT (theme code); Clawd pixel art © Anthropic
