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

## 艺术与视频动画

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| hypit | 给 AI Agent 的视频制作语言：丢一段爆款视频进来，Agent 就把整套工作流复刻出来（素材、字幕、B-roll、特效，按词不按秒锚定），一句命令生成 100 个变体；21.3k star，个人自用免费，商用条件见其 License（2026-10-12 已安装验证） | https://github.com/hypit-ai/hypit |
| shuohao-skills | AI 短剧制作 skill 集合（7 个）：小说改编排大纲、拆角色、定场景道具、写剧本、排开场走位、切分镜，带脚本化质量门禁，中文优先；4.7k star，Apache-2.0（2026-10-17 收录） | https://github.com/eternityspring/shuohao-skills |
| reelbench-skills | AI 视频拆解与清理工具 skill：成片逐镜头拆解（景别/运镜/节奏作用，15 个质量门禁）、视频与镜头数据对照合成、去元数据重建干净文件；932 star，Apache-2.0（2026-10-18 收录） | https://github.com/eternityspring/reelbench-skills |
| stickman-video-director | 火柴人动画导演 Skill：给 AI 一个话题，产出脚本、动态分镜、配音与音效提示词（再喂 AI 视频生成模型出片）；5 种画风 7 个视觉方案（极简黑白、现代流行红帽子、史前暗黑喜剧、温馨叙事、江户历史卡通），主打 YouTube 解说、TikTok、职场励志与知识短片；2.5k star，MIT（2026-10-21 收录） | https://github.com/kaomei/stickman-video-director |
| Concat | 开源免费的剪映/CapCut 平替（Rust 本地引擎）：多轨时间线剪辑、本地 Whisper 自动字幕、本地 TTS 与声音克隆、抠像、关键帧动画、100 种特效转场、4K 导出，无水印无账号全离线；自带 MCP 服务器与 JSON-RPC 接口，AI Agent 可直接驱动剪辑；10.3k star，AGPL-3.0，beta 0.2.8（2026-10-21 收录） | https://github.com/jub0t/Concat |

## 内容创作

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| chinese-novelist-skill | AI 写中文小说：三层问答定大纲、逐章生成 10-50 章完整长篇（3000-5000 字/章），带创作记忆、中断续写、悬念钩子、自动校验重写；3.5k star，MIT（2026-10-14 收录） | https://github.com/PenglongHuang/chinese-novelist-skill |
| LuxTTS | 高质量极速 TTS 语音克隆模型：150 倍实时速度、48kHz 清晰语音，仅需 1GB 显存，CPU 也可实时运行；5.4k star，Apache-2.0（模型，2026-10-14 收录） | https://github.com/ysharma3501/LuxTTS |
| InkOS | 故事创作 AI Agent 系统：长短篇小说、剧本剧作、互动影游、IP 内容与多语言翻译，19 个内置专业 Skill（写作/审稿/分镜/翻译），Studio/TUI/CLI 三端；10.3k star，AGPL-3.0（2026-10-14 收录） | https://github.com/Narcooo/inkos |
| Easel | 开源 AI 社媒运营工作台：发现热点→策划选题→创作图文/音频/视频→多平台发布→归因复盘，113 个 skill，账号画像驱动越用越贴合；3.8k star，Apache-2.0（小红书自动发布有风控风险，官方建议人工确认；2026-10-17 收录） | https://github.com/ZJU-REAL/Easel |
| audio-studio-mcp | 本地 AI 音频工作室 MCP Server：在自己 Mac 上用 Stable Audio 3（MLX）一句话生成 BGM/乐器 loop/音效（每次 1-4 个候选），可整体换风格/重绘时间段/续写延长，做无缝循环、响度标准化，导出 WAV/OGG/FLAC；无云服务、无 API Key、生成免费，每个文件带 prompt+seed 的 .json 可复现；86 star，MIT（模型权重适用 Stability AI Community License，个人及年收<100万美元组织可商用，商用前请核实最新条款；仅 Apple Silicon Mac；2026-10-19 收录） | https://github.com/kanaworksai-hue/audio-studio-mcp |
| ai-comic-tools | AI 漫画创作工具归类仓库：7 个 GitHub 项目覆盖故事→分镜→画格→上色全环节，对比表+选型决策树+每家一页评估；含 StoryDiffusion（6.5k star，Apache-2.0，NeurIPS 2024 Spotlight）、MangaNinja（743 star，CVPR 2025 线稿上色，CC BY-NC 4.0 非商用注意）（2026-10-19 收录） | https://github.com/oeaf/ai-comic-tools |
| VoiceStudio | 开源、完全本地的 ElevenLabs 平替（Electron 桌面应用）：语音克隆、音色设计、视频配音、听写、转录、有声书制作，646 种语言；默认 k2-fsa/OmniVoice 引擎可换；NVIDIA CUDA / Apple Silicon 加速，无独显可 CPU 跑；带本地 API + MCP + 官方 skill（`npx skills add debpalash/VoiceStudio`）供 agent 调用；76.4k star，AGPL-3.0（应用本身含商用条件，模型权重/音色/生成内容授权另算；只克隆有授权的声音；2026-10-19 收录） | https://github.com/debpalash/VoiceStudio |

## 效率与自动化

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| WorkDaddy | WorkBuddy/CodeBuddy 桌面端增强助手：多账号独立备份一键切换、免打扰模式让 AI 无人值守跑长任务、异常中断自动续接、跨账号会话迁移、暂存/快捷提示词；1.9k star，AGPL-3.0 协议（桌面工具，2026-10-13 收录） | https://github.com/babygoton/WorkDaddy |
| agent2api | 本地 OpenAI 兼容网关：复用 WorkBuddy 等十余家 AI 桌面客户端登录态，一个 base_url 调用多家模型额度，带多账号管理与请求报表；871 star（仅供学习交流、禁商用，反代行为可能违反上游 ToS；2026-10-14 收录） | https://github.com/aimod-cc/agent2api |
| magpie | 多 Agent 统一模型网关：一个本地网关服务所有 coding agent（Claude Code、Codex、Gemini CLI 等），任意模型配任意 Agent，路由组额度耗尽自动转移，用量/成本统计；12.8k star，MIT（桌面工具，2026-10-14 收录） | https://github.com/yetone/magpie |
| reason-network | 团队 coding agent 互联消息总线：每台电脑一个 daemon + MCP（list_team/send_message/check_inbox 三个工具），Claude Code/Codex/Cursor/Gemini CLI/Copilot CLI/opencode/pi/Reason 跨机互发消息；iroh 点对点直连（中继兜底），无中心服务器；105 star，MIT/Apache-2.0 双协议（2026-10-16 建库，2026-10-17 收录） | https://github.com/reason-machines/reason-network || reason-network | 团队 coding agent 互联消息总线：每台电脑一个 daemon + MCP（list_team/send_message/check_inbox 三个工具），Claude Code/Codex/Cursor/Gemini CLI/Copilot CLI/opencode/pi/Reason 跨机互发消息；iroh 点对点直连（中继兜底），无中心服务器；105 star，MIT/Apache-2.0 双协议（2026-10-16 建库，2026-10-17 收录） | https://github.com/reason-machines/reason-network |
| talorys | 自部署个人 AI 助手：跑在你自己的 Cloudflare 账号里，聊天、记忆、任务笔记、定时提醒和推送通知，一条命令部署，免费档友好、单用户、无遥测；1.0k star，MIT（2026-10-15 收录） | https://github.com/rociiu/talorys |

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

## 数据与分析

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |

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
