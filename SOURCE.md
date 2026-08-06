# Source — 原文出处与蒸馏元信息

## 原视频

| 字段 | 值 |
|---|---|
| 标题 | 3 分钟教会你从 0 到 1 找到属于自己的生意 |
| 作者 / 账号 | dontbesilent 聊赚钱 |
| 平台 | 抖音 |
| 链接 | https://v.douyin.com/P7jVmDtgK8Q/ |
| 视频 ID | 7645897962001845542 |
| 时长 | 452.97 秒（≈ 7'33"） |
| 分辨率 | 1920×1440 |
| 原作者简介 | 抖音/小红书博主，2024 年首次发布此方法时，小红书两天半涨粉 1 万 |
| 抓取日期 | 2026-08-06 |

## 转录

- **ASR 后端**：SiliconFlow `FunAudioLLM/SenseVoiceSmall`
- **转录字数**：3644 字
- **原始文件**：`downloads/douyin-7645897962001845542/transcript.txt`（本地）
- **完整转录亦以真·ima 笔记形态入库到 01 资料库**

## 蒸馏

- **方法论框架**：cangjie-skill 7 阶段流水线
- **降级方案**：原文仅 3.6K 字，5 类 extractor 串行执行（非并行 sub-agent）
- **阶段 4 压测**：轻量化——诱饵/边界测试嵌入各 skill 的 B 段 + darwin-skill 兼容 `test-prompts.json`
- **原方法论根**：benchmarking / 基准测试，源自施乐公司上世纪七八十年代

## 蒸馏产物

- **本地审计目录**：`books/benchmark-table-method/`（PIPELINE_STATE / BOOK_OVERVIEW / candidates / verified / 5 个 SKILL.md / INDEX / GLOSSARY / DIGEST）
- **03 输出库沉淀**：单笔记《表格工作法找生意 · 完整沉淀》（note_ / media_type=11）
- **公开发布**：本仓库
- **WorkBuddy 本地安装**：`~/.workbuddy/skills/{benchmark-table-method, find-benchmarks-on-content-platforms, estimate-competitor-revenue, subjective-difficulty-scoring, product-traffic-match}/`