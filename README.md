# AI Studio（免费工具工作室 · 总控仓）

把一批免费基础设施拧成一个能干活的工作室，这个仓库是 GitHub Actions 自动化任务的家。

## 查看工作室状态

在 **Actions → studio-check → Run workflow** 可以手动检查。定时任务设为每周一 01:14 UTC（北京时间 09:14）。运行成功后可从 `studio-status` 下载 `status.txt`，查看 GitHub Actions 执行环境检查结果、UTC 时间和 Git 版本。运行日志还记录系统、Python、磁盘和内存。报告中的 `external_services=not_checked` 表示该工作流没有探测下表的服务。

## 服务接入记录与计划

以下为作者的接入记录与待办。免费额度和账户条件以服务商文档及账户页面为准。

| 成员 | 角色 | 状态 |
|---|---|---|
| GitHub Actions | 自动执行任务（定时/触发） | 已有手动成功记录，已配置每周运行 |
| Simular Box | AI 专属云电脑 | ✅ 已接入助手矩阵 |
| Cloady | 免费容器 | ✅ 已部署应用 |
| OpenRouter | [免费模型 API](https://openrouter.ai/collections/free-models) | ✅ 已在助手矩阵 |
| Kaggle | [GPU 笔记本](https://www.kaggle.com/docs/notebooks) | ⏸ 账号已注册，待身份验证 |
| Supabase | [数据库](https://supabase.com/docs/guides/platform/billing-faq) | ⬜ 待注册 |
| Cloudflare Workers | [轻量服务部署](https://developers.cloudflare.com/workers/platform/pricing/) | ⬜ 待注册 |
| Cloudflare R2 | [文件存储](https://developers.cloudflare.com/r2/pricing/) | ⬜ 待定 |
| Google Colab | 免费 GPU | ⬜ 需本人 Google 登录，不承诺时长 |
| Sakupa | 静态托管 | ❌ 已放弃，计划改用 Cloudflare Pages |

作者：王硕凡（Fan-Fan-F）
