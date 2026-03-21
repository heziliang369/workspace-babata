# MEMORY.md - 长期记忆库

### 2026-03-20
- 用户偏好：对多步骤任务（如批量删除、同步等）一次性全部执行，不需要每一步单独确认。

### 2026-03-21 - 飞书 Bitable 写入
- 飞书表格 app_token: `I25LbIr8daHDyCsYy7ncNUasnxg`
- 表格 ID: `tblWvjtSoLHw1JxZ` (数据表)
- 字段：文本、单选、日期、附件
- 使用 field_name 作为字段键写入，而非 field_id

### 2026-03-20 - 发送图片消息经验
- 步骤a：将图片复制到 Feishu 允许的媒体目录：`mkdir -p ~/.openclaw/media && cp /Users/aaron/.openclaw/workspace-main/baidu-zhangzhou.png ~/.openclaw/media/`
- 步骤b：使用正确的 OpenID 发送图片：`openclaw message send --channel feishu --target ou_125393c318cd2b0a4716dc417cec5794 --media ~/.openclaw/media/baidu-zhangzhou.png --message "图片预览"`
- 要点：必须使用完整的 OpenID（ou_...），否则报 400 错误；文件必须位于 Feishu 允许的媒体目录 (~/.openclaw/media/) 才能以图片预览形式展示。

### 2026-03-22 - 学习存储路径更新
- 学习经验及错误日志统一存放于 `~/.openclaw/workspace/.learnings` 文件夹，供后续查询及记录。


- Obsidian 的默认 vault 路径在 macOS 上通常是 `~/Documents/Obsidian`（除非在设置中自定义）。


- 公司信息文档已更新，路径为 `/Users/aaron/Documents/Obsidian Vault/Company/Info.md`


- **学习经验存放路径**: `～/.openclaw/workspace/.learnings`


- **公司:** 云珩科技
## 同事

---
- **灵汐** - CEO
- **贾维斯** - CTO
- **巴巴塔(我)** - CFO

---

_持续更新..._