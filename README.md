# Y - 个人自动化脚本

自用脚本仓库，主要用于阅读类 App 和部分平台的日常任务自动化。

## 脚本列表

| 文件 | 说明 |
|------|------|
| `youth.js` | 中青阅读 / 中青看点 |
| `qqreads.js` | 企鹅阅读（QQ阅读） |
| `weibo.js` | 微博签到 |
| `Auto_Kuaishou.js` | 快手极速版 |
| `jzread.js` | 其他阅读相关 |
| `jd_Evaluation.py` | 京东评价 |
| `raw_scripts_ttl.js` | 太太乐 |
| `sendNotify.js` | 通用通知推送模块 |

## GitHub Actions

| 工作流 | 说明 |
|--------|------|
| `youth.yml` | 中青看点定时任务（需配置 Secrets） |
| `weibo.yml` | 微博签到（依赖外部仓库脚本） |

运行前需在仓库 **Settings → Secrets** 中配置对应环境变量（如 `YOUTH_HEADER`、`WB_TOKEN`、推送相关 Token 等）。

## 使用说明

- 本仓库为**个人自用**
- 脚本可能依赖 Cookie、Header 或代理工具（Quantumult X / Surge 等）
- 请根据自身环境修改变量后再使用

## 注意事项

- 脚本较旧，平台规则可能已变更，使用前请自行测试
- 请遵守相关平台服务条款，合理使用
- 不提供技术支持

---

*最后整理：2026-11*
