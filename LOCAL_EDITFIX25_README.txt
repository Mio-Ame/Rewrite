修复25：日志分类完整包
在修复24基础上，仅调整运行日志展示分类。
明确标记dryRun=true或reason=dry-run的generation-start-ignored事件单列为“试运行已忽略”。其余不能归组的事件显示为“历史记录缺少归属信息”。各组沿用原有复制本组按钮。
不补猜历史归属，不改生成、请求、存储及AI上下文流程。累计保留修复24功能；覆盖现有目录后刷新，不用更换预设或API配置。
本轮13项日志检查通过，包含分类、时间、顺序、原始记录保留和AI请求分组。未重跑完整平台回归。GitHub未更新。
原作者：Veridis / The-Veridis-Lion
原项目：https://github.com/The-Veridis-Lion/Veridis-Rewrite
原发布：https://discord.com/channels/1134557553011998840/1488671923776000020
保留原README许可和版权署名，仅按原许可允许的非商业用途使用。旧LOCAL文件为历史说明，以本文件为准。
