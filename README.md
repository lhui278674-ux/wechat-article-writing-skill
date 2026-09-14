# 公众号文章创作 Skill

这是一个面向中文微信公众号文章创作的 Codex Skill 项目。仓库只保留最新版 Skill 本体和必要说明文件，便于安装、同步和持续更新。

## 项目结构

- `wechat-article-writing/`：最新版、可安装的 Skill 本体；入口文件为 `SKILL.md`。
- `README.md`：仓库说明和更新方法。
- `.gitignore`：本地缓存及敏感文件排除规则。

完整的安装方法、能力边界和使用示例见 [`wechat-article-writing/README.md`](wechat-article-writing/README.md)。

评测记录、历史快照和本地文章素材不纳入版本控制，避免旧版本或私密内容被意外上传。

## 更新仓库

修改文件后，在本项目目录运行：

```powershell
git status
git add .
git commit -m "描述本次修改"
git push
```

提交前请确认没有把账号信息、访问令牌、私密素材或其他敏感文件加入版本控制。
