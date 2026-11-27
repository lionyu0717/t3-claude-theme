# T3–Claude

**中文** | [English](#english)

把 **Claude Code 老桌面版** 的温暖感觉带回 T3 Code。

Claude 改版之后，很多人怀念原来那种暖色调、纸一样质感的使用体验——这个主题就是照着老版本复刻的：暖纸底色、衬线正文、圆润的输入框，还有一只更活泼的像素小 Clawd，趴在输入框上方陪你工作（待机、东张西望、招手、跳跃、撒花）。

## 安装（完整版）

主题是两个文件：`t3-claude.json`（配色、字体、动画）和 `t3-claude.png`（小 Clawd 像素帧）。**只装 json 也能用，但不会有小 Clawd。**

1. 从 [Releases](../../releases) 下载 `t3-claude.json`
2. 打开 T3 Code → **Settings → Appearance → Import theme file**，选择下载的文件
3. 再下载 `t3-claude.png`，放进 T3 的主题目录，和 `t3-claude.json` 放在一起：
   - macOS：`~/.t3/userdata/themes/`
   - Windows：`%USERPROFILE%\\.t3\\userdata\\themes`
   - Linux：`~/.t3/userdata/themes/`
4. 在主题列表里选择 **T3–Claude**（看不到小 Clawd 就切换一下主题或重启 T3）

## 包含什么

- 老 Claude 桌面版的暖纸色板（浅色 / 深色两套）
- 对话与输入框使用 Anthropic Serif（字体已内嵌，无需安装），界面使用 Georgia
- 复刻老版的输入框与发送按钮：打字时变成回车符号 ↵，悬停浮现陶土色
- 输入框上方的像素小 Clawd：待机、挥手、跳跃、撒花，还会沿着输入框**散步**（脚步与位移同步，纯 CSS 实现）
- 发送 / steering / 排队 / 停止按钮统一为 Clawd 陶土色 `#d97757`

## 关于 Open VSX 精简版

`openvsx/` 里是**仅配色**的精简版（VS Code 扩展格式），方便在 T3 的 Settings → Appearance → 社区主题搜索里直接安装。受格式限制，它不含字体、输入框样式和小 Clawd——完整体验请使用上面的主题文件。

## 说明

- 小 Clawd 的原始素材与动作数据来自 Claude Code 桌面版的 Clawd's Quest，仅供学习交流
- 本主题与 Anthropic 无关，仅为粉丝作品

## License

MIT（主题代码）；Clawd 像素素材版权归 Anthropic 所有

---

# English

Brings back the warm feel of the **old Claude Code desktop app** to T3 Code.

After Claude's redesign, many people missed the warm, paper-like experience of the original. This theme recreates it: warm paper palette, serif conversation text, a rounded composer, and a livelier pixel Clawd living above the input box (idling, looking around, waving, jumping, celebrating).

## Install (full version)

The theme is two files: `t3-claude.json` (colors, fonts, animation) and `t3-claude.png` (the Clawd sprite sheet). **The JSON alone works, but there will be no Clawd.**

1. Download `t3-claude.json` from [Releases](../../releases)
2. In T3 Code, open **Settings → Appearance → Import theme file** and pick the file
3. Also download `t3-claude.png` and place it in T3's themes directory, next to `t3-claude.json`:
   - macOS / Linux: `~/.t3/userdata/themes/`
   - Windows: `%USERPROFILE%\\.t3\\userdata\\themes`
4. Select **T3–Claude** in the theme list (if the Clawd doesn't show, switch themes or restart T3)

## What's inside

- The old Claude desktop warm palette (light & dark)
- Anthropic Serif for conversation and composer (embedded, no install needed), Georgia for the interface
- The old-style composer and send button: a return symbol ↵ while typing, clay on hover
- A pixel Clawd above the composer with its full set of original ambient actions — it even takes a little walk along the composer (footsteps synced to movement, pure CSS)
- Send / steer / queue / stop buttons unified in Clawd clay `#d97757`

## Open VSX lite version

`openvsx/` holds a **colors-only** build (VS Code extension format) for one-click install from T3's community theme search. The format can't carry fonts, composer styling, or the Clawd — use the theme file above for the full experience.

## Notes

- Clawd's pixel art and motion data come from Claude Code desktop's Clawd's Quest, shared for learning purposes
- Unofficial fan work, not affiliated with Anthropic

## License

MIT (theme code); Clawd pixel art © Anthropic
