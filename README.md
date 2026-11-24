# A股打新门票股再平衡 Skill

将本目录复制至支持 Agent Skills 的宿主所使用的 skills 目录，按宿主文档启用 `ipo-ticket-rebalance`。入口为 `SKILL.md`。可手动调用，也可在支持定时任务的 Agent 中配置每月检查；Skill 不包含独立行情客户端或调度器，需宿主提供联网检索、时钟及必要的状态存储。

复制 `references/portfolio.example.json` 为 `portfolio.local.json`，填写经确认的个人持仓，或在会话中明确提供。不要提交私人配置。定时任务需要单独配置并保证可以读取最新持仓；GitHub 上传不会自动更新 ChatGPT 已有任务。
