# Skill 收藏馆

> ⭐ **Support This Project**
>
> [![GitHub stars](https://img.shields.io/github/stars/oeaf/awesome-skills?style=social)](https://github.com/oeaf/awesome-skills)
> [![GitHub forks](https://img.shields.io/github/forks/oeaf/awesome-skills?style=social)](https://github.com/oeaf/awesome-skills)
> [![GitHub issues](https://img.shields.io/github/issues/oeaf/awesome-skills)](https://github.com/oeaf/awesome-skills/issues)
>
> 如果这个项目对你有用，欢迎点个 ⭐ Star！你的支持是我持续更新的动力。

收集好用的 skill：每个 skill 附上来源链接和一句话介绍，按大类整理。
以后有新的 skill，直接交给 Muse，她会把链接和介绍补进来。
新手也可以从这里快速找到实用的 skill。

## 目录

- [可视化表达](#可视化表达)
- [艺术与视频动画](#艺术与视频动画)
- [内容创作](#内容创作)
- [效率与自动化](#效率与自动化)
- [开发与工程](#开发与工程)
- [数据与分析](#数据与分析)
- [自研 Skill](#自研-skill)

---

## 可视化表达

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| answer-me-with-html | 把复杂回答变成一页可视化 HTML 讲解页：流程、架构、对比、诊断都可画，也能做讲解视频（2026-10-06 已安装验证） | https://github.com/QingYunA/answer-me-with-html |
| anatomy | 用实物模型讲技术概念的 Agent Skill：生成精美交互式等距插图（SVG + 可选 WebGL 着色器/3D），把抽象概念做成可动可交互的实物；12.8k star，MIT（2026-10-15 收录） | https://github.com/wheresryan22/anatomy |
| diagram-design | 编辑级图表设计 Agent Skill：一句话生成自包含 HTML+SVG 图表（架构/时序/状态机/四象限/桑基/甘特/组织图等 45 种图型），扁平无阴影的杂志排版风、拒绝 Mermaid 糙图；可按品牌配色与字体定制，支持 drawio/Mermaid/Excalidraw 导入、PNG/SVG 导出；59.5k star，MIT（2026-10-21 收录并本地安装） | https://github.com/cathrynlavery/diagram-design |

## 艺术与视频动画

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| hypit | 给 AI Agent 的视频制作语言：丢一段爆款视频进来，Agent 就把整套工作流复刻出来（素材、字幕、B-roll、特效，按词不按秒锚定），一句命令生成 100 个变体；21.3k star，个人自用免费，商用条件见其 License（2026-10-12 已安装验证） | https://github.com/hypit-ai/hypit |
| digital-human-koubo | 数字人口播全流程 Skill：一张照片 + 一句需求出成品口播片——GPT Image 建人设锁一致性、经 Renoise MCP 调 Grok Video 1.5 生成原生说话+口型片段、whisper 回转录对稿质检、Remotion 剪辑渲染；5 种剪辑风格 + 48 个从 25 条头部创作者视频逐帧拆出的包装组件；520 star，MIT（真 Skill，2026-10-26 收录；生成需付费 Renoise 积分、不走 Pavo；仓库建于收录当日、维护待观察；招牌「文字在人物身后」组件仅 macOS；Remotion 另有其协议） | https://github.com/andyhuo520/digital-human-koubo |
| shuohao-skills | AI 短剧制作 skill 集合（7 个）：小说改编排大纲、拆角色、定场景道具、写剧本、排开场走位、切分镜，带脚本化质量门禁，中文优先；4.7k star，Apache-2.0（2026-10-17 收录） | https://github.com/eternityspring/shuohao-skills |
| reelbench-skills | AI 视频拆解与清理工具 skill：成片逐镜头拆解（景别/运镜/节奏作用，15 个质量门禁）、视频与镜头数据对照合成、去元数据重建干净文件；932 star，Apache-2.0（2026-10-18 收录） | https://github.com/eternityspring/reelbench-skills |
| stickman-video-director | 火柴人动画导演 Skill：给 AI 一个话题，产出脚本、动态分镜、配音与音效提示词（再喂 AI 视频生成模型出片）；5 种画风 7 个视觉方案（极简黑白、现代流行红帽子、史前暗黑喜剧、温馨叙事、江户历史卡通），主打 YouTube 解说、TikTok、职场励志与知识短片；2.5k star，MIT（2026-10-21 收录） | https://github.com/kaomei/stickman-video-director |
| Concat | 开源免费的剪映/CapCut 平替（Rust 本地引擎）：多轨时间线剪辑、本地 Whisper 自动字幕、本地 TTS 与声音克隆、抠像、关键帧动画、100 种特效转场、4K 导出，无水印无账号全离线；自带 MCP 服务器与 JSON-RPC 接口，AI Agent 可直接驱动剪辑；10.3k star，AGPL-3.0，beta 0.2.8（2026-10-21 收录） | https://github.com/jub0t/Concat |
| OpenCut | 开源免费的剪映/CapCut 平替（网页版，浏览器打开 opencut.app 即剪）：同品类社区最大；与 Concat 并列收录作选型对比——手动剪辑图省事选它、Agent 自动剪辑选 Concat；注意主仓库正推倒重写（Rust 内核、插件架构，给 Agent 的 MCP 服务器与无头批量渲染在路线图上、尚未发布），当前可用稳定版在 opencut-classic 仓库，官网亦跑该版；95.8k star，MIT（2026-10-23 收录） | https://github.com/opencut-app/opencut |
| MoneyPrinterTurbo | 一站式 AI 短视频生成工具：给主题/关键词，自动写脚本、从 Pexels/Pixabay 等匹配免费库存素材、配音（Edge TTS 免费，另支持 Fish Audio 等）、加字幕与配乐并合成 9:16/16:9/1:1 高清成片，带 WebUI/API/CLI 与批量生成，可自动发 TikTok/IG/YouTube Shorts；与 AI 真生成画面的管线互补，主打低成本无脸号批量出片（脚本需自备 LLM Key）；135.6k star，MIT（工具项目，附 Agent Skill，2026-10-27 收录） | https://github.com/harry0703/MoneyPrinterTurbo |

## 内容创作

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| chinese-novelist-skill | AI 写中文小说：三层问答定大纲、逐章生成 10-50 章完整长篇（3000-5000 字/章），带创作记忆、中断续写、悬念钩子、自动校验重写；3.5k star，MIT（2026-10-14 收录） | https://github.com/PenglongHuang/chinese-novelist-skill |
| LuxTTS | 高质量极速 TTS 语音克隆模型：150 倍实时速度、48kHz 清晰语音，仅需 1GB 显存，CPU 也可实时运行；5.4k star，Apache-2.0（模型，2026-10-14 收录） | https://github.com/ysharma3501/LuxTTS |
| Qwen3-TTS | 阿里通义开源 TTS 模型家族：3 秒声音克隆、文字描述造声（VoiceDesign）、流式生成，支持 10 种语言，0.6B/1.7B 两档；14.0k star，Apache-2.0（模型，2026-10-26 收录，源自 @0x8888 配音清单帖评估） | https://github.com/QwenLM/Qwen3-TTS |
| VibeVoice | 微软开源长音频 TTS 模型：一次生成最长 90 分钟、最多 4 人对话，专攻播客/访谈/有声书，另有 Realtime 流式版与 ASR 版；55.0k star，MIT（模型，需 GPU；官方仓曾因声音克隆滥用短暂下架，现已恢复并加 AI 声明与水印；2026-10-26 收录，源自 @0x8888 配音清单帖评估） | https://github.com/microsoft/VibeVoice |
| InkOS | 故事创作 AI Agent 系统：长短篇小说、剧本剧作、互动影游、IP 内容与多语言翻译，19 个内置专业 Skill（写作/审稿/分镜/翻译），Studio/TUI/CLI 三端；10.3k star，AGPL-3.0（2026-10-14 收录） | https://github.com/Narcooo/inkos |
| Easel | 开源 AI 社媒运营工作台：发现热点→策划选题→创作图文/音频/视频→多平台发布→归因复盘，113 个 skill，账号画像驱动越用越贴合；3.8k star，Apache-2.0（小红书自动发布有风控风险，官方建议人工确认；2026-10-17 收录） | https://github.com/ZJU-REAL/Easel |
| audio-studio-mcp | 本地 AI 音频工作室 MCP Server：在自己 Mac 上用 Stable Audio 3（MLX）一句话生成 BGM/乐器 loop/音效（每次 1-4 个候选），可整体换风格/重绘时间段/续写延长，做无缝循环、响度标准化，导出 WAV/OGG/FLAC；无云服务、无 API Key、生成免费，每个文件带 prompt+seed 的 .json 可复现；86 star，MIT（模型权重适用 Stability AI Community License，个人及年收<100万美元组织可商用，商用前请核实最新条款；仅 Apple Silicon Mac；2026-10-19 收录） | https://github.com/kanaworksai-hue/audio-studio-mcp |
| ai-comic-tools | AI 漫画创作工具归类仓库：7 个 GitHub 项目覆盖故事→分镜→画格→上色全环节，对比表+选型决策树+每家一页评估；含 StoryDiffusion（6.5k star，Apache-2.0，NeurIPS 2024 Spotlight）、MangaNinja（743 star，CVPR 2025 线稿上色，CC BY-NC 4.0 非商用注意）（2026-10-19 收录） | https://github.com/oeaf/ai-comic-tools |
| VoiceStudio | 开源、完全本地的 ElevenLabs 平替（Electron 桌面应用）：语音克隆、音色设计、视频配音、听写、转录、有声书制作，646 种语言；默认 k2-fsa/OmniVoice 引擎可换；NVIDIA CUDA / Apple Silicon 加速，无独显可 CPU 跑；带本地 API + MCP + 官方 skill（`npx skills add debpalash/VoiceStudio`）供 agent 调用；76.4k star，AGPL-3.0（应用本身含商用条件，模型权重/音色/生成内容授权另算；只克隆有授权的声音；2026-10-19 收录） | https://github.com/debpalash/VoiceStudio |
| xiaohongshu-mcp | 小红书 MCP 服务器：让 AI 助手直接操作小红书——扫码登录、发布图文/视频、搜索内容、刷推荐流、看帖子详情与评论、发评论/回复、点赞、收藏、看用户主页；Docker 部署的无头浏览器 HTTP 服务，原生支持 XHS_PROXY 代理（配固定住宅 IP 可显著降低机房 IP 的风控风险）；16.5k star，Apache-2.0（2026-10-23 收录） | https://github.com/xpzouying/xiaohongshu-mcp |
| infinite-canvas | 面向 AI 创作的开源无限画布工作台：节点连线编排文生图/图生图/参考图编辑/对话/音频/视频生成连续迭代，带提示词库、素材管理与画布助手；浏览器直连自备的 OpenAI 兼容接口（中转站/newapi/自建渠道），画布、素材与 Key 均存浏览器本地；另有本地 Agent 桥，可让 Codex/Claude Code 经 MCP 操作当前画布；8.0k star，MIT（开发期项目，作者明示本地数据格式可能不兼容变更；2026-10-23 收录） | https://github.com/basketikun/infinite-canvas |

## 效率与自动化

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| WorkDaddy | WorkBuddy/CodeBuddy 桌面端增强助手：多账号独立备份一键切换、免打扰模式让 AI 无人值守跑长任务、异常中断自动续接、跨账号会话迁移、暂存/快捷提示词；1.9k star，AGPL-3.0 协议（桌面工具，2026-10-13 收录） | https://github.com/babygoton/WorkDaddy |
| agent2api | 本地 OpenAI 兼容网关：复用 WorkBuddy 等十余家 AI 桌面客户端登录态，一个 base_url 调用多家模型额度，带多账号管理与请求报表；871 star（仅供学习交流、禁商用，反代行为可能违反上游 ToS；2026-10-14 收录） | https://github.com/aimod-cc/agent2api |
| magpie | 多 Agent 统一模型网关：一个本地网关服务所有 coding agent（Claude Code、Codex、Gemini CLI 等），任意模型配任意 Agent，路由组额度耗尽自动转移，用量/成本统计；12.8k star，MIT（桌面工具，2026-10-14 收录） | https://github.com/yetone/magpie |
| reason-network | 团队 coding agent 互联消息总线：每台电脑一个 daemon + MCP（list_team/send_message/check_inbox 三个工具），Claude Code/Codex/Cursor/Gemini CLI/Copilot CLI/opencode/pi/Reason 跨机互发消息；iroh 点对点直连（中继兜底），无中心服务器；105 star，MIT/Apache-2.0 双协议（2026-10-16 建库，2026-10-17 收录） | https://github.com/reason-machines/reason-network || reason-network | 团队 coding agent 互联消息总线：每台电脑一个 daemon + MCP（list_team/send_message/check_inbox 三个工具），Claude Code/Codex/Cursor/Gemini CLI/Copilot CLI/opencode/pi/Reason 跨机互发消息；iroh 点对点直连（中继兜底），无中心服务器；105 star，MIT/Apache-2.0 双协议（2026-10-16 建库，2026-10-17 收录） | https://github.com/reason-machines/reason-network |
| talorys | 自部署个人 AI 助手：跑在你自己的 Cloudflare 账号里，聊天、记忆、任务笔记、定时提醒和推送通知，一条命令部署，免费档友好、单用户、无遥测；1.0k star，MIT（2026-10-15 收录） | https://github.com/rociiu/talorys |
| OpenCLI | 把网站变成命令行的浏览器自动化 CLI：Chrome 扩展+本地守护进程，让 AI Agent 在你已登录的真实 Chrome 里执行确定性命令（默认 JSON 输出）；内置 B站/知乎/小红书/Reddit/HackerNews/X/GitHub 等站点适配器，无适配器的站点可用通用浏览器原语（导航/点击/填表/提取/截图），还能用配套 skill 自写新适配器；与 xiaohongshu-mcp 恰成对照——真人浏览器与网络环境、风控面小得多；30.6k star，Apache-2.0（2026-10-23 收录） | https://github.com/jackwener/OpenCLI |
| Agent-Reach | 给 AI Agent 装全网读取能力的 CLI+Skill 混合体：一个命令搜/读 X、Reddit、YouTube、B站、小红书等 14 个平台（只读不发帖），每平台一条多后端工具链自动兜底 + doctor 体检，零 API 费；OpenCLI 与 xiaohongshu-mcp 都是它的上游后端之一；102.7k star，MIT（混合体，2026-10-26 收录；登录渠道复用浏览器 cookie，作者建议用小号、暖号勿接；1.6 版部分渠道未实测；PyPI 同名包非本项目） | https://github.com/Panniantong/Agent-Reach |
| grill-me | 方案盘问 Skill（原作者 Matt Pocock，出自其 302.5k star 的 mattpocock/skills 合集）：拿一个模糊想法对你无情追问——按轮次问遍所有"前置条件已定"的问题，逼你把决策树每个分支都想清楚直到能拍板，无状态、不写文件；grill-me 是入口、grilling 是盘问引擎，另有留痕版 grill-with-docs（结合代码库产出术语表与 ADR）和大题版 wayfinder；GitHub 上同名独立仓库多为它的副本（2026-10-25 收录） | https://github.com/mattpocock/skills |
| Cindy | 开源开箱即用的 AI Agent 客户端（桌面+手机）：把 Claude Code、Codex、Pi 三套 harness 装进一个界面，会话跨设备接续、共享已配置的模型与订阅，带手机远程桌面、自动化例程、Slack/Telegram 通道与可定制的 companion（角色/指令/记忆/Skill）；客户端免费，用已有订阅/自备 Key/本地模型；7.3k star，Apache-2.0（工具项目，2026-10-27 收录；注意：2026-07 才建仓、成熟度待观察；后端不在开源仓内、默认连 Cindy 官方云，官方版带 TapDB 使用统计默认开、可在设置里关、本地跳过登录模式不报） | https://github.com/makecindy/cindy |

## 开发与工程

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| rea | 让 AI Agent 逆向分析任何 App：看中某个功能就讲清实现原理、带证据重建到自己项目；支持原生二进制、Electron、.NET、APK、网站、固件；83.7k star，MIT 协议（2026-10-11 已安装验证；另两个 skill 为该仓库自用维护工具，未装） | https://github.com/morluto/rea |
| reverse-skill | 网络安全技能路由包：逆向/授权渗透/CTF/安全研究，44 条路由规则自动选方法论、按需装工具链、经验库自进化；与 rea 互补（rea 偏产品逆向抄功能，这个偏攻防找漏洞）；41k star，MIT 协议（2026-10-12 已安装验证） | https://github.com/zhaoxuya520/reverse-skill |
| pentagi | 全自主 AI 多智能体渗透测试系统：Go 后端 + Web UI，Docker 自托管部署，自动执行复杂渗透测试流程；27.7k star，MIT 协议（独立系统，需自行部署；2026-10-13 收录） | https://github.com/vxcontrol/pentagi |
| mobile-mcp | 让 AI Agent 操作真机/模拟器的 MCP Server：iOS、Android 通用，点击/滑动/输入/装包/录屏/日志/崩溃报告全覆盖，支持 Claude Code、Codex、Gemini 等；9.1k star，Apache-2.0（工具，2026-10-14 收录） | https://github.com/mobile-next/mobile-mcp |
| harness2 | Google Research 的递归 Agent Harness 优化框架：不改模型权重，递归优化模型外围 8 个可编辑组件（system prompt、guardrails、memory、工具指引、subagents、skills、scripts、plugins）——任务级 Propose–Probe–Compose 试出最优 harness，跨任务沉淀经验进 improvement harness；实测 WorkBuddy-Bench +11.5、JobBench +4.5；6.5k star，Apache-2.0（模型实跑需自备 Vertex AI/模型额度，有 API 成本；2026-10-19 收录） | https://github.com/google-research/harness2 |
| serena | 给编程 Agent 装的"IDE"：MCP 工具包，让 Claude Code/Codex 等按符号理解与改代码（find symbol、find references、跨文件 rename、符号级编辑），底层走 LSP 语言服务器（40+ 语言，免费），另有付费 JetBrains 插件后端；uv 一条命令安装；30.5k star，GPL-3.0-or-later（本地自用无义务，分发才触发；2026-10-20 收录） | https://github.com/oraios/serena |
| leanrea | rea 的瘦身版：一个 8KB 的 SKILL.md 干 rea 的活——不用 MCP、不用 207 个工具，直接告诉 Agent 每种目标（Electron/asar、原生二进制、Go、APK、WASM、固件等）用哪个原生命令最快 + 现成侦察命令 + 踩坑清单；作者自测对比 rea 快 38%、省 60% token、准确率打平（小样本，自测数据）；1.2k star，MIT（2026-10-21 收录并本地安装，作默认逆向路线，rea 留作后备） | https://github.com/aicodeking/leanrea |
| LocalAI | 本地一站式 AI 推理引擎：OpenAI/Anthropic/ElevenLabs 兼容的 drop-in API，一个端点跑 LLM、视觉、语音（含声音克隆）、图像、视频，消费级硬件免 GPU 可跑；60+ 后端按需拉取，内置 agent+MCP 与 whisper ASR（可补语音管线 STT 缺口）；49.8k star，MIT（本机小 VM 无 GPU，重模态实际跑不动，只索引不部署；2026-10-21 收录） | https://github.com/mudler/LocalAI |
| graphify | 代码库知识图谱 Skill：在编程 Agent 里用 /graphify 把整个文件夹（代码、文档、SQL、配置、PDF、截图）变成可查询的知识图谱——代码走本地 tree-sitter AST 确定性解析，文档图片走模型抽取，每条边标注提取/推断/存疑；产出交互图谱、Obsidian 库、Agent 导航 wiki 与核心节点报告，查图谱比读原文大幅省 token（作者实测 52 文件混合语料 71.5 倍），带增量缓存、watch 同步、git 钩子与 MCP 模式；133.6k star，Apache-2.0（2026-10-23 收录） | https://github.com/Graphify-Labs/graphify |
| REA-Prompts | REA 配套提示词库（REAP）：单个 README 收录 17 类逆向调查提示词——功能追踪、原生二进制、功能克隆、游戏、固件、Android、内核、Electron/JS、版本对比与崩溃分析、长任务调查等，替换占位符粘贴即可用；统一要求给出文件/函数/地址级证据并区分事实与推断，含授权安全研究场景提示词；1.8k star，无 License（2026-10-24 收录） | https://github.com/JoasASantos/REA-Prompts |
| CodeGraph | 预索引代码知识图谱工具（独立 CLI + MCP 服务器，非 Skill）：Rust 内核 + tree-sitter 把代码库建成图谱存入本地 SQLite，Agent 一次调用即得相关源码、调用链与改动影响半径，不用 grep 逐文件爬；文件变更自动增量同步、框架路由感知、20+ 语言、100% 本地无需 Key；作者实测工具调用 -88%、token -62%、成本 -44%（但长会话上下文常驻占用偏高）；75.2k star，MIT（2026-10-24 收录并本地试跑通过） | https://github.com/colbymchenry/codegraph |
| ProxyPin | 开源免费全平台抓包工具（Charles/Fiddler 平替，Flutter 开发）：拦截、查看、改写 HTTP(S) 流量，支持抓 Flutter 应用；手机扫码连接免手配 WiFi 代理、配置同步、多端互转流量，带域名过滤、JS 脚本处理、请求重写/映射（本地 mock）、AES 自动解密、请求阻断、历史保存与 HAR 导入导出，覆盖 Win/Mac/Android/iOS/Linux（iOS 有 App Store 版）；14.3k star，Apache-2.0（工具项目，2026-10-27 收录；Mac 首次打开需在安全设置里放行未受信开发者） | https://github.com/wanghongenpin/proxypin |

## 数据与分析

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| world-intel-mcp | 全球情报 MCP 服务器：160 个工具覆盖 30+ 领域——金融市场/美联储流动性/SEC 文件全文检索、预测市场（Polymarket 与 Kalshi 同事件对照）、冲突军事（ACLED、ADS-B 军机追踪）、网络威胁、气候灾害、GDELT 新闻信号、难民迁移、选举日历与地理数据库（基地/港口/核设施）；数据全走免费公开 API 无需付费 key，带历史观测存档、每日带引用简报与地理围栏告警；1.0k star，MIT（2026-10-22 收录） | https://github.com/marc-shade/world-intel-mcp |

---

## 自研 Skill

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| feishu-bridge | 飞书企业自建应用机器人 ↔ AI Agent 双向桥接：长连接收发消息、附件回传、进程保活 | https://github.com/oeaf/feishu-bridge |
| openmontage-muse | 本地 AI 视频生产管线：自带视频生成、Fish Audio 免费配音、ffmpeg 合成 | https://github.com/oeaf/openmontage-muse |
| github-browser-ops | 用浏览器操作 GitHub 仓库的标准流程（GitHub App 无写权限时的代操作方案） | https://github.com/oeaf/github-browser-ops |
| my-project | Pi coding agent 粗活外包：API key 池轮换调用，把重复劳动甩给便宜模型 | https://github.com/oeaf/my-project |
| openverse-sfx | 免费音效搜索：Openverse API 聚合 Freesound，英文关键词搜可商用音效，返回试听直链、时长和现成署名文案（2026-10-18 建库，接口已实测可用） | https://github.com/oeaf/openverse-sfx |
| ai-video-styles | AI 视频风格选型手册：5 个 Claude 代码做视频工具归类（lemo-opuscar / huashu-art-motion / animate / xilo-opus-video / opus-video-skills），对比表+决策树+每家一页评估（2026-10-18 建库，4 家已逐一评估） | https://github.com/oeaf/ai-video-styles |

---

## 如何新增

1. 把 skill 的仓库链接（或压缩包）发给 Muse；
2. 她会试装验证，写好一句话介绍，按上面的大类放进来；
3. 分类不够用时再加新类，保持大类精简。
