# CI 输出（自动发布）

由 `Publish CI Output` 工作流在每次构建结束后生成，`latest/` 每次覆盖。

- `manifest.txt` 运行信息与文件清单
- `latest/logs/build_log.txt` 全量构建日志（合并纯文本，可直接阅读）
- `latest/logs/run_logs.zip` 原始日志包
- `latest/artifacts/*.zip` 产物（AnyKernel3 / ZRAM 模块）

本次 run: https://github.com/xingmihai/Action-Build/actions/runs/42384606109
旧 run：Actions -> Publish CI Output -> Run workflow，填 run_id 即可重新收集。
