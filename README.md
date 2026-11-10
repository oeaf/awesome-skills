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
| handraw-style | 手绘风格与排版图型提示词 Skill（真 Skill）：365 种手绘/写实风格、170 种排版图型（社媒卡/信息图/漫画分镜/IP设计/电商）、36 种单色主题色全编号化，选编号+主题即出中英双语生图提示词，带智能推荐、海报设计、文章/视频封面设计、长文批量配图回填与摄影企划模式，本地离线画廊可检索；6.7k star，MIT（附署名要求，商用须保留作者 yang0 与原仓地址）；v1.9.8（2026-10-31 收录并本地安装；注意：上游自带把用户原始请求+图片发到作者网站作品广场的 community-share 子技能，本机已在 LOCAL_NOTES.md 中禁用，默认不外发） | https://github.com/yang0/handraw-style |

## 艺术与视频动画

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| hypit | 给 AI Agent 的视频制作语言：丢一段爆款视频进来，Agent 就把整套工作流复刻出来（素材、字幕、B-roll、特效，按词不按秒锚定），一句命令生成 100 个变体；21.3k star，个人自用免费，商用条件见其 License（2026-10-12 已安装验证） | https://github.com/hypit-ai/hypit |
| digital-human-koubo | 数字人口播全流程 Skill：一张照片 + 一句需求出成品口播片——GPT Image 建人设锁一致性、经 Renoise MCP 调 Grok Video 1.5 生成原生说话+口型片段、whisper 回转录对稿质检、Remotion 剪辑渲染；5 种剪辑风格 + 48 个从 25 条头部创作者视频逐帧拆出的包装组件；520 star，MIT（真 Skill，2026-10-26 收录；生成需付费 Renoise 积分、不走 Pavo；仓库建于收录当日、维护待观察；招牌「文字在人物身后」组件仅 macOS；Remotion 另有其协议） | https://github.com/andyhuo520/digital-human-koubo |
| shuohao-skills | AI 短剧制作 skill 集合（7 个）：小说改编排大纲、拆角色、定场景道具、写剧本、排开场走位、切分镜，带脚本化质量门禁，中文优先；4.7k star，Apache-2.0（2026-10-17 收录） | https://github.com/eternityspring/shuohao-skills |
| reelbench-skills | AI 视频拆解与清理工具 skill：成片逐镜头拆解（景别/运镜/节奏作用，15 个质量门禁）、视频与镜头数据对照合成、去元数据重建干净文件；932 star，Apache-2.0（2026-10-18 收录） | https://github.com/eternityspring/reelbench-skills |
| rea-video | 逐镜逆向一切视频的 Skill+CLI（混合体）：判实拍/AI/3D/代码/录屏/混剪的制作方式（AIGC 标识/帧率/噪点取证优先），拆花字字幕（导出 SRT/ASS）、剪辑节奏与声音来源，分镜给实拍机位布光、AI 反推提示词、代码 Remotion 复刻方案，出 report.html；1,652 star，Apache-2.0（2026-11-05 核查：LICENSE 文件已补，收录时“无 LICENSE、授权不完整”的说法已过时；2026-11-04 收录，只索引未本地装） | https://github.com/JuneYaooo/rea-video |
| ai-anime-series | AI 动画单元剧 Skill（真 Skill）：固定原创角色一句话出一集——角色设定图 + 宫格故事板（30 秒 9 格）+ 即梦 Seedance 2.5 全能参考一次生成无台词动作喜剧，脚本自动拼提示词（@图/宫格/秒数对齐）、抽帧检查、单格补拍与合集拼接；276 star，scripts 为 MIT、其余（SKILL/文档/模板/示例）为 CC BY-NC 4.0 非商用（变现账号需留意），且生成须即梦会员在画布手动出图出视频（2026-11-04 收录，只索引未本地装，仓库仅建仓日 3 commit、维护待观察） | https://github.com/10291124jcjc-dotcom/ai-anime-series |
| sprite-gen | 2D 游戏精灵与动画图集 Skill+CLI（混合体）：一张原画按状态逐行生成（idle/walk/run/jump/attack）、锁定角色一致性、色键背景清成真透明 alpha、逐帧提取并拼运行时图集（sprite-sheet-alpha.png + manifest.json），另可走视频线生成无缝透明循环；带选帧 curation、待机呼吸、换色与 Aseprite/Phaser/Flame 导出；3,347 star，Apache-2.0（生成全用自有凭证、订阅优先：Codex/Grok/Claude 登录，OpenAI provider 仅主动选时按次计费；2026-11-05 收录，只索引未本地装） | https://github.com/aldegad/sprite-gen |
| gif-factory | 角色 GIF 量产真 Skill（GIF 工厂）：生图工具先出 4×4 透明精灵图集，自带 Python 导出脚本切分、加动效、拼成 GIF；外观三档（像素 320px、清爽插画 HD 512px、照片真人与宠物）与动作两档（轻动效、连续关键帧动作）独立组合，五条产出线为聊天表情包、电子光栅变画卡、角色动态海报、吉祥物品牌短片、紧凑动态绘本（另有子 Skill）；56 例风格画廊逐个标注已验收与待定状态，素材只用用户提供或授权的图；678 star，MIT（仓龄仅 3 天、单作者、各风格成熟度参差；仓库本体约 368MB 多为预览 GIF，本地装应只拉 Skill 本体；2026-11-08 收录，只索引未本地装） | https://github.com/WoYun520/gif-factory |
| muse4ai | Meta Muse 桥接工具（工具项目，附 Agent Skill）：装在 Windows PC 上，把已登录的 Muse 账号会话经 REST/MCP/自建 OAuth 开放给 ChatGPT、Claude、Codex 等 Agent 调用，生图/生视频（约 8–10 秒 720p，可续接至约 60 秒）、改视频、带记忆聊天，烧账号自身的 Muse 用量额度；866 star，MIT（非官方项目，作者明示自动化 Muse 会话可能不符合 Meta 服务条款、风险自担，安装包未签名；仅 Windows 版，macOS/Linux 未打包；2026-11-06 收录，只索引未本地装） | https://github.com/andrew-babo/muse4ai |
| muse2api | Muse 逆向 OpenAI 兼容 API（工具项目）：把 muse.ai 封装成对话、文生图、文生视频/图生视频接口，浏览器自动化驱动网页，多账号池轮转、48h 自动续期、每账号独立代理，配套 Cookie 导入插件与管理后台，Docker/systemd 可自部署；1,016 star，MIT 开源可审计（MuseCanvas 闭源生成池的上游原版）；账号池化与自动化调用有 Meta 条款与封号风险（2026-11-06 收录，只索引未本地装） | https://github.com/czg86389-hub/muse2api |
| gbro-collage-broll | 半调纸拼贴 B-roll 生成 Skill（真 Skill）：约 5 秒口播文稿转高级编辑风拼贴组装动画（纯色纸面 + 黑白半调剪贴 + 卡纸点缀，元素滑入卡位），默认 9:16、5 秒无声 MP4；核心是三闸门审批（隐喻确认→静帧确认→视频生成）避免浪费付费生成，视频用 Gemini Omni Flash 首尾帧并带抽帧 QA；1,730 star，MIT（静帧原依赖 Codex 内置生图、视频需自备 GEMINI_API_KEY 按量计费；2026-07 一次性发布后停更；2026-11-06 收录，只索引未本地装） | https://github.com/pyang5166/gbro-collage-broll |
| comfy-colab-kit | ComfyUI on Colab 按需唤醒网关（工具项目，附 Agent Skill）：本地或 VPS 常驻小网关，点 Wake 自动在自有 Google 账号下开 Colab L4、灌入模型配置档（MOSS-Image、FLUX.2、Wan 2.2 视频、SD3.5、Qwen）并反向代理出完整原版 ComfyUI；空闲/超时长/CU 预算硬顶自动关停防烧额度，MCP 与 ckit 命令行供 Agent 无浏览器调用（文生图、图生图、图生视频、关停）；118 star，MIT（程序化操控 Colab 属条款灰区、作者声明仅限个人使用，Google 账号风险自担；2026-11-07 收录，只索引未本地装） | https://github.com/FireTable/comfy-colab-kit |
| seedance-2.0 | Seedance 2.0 导演操作系统（真 Skill）：覆盖即梦/Dreamina/剪映/豆包/火山方舟/BytePlus/Runway Seedance 通道/fal 等全部入口，先做导演解读再按模式写文生/图生/参考生/首尾帧提示词，带对白口型音频、序列续接状态管理、IP 安全改写与多语言提示词，含专业制片闸门；8,088 star，MIT（写死只服务 2.0：时长、参考上限、模型 ID 等硬参数不可外推到 2.5 等新线，导演手艺框架可借鉴；2026-11-07 收录，只索引未本地装） | https://github.com/Emily2040/seedance-2.0 |
| cinecode | 用代码拍电影的真 Skill：每一帧都在无头 Chrome 里用 HTML/CSS/three.js 代码画出并渲染，声音走 Web Audio 合成，剧本、画面、声音、剪辑到 -14 LUFS 母带MP4 由 Agent 全包；Quick 模式（单个 HTML 文件、最长约 3 分钟、低清草稿两轮修订）与 Film 模式（风格帧、动画预演、three.js 渲染、分层声音六道门禁），覆盖短片、YouTube 长片、广告、讲解片与音乐视频，附运镜、风格、声音、字体库等约 35 万字 references；1,060 star，MIT（仓龄仅 5 天，提交全挤在 2026-11-03 首发日，维护持续性未验；SKILL.md 自带 hooks，会在宿主每次提问与工具调用时跑其 guard 脚本强制流程，本地装前需先审，原生面向 Claude Code 与 Cursor；2026-11-08 收录，只索引未本地装） | https://github.com/sarpstar/cinecode |
| stickman-video-director | 火柴人动画导演 Skill：给 AI 一个话题，产出脚本、动态分镜、配音与音效提示词（再喂 AI 视频生成模型出片）；5 种画风 7 个视觉方案（极简黑白、现代流行红帽子、史前暗黑喜剧、温馨叙事、江户历史卡通），主打 YouTube 解说、TikTok、职场励志与知识短片；2.5k star，MIT（2026-10-21 收录） | https://github.com/kaomei/stickman-video-director |
| Concat | 开源免费的剪映/CapCut 平替（Rust 本地引擎）：多轨时间线剪辑、本地 Whisper 自动字幕、本地 TTS 与声音克隆、抠像、关键帧动画、100 种特效转场、4K 导出，无水印无账号全离线；自带 MCP 服务器与 JSON-RPC 接口，AI Agent 可直接驱动剪辑；10.3k star，AGPL-3.0，beta 0.2.8（2026-10-21 收录） | https://github.com/jub0t/Concat |
| OpenCut | 开源免费的剪映/CapCut 平替（网页版，浏览器打开 opencut.app 即剪）：同品类社区最大；与 Concat 并列收录作选型对比——手动剪辑图省事选它、Agent 自动剪辑选 Concat；注意主仓库正推倒重写（Rust 内核、插件架构，给 Agent 的 MCP 服务器与无头批量渲染在路线图上、尚未发布），当前可用稳定版在 opencut-classic 仓库，官网亦跑该版；95.8k star，MIT（2026-10-23 收录） | https://github.com/opencut-app/opencut |
| MoneyPrinterTurbo | 一站式 AI 短视频生成工具：给主题/关键词，自动写脚本、从 Pexels/Pixabay 等匹配免费库存素材、配音（Edge TTS 免费，另支持 Fish Audio 等）、加字幕与配乐并合成 9:16/16:9/1:1 高清成片，带 WebUI/API/CLI 与批量生成，可自动发 TikTok/IG/YouTube Shorts；与 AI 真生成画面的管线互补，主打低成本无脸号批量出片（脚本需自备 LLM Key）；135.6k star，MIT（工具项目，附 Agent Skill，2026-10-27 收录） | https://github.com/harry0703/MoneyPrinterTurbo |
| awesome-opus5-5-videos | Claude Opus 5.5 代码动画视频提示词弹药库：703 条爆款视频的原始提示词（动效/讲解/3D 场景/游戏互动四类），每条链回创作者原帖、418 条在 Skillry 有与原作并排的实时复刻；复制提示词给跑 Opus 5.5 的 Agent、渲染成单个 HTML、录屏即成片，与 huashu-art-motion / ai-video-styles 的代码做视频路线配套；12.1k star，MIT（资料类，2026-10-28 收录；2026-09 新仓、仅 10 个 commit 的清单型仓库；部分提示词不完整，视频与提示词权利归原作者，原样搬运商用需谨慎） | https://github.com/yihui-dev/awesome-opus5-5-videos |

## 内容创作

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| chinese-novelist-skill | AI 写中文小说：三层问答定大纲、逐章生成 10-50 章完整长篇（3000-5000 字/章），带创作记忆、中断续写、悬念钩子、自动校验重写；3.5k star，MIT（2026-10-14 收录） | https://github.com/PenglongHuang/chinese-novelist-skill |
| lieflat-less-ai-tone | 数据驱动的中文去 AI 味 Skill（真 Skill）：基于两轮语料研究（1,169 篇、约 520 万字、100+ 项指标、约 50 万次模型语义判断）筛出真能区分 AI 文与人写文的特征并按证据分层；流程是先出带指标、原文例句与改法的检测报告，用户确认后才最小改写并复测，反对禁用词表与乱改误伤；附检测/报告/结构/翻译腔脚本与完整实例；6,671 star（CC BY-NC 4.0：署名、非商用，商用需联系作者；语料以简体长文为主；2026-11-07 收录，只索引未本地装） | https://github.com/larashero3-dotcom/lieflat-less-ai-tone |
| watermarks-remover | 清除 AI 内容出身标记的 Skill + 本地服务（混合体）：三层清理，不可见字符（零宽、异种空格、双向控制符、标签字符）、统计文本水印（绿名单、Gumbel 类与 SynthID-Text 类）靠改写处理、文件元数据（C2PA、EXIF、XMP、文档属性），覆盖图片、PDF、Office、EPUB、HTML、Markdown、音视频等三十余种格式；瘦客户端 Skill 调本地纯标准库 HTTP 服务（仅监听 127.0.0.1），另有自包含纯文本版 Skill 与写文件后自动检查的 hook，官方定位为处理自有内容的隐私与卫生清理，与本库 video-scrub 的清元数据属同一卫生线；26,555 star，MIT（双面性提示：同一能力也可用于把 AI 内容伪装成纯人写，条目按官方定位仅限自有内容场景；2026-11-07 收录，只索引未本地装） | https://github.com/guillaumemeyer/watermarks-remover |
| ljg-skills | 李继刚的个人技能合集（26 个 ljg-* 真 Skill），以认知工具为主：概念解剖、追本之箭、降秩引擎、约束引擎、理解引擎、结构类比、机制研究、母题结构风洞；阅读类有拆书、论文阅读、伴读、信息提问机（文章抽成 Q-A 链）、古文精读；产出类有内容铸卡 ljg-card（文本铸成长图、全文卡、漫画、白板 PNG，依赖 Playwright 截图）、写作引擎 ljg-writes、单文件离线 HTML 演讲 ljg-present、商业模式画布与知识地图，另有圆桌讨论、关系与投资分析、盲区扫描（接微信读书）、单词精通等；原生面向 Codex，经 skills CLI 挑装或全装，双分支双格式：master 为 Org-mode，md 分支为 Markdown（通用生态用后者）；7,699 star，MIT，持续同步至 v1.17.126（2026-11-08 收录，只索引未本地装） | https://github.com/lijigang/ljg-skills |
| cangjie-skill | 内容蒸馏 Skill（真 Skill）：把书、长视频、播客、访谈里的方法论蒸馏成可调用的 Agent Skill 包（RIA-TV++ 流水线：全内容理解→五路并行提取→三重验证→能力卡构建→卡片链接→压力测试→确定性编译，产出 single 单技能或 pack 紧凑技能包）；配套 video-downloader（在 kangarooking-skills 仓）负责视频下载、字幕/语音转写与多模态画面理解（看懂代码/PPT/图表并对齐时间戳，含视频号支持），产出多模态文案再交给仓颉蒸馏；12.6k star，MIT（仓库最新为 v2.5.0，作者 X 帖所称「3.0」是仓颉+video-downloader 组合工作流口径、仓库本身未挂 3.0 版本号；蒸馏效果取决于驱动模型，帖中 LongCat-2.5 的参数与价格为宣传口径、未核实；2026-11-10 收录，只索引未本地装） | https://github.com/kangarooking/cangjie-skill |
| LuxTTS | 高质量极速 TTS 语音克隆模型：150 倍实时速度、48kHz 清晰语音，仅需 1GB 显存，CPU 也可实时运行；5.4k star，Apache-2.0（模型，2026-10-14 收录） | https://github.com/ysharma3501/LuxTTS |
| Qwen3-TTS | 阿里通义开源 TTS 模型家族：3 秒声音克隆、文字描述造声（VoiceDesign）、流式生成，支持 10 种语言，0.6B/1.7B 两档；14.0k star，Apache-2.0（模型，2026-10-26 收录，源自 @0x8888 配音清单帖评估） | https://github.com/QwenLM/Qwen3-TTS |
| Qwen3.8-27B-Uncensored | 无审查多模态大模型（模型，Hugging Face 非 GitHub）：Qwen3.8-27B 的去审查 GGUF 量化仓，量化档 IQ2_M 10.62GB 到 Q8_0 29.05GB（Q4_K_M 16.81GB），另有 0.93GB 的 mmproj 视觉投影文件；近 30 天下载 251 万次、1,934 赞（2026-11-08 核）；苹果芯片另有 orcarouter 的 MLX 版（2/4/6-bit）；出处为 @aehyok 2026-10-01 的无审查模型推荐帖（同帖另两条 Qwen3.6 与生图、生视频条目未收）；硬件提示：基础版 Mac mini M4 的 16GB 内存跑不动 Q4_K_M，IQ2_M 能塞下但质量掉得明显，真要本地跑无审查昨天核过的 9B Heretic 更合适（2026-11-08 收录，只索引未下载未安装） | https://huggingface.co/JonathanColetti/Qwen3.8-27B-Uncensored-GGUF |
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
| OpenMausBot | 开源个人 Agent 团队客户端（工具项目）：像聊天软件一样的桌面应用，侧边栏每个联系人是一个真 Agent，跑你本机已装的 claude / codex / grok 命令行、用你现成的登录与订阅，每个 bot 独立人设、模型与电脑（云端桌面、隔离虚拟机，或经授权控制主机），敏感操作有审批卡，数据存本地；16,121 star，Apache-2.0（自称 Grok Bot 与 Meta Muse 等的开源替代；0.1.x 非常早期、迭代极快、815 个 open issue；bot 可控主机加 Composio 聚合授权、权限面大；2026-11-07 收录，只索引未本地装） | https://github.com/milind-soni/OpenMausBot |
| deva | 对话式桌面 AI Agent 客户端（工具项目，Electron）：把 Agent 能力装进聊天界面，多服务商接入，自带浏览器与终端等工具和 persona 角色系统（角色提示词追加到系统提示词层，一个对话绑定一个角色、首发后不可改，自定义角色存本地 .md）；内置全能助手 Deva 与破甲角色「小码酱」（约 29KB 的安全研究与逆向向提示词快照，README 称源自 dsh-purge 且仅对国产模型生效，2026-10-25 源码核查实为硬编码、无模型白名单）；870 star，MIT（破甲角色属越狱向提示词，本条目仅作索引记录；桌面应用，本机 VM 无图形会话，真要用装 Mac；2026-11-08 收录，只索引未本地装） | https://github.com/sqfcyily/deva |

## 开发与工程

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| rea | 让 AI Agent 逆向分析任何 App：看中某个功能就讲清实现原理、带证据重建到自己项目；支持原生二进制、Electron、.NET、APK、网站、固件；83.7k star，MIT 协议（2026-10-11 已安装验证；另两个 skill 为该仓库自用维护工具，未装） | https://github.com/morluto/rea |
| reverse-skill | 网络安全技能路由包：逆向/授权渗透/CTF/安全研究，44 条路由规则自动选方法论、按需装工具链、经验库自进化；与 rea 互补（rea 偏产品逆向抄功能，这个偏攻防找漏洞）；41k star，MIT 协议（2026-10-12 已安装验证） | https://github.com/zhaoxuya520/reverse-skill |
| pentagi | 全自主 AI 多智能体渗透测试系统：Go 后端 + Web UI，Docker 自托管部署，自动执行复杂渗透测试流程；27.7k star，MIT 协议（独立系统，需自行部署；2026-10-13 收录） | https://github.com/vxcontrol/pentagi |
| dsh-purge | DeepSeek Harness 本机红队评测插件（工具项目，非 Skill）：装在本机官方 DSH（Web/桌面）上，分开宿主策略与模型拒绝、分组管理补丁/提示词/多套规则（可按模型换提示词，默认面向国模）、带本地演练台，v1.1.90 适配 DSH 0.2.1-rc.2（不支持 rc.3+）；18.1k star，Apache-2.0 但附加署名/禁止倒卖、转售/白标/卖课须另谈商业授权，开源版自限仅本机回环与 RFC1918 私网靶场、禁游戏外挂，改宿主提示词与策略可能违反上游服务条款（2026-11-05 收录，只索引未本地装） | https://github.com/HunYiSage/dsh-purge |
| mobile-mcp | 让 AI Agent 操作真机/模拟器的 MCP Server：iOS、Android 通用，点击/滑动/输入/装包/录屏/日志/崩溃报告全覆盖，支持 Claude Code、Codex、Gemini 等；9.1k star，Apache-2.0（工具，2026-10-14 收录） | https://github.com/mobile-next/mobile-mcp |
| agent-desktop | Vercel Labs 的桌面 Computer Use 工具（Rust CLI + C 库，自带 Agent Skill）：不靠截图猜像素，读操作系统无障碍树给每个 UI 元素稳定 ref，Agent 点 ref 后再 snapshot 验证、动作可安全重试，默认 headless 不抢焦点；56 个命令覆盖点击/输入/窗口管理/剪贴板/通知/截图，支持 macOS、Windows、Linux；5.2k star，Apache-2.0（工具项目，2026-11-01 收录，只索引未本地装；注意：snapshot/剪贴板/截图可带出桌面隐私内容，勿传公开日志；本机 VM 无图形会话，真要用装在 Mac 上） | https://github.com/vercel-labs/agent-desktop |
| browse | OpenCode 家的真实浏览器操控工具（工具项目，MCP 服务 + Chromium 扩展，母项目 anomalyco/opencode 225k star）：让 OpenCode、Claude Code、Codex、Cursor、Zed 等 MCP 客户端直接用用户本人的真实浏览器（Chrome、Edge、Brave、Arc 等）连同标签页、登录态与扩展干活，后台折叠分组开标签、Playwright 驱动、截图与录屏、抓 HAR 网络包；登录、二次验证、付款环节把标签页交还用户，点 Continue 才继续，还可把已开标签页借给 Agent，可设站点白名单；免费，241 star，MIT（权限面提示：接上的 Agent 等于握有已登录浏览器的控制权，属最敏感的一类授权，靠白名单与人工接管缓解；战场在用户本机浏览器，本机 VM 装了无意义；2026-11-08 收录，只索引未本地装） | https://github.com/anomalyco/browse |
| agent-autoloop | 命令行 Agent 自动化中台（工具项目，附 Agent SKILL.md）：事件（定时/GitHub、GitLab Webhook/HTTP/轮询）按 rules.json 派给 Claude Code、Codex、ACP、DeepSeek Harness 或通用命令（含 Pi）在后台干活、干一轮退出；拿不准（删数据/重启/花钱/对外发消息）才经飞书/钉钉/企微/Slack/Discord/桌面通知发拍板卡片，答后接原会话续办；带早报、Issue 跟进、线上告警、网站巡检、飞书摘要模板与 PR 交付流水线；3,390 star，MIT（仅 macOS/Linux，Windows 版未出；项目仅 3 天，部分模板只做过本地模拟验证；2026-11-06 收录，只索引未本地装） | https://github.com/KKKKhazix/agent-autoloop |
| harness2 | Google Research 的递归 Agent Harness 优化框架：不改模型权重，递归优化模型外围 8 个可编辑组件（system prompt、guardrails、memory、工具指引、subagents、skills、scripts、plugins）——任务级 Propose–Probe–Compose 试出最优 harness，跨任务沉淀经验进 improvement harness；实测 WorkBuddy-Bench +11.5、JobBench +4.5；6.5k star，Apache-2.0（模型实跑需自备 Vertex AI/模型额度，有 API 成本；2026-10-19 收录） | https://github.com/google-research/harness2 |
| serena | 给编程 Agent 装的"IDE"：MCP 工具包，让 Claude Code/Codex 等按符号理解与改代码（find symbol、find references、跨文件 rename、符号级编辑），底层走 LSP 语言服务器（40+ 语言，免费），另有付费 JetBrains 插件后端；uv 一条命令安装；30.5k star，GPL-3.0-or-later（本地自用无义务，分发才触发；2026-10-20 收录） | https://github.com/oraios/serena |
| leanrea | rea 的瘦身版：一个 8KB 的 SKILL.md 干 rea 的活——不用 MCP、不用 207 个工具，直接告诉 Agent 每种目标（Electron/asar、原生二进制、Go、APK、WASM、固件等）用哪个原生命令最快 + 现成侦察命令 + 踩坑清单；作者自测对比 rea 快 38%、省 60% token、准确率打平（小样本，自测数据）；1.2k star，MIT（2026-10-21 收录并本地安装，作默认逆向路线，rea 留作后备） | https://github.com/aicodeking/leanrea |
| LocalAI | 本地一站式 AI 推理引擎：OpenAI/Anthropic/ElevenLabs 兼容的 drop-in API，一个端点跑 LLM、视觉、语音（含声音克隆）、图像、视频，消费级硬件免 GPU 可跑；60+ 后端按需拉取，内置 agent+MCP 与 whisper ASR（可补语音管线 STT 缺口）；49.8k star，MIT（本机小 VM 无 GPU，重模态实际跑不动，只索引不部署；2026-10-21 收录） | https://github.com/mudler/LocalAI |
| graphify | 代码库知识图谱 Skill：在编程 Agent 里用 /graphify 把整个文件夹（代码、文档、SQL、配置、PDF、截图）变成可查询的知识图谱——代码走本地 tree-sitter AST 确定性解析，文档图片走模型抽取，每条边标注提取/推断/存疑；产出交互图谱、Obsidian 库、Agent 导航 wiki 与核心节点报告，查图谱比读原文大幅省 token（作者实测 52 文件混合语料 71.5 倍），带增量缓存、watch 同步、git 钩子与 MCP 模式；133.6k star，Apache-2.0（2026-10-23 收录） | https://github.com/Graphify-Labs/graphify |
| REA-Prompts | REA 配套提示词库（REAP）：单个 README 收录 17 类逆向调查提示词——功能追踪、原生二进制、功能克隆、游戏、固件、Android、内核、Electron/JS、版本对比与崩溃分析、长任务调查等，替换占位符粘贴即可用；统一要求给出文件/函数/地址级证据并区分事实与推断，含授权安全研究场景提示词；1.8k star，无 License（2026-10-24 收录） | https://github.com/JoasASantos/REA-Prompts |
| craft-anything | 干净室逆向重建引擎（工具项目，纯 Rust）：指向任何网站/App/游戏/文件，320 个检查工具（反汇编、伪 C、调用图、运行检查，每工具同时是 CLI 与 MCP）研究原作，再驱动编程 Agent 重建新项目并逐项比对原作、迭代修正，Clean room / Deep 双模式；桌面应用 + CLI + MCP，重建首选驱动用户自有 Claude Code（不经手账号），Codex 适配尚未验证；16,860 star，MIT/Apache-2.0 双授权（early alpha，建仓 6 天连发四版、迭代极快；2026-11-06 收录，只索引未本地装） | https://github.com/storytold/craft-anything |
| CodeGraph | 预索引代码知识图谱工具（独立 CLI + MCP 服务器，非 Skill）：Rust 内核 + tree-sitter 把代码库建成图谱存入本地 SQLite，Agent 一次调用即得相关源码、调用链与改动影响半径，不用 grep 逐文件爬；文件变更自动增量同步、框架路由感知、20+ 语言、100% 本地无需 Key；作者实测工具调用 -88%、token -62%、成本 -44%（但长会话上下文常驻占用偏高）；75.2k star，MIT（2026-10-24 收录并本地试跑通过） | https://github.com/colbymchenry/codegraph |
| google-colab-cli | Google 官方 Colab 命令行工具（工具项目，附官方 Agent Skill colab-operator）：终端里开 CPU 与 GPU（T4、L4、G4、H100、A100）和 TPU 会话，用 exec、run、repl、ssh 执行本地脚本、传文件、挂 Google Drive、导出会话日志，run 是一次性任务跑完自动销毁；uv 或 pip 安装，仅支持 Linux 与 macOS；授权走 OAuth2 或 ADC（Agent 无头使用走 ADC，需本人完成一次 Google 授权）；2,005 star，Apache-2.0（官方合规的 Colab 自动化通道，区别于 comfy-colab-kit 那种第三方程序化操控的条款灰区；烧同一个 Colab CU 余额，Google AI Pro 每月附 200 CU；2026-11-08 收录，只索引未本地装） | https://github.com/googlecolab/google-colab-cli |
| colab-t4-local-api | Colab T4 本地 OpenAI API 复刻包（工具项目，非 Skill）：Windows 本地网关经 Cloudflare 临时隧道连 Colab T4 上的 llama.cpp，模型缓存进自有 Google Drive，本地以 http://127.0.0.1:11435/v1 提供 OpenAI 兼容接口，本地无需显卡；默认模型 deepseek-heretic-9b（DeepSeek 蒸馏 Qwen 9B 去审查版），配置 128K 上下文（README 注明仅为配置值、不保证 T4 显存能吃下任意长度）；专为 Agent 部署设计（AGENTS.md+部署手册+doctor 自检+离线测试，审查记录明示离线测试不等于云端部署成功）；46 star，无 LICENSE（README 明示尚未选许可证、不应宣称已开源授权），2026-11-08 建仓仅 2 次提交、仓龄极新；程序化操控 Colab 属条款灰区、Colab 资格与免费政策会变不承诺长期在线，本地入口 loopback 无鉴权勿改公网监听，仅 Windows（2026-11-10 收录，只索引未本地装） | https://github.com/mingzi206-gh/colab-t4-local-api |
| ProxyPin | 开源免费全平台抓包工具（Charles/Fiddler 平替，Flutter 开发）：拦截、查看、改写 HTTP(S) 流量，支持抓 Flutter 应用；手机扫码连接免手配 WiFi 代理、配置同步、多端互转流量，带域名过滤、JS 脚本处理、请求重写/映射（本地 mock）、AES 自动解密、请求阻断、历史保存与 HAR 导入导出，覆盖 Win/Mac/Android/iOS/Linux（iOS 有 App Store 版）；14.3k star，Apache-2.0（工具项目，2026-10-27 收录；Mac 首次打开需在安全设置里放行未受信开发者） | https://github.com/wanghongenpin/proxypin |
| mubeng | 代理检测与 IP 轮换网关（工具项目，Go）：批量验活代理池，并在本机起代理端口逐请求轮换出口 IP；支持 HTTP、SOCKS4(A)/5 与 Amazon API Gateway，可作 Burp/ZAP 上游代理链，全平台二进制/Docker；2,796 star，Apache-2.0（README 明示用途含绕 IP 封禁、API 限速与 WAF 拦截，撞目标站 ToS 自担；2021 年老项目、维护放缓，末次功能更新 2025-08；2026-11-06 收录，只索引未本地装） | https://github.com/mubeng/mubeng |

## 数据与分析

| 名字 | 功能简介 | 项目地址 |
| --- | --- | --- |
| world-intel-mcp | 全球情报 MCP 服务器：160 个工具覆盖 30+ 领域——金融市场/美联储流动性/SEC 文件全文检索、预测市场（Polymarket 与 Kalshi 同事件对照）、冲突军事（ACLED、ADS-B 军机追踪）、网络威胁、气候灾害、GDELT 新闻信号、难民迁移、选举日历与地理数据库（基地/港口/核设施）；数据全走免费公开 API 无需付费 key，带历史观测存档、每日带引用简报与地理围栏告警；1.0k star，MIT（2026-10-22 收录） | https://github.com/marc-shade/world-intel-mcp |
| douyin-comments | 抖音单条视频完整评论抓取 Skill（真 Skill）：在已登录 Chrome 里照抄页面真实请求、签名交给页面 SDK，抓一级评论+全部楼中楼+视频详情，输出按点赞排序的评论全文 Markdown 与原始 JSON，可选下载 720p 视频；不逆向 a_bogus、不用付费接口，实测 195 条与手动展开逐条一致；硬依赖 Claude Code + Claude in Chrome 扩展；279 star，无 License（代码复用无授权依据），作者声明仅个人研究、须遵守抖音协议、勿批量/商用，2026-10-30 建仓尚新（2026-10-31 收录，只索引未本地装） | https://github.com/Pluviobyte/douyin-comments |
| Scrapling | Python 网页抓取全家桶框架（工具项目，附 MCP Server + Agent Skill）：快速 HTTP（TLS 指纹伪装/HTTP3）+ 隐身浏览器（Playwright，过 Cloudflare Turnstile/Interstitial）+ Scrapy 式 Spider 并发爬虫（代理轮换/断点续爬/AutoThrottle）+ 自适应元素追踪解析（CSS/XPath/文本/正则），一行转 RAG-ready Markdown，带 CLI 与交互 Shell；91.5k star，BSD-3-Clause（2026-11-01 收录，只索引未本地装；隐身绕过能力使用时注意目标站 ToS） | https://github.com/D4Vinci/Scrapling |
| MediaCrawler | 多平台自媒体数据采集工具（工具项目，非 Skill）：基于 Playwright 保登录态 + JS 取签名（免逆向加密），支持小红书、抖音、快手、B站、微博、贴吧、知乎 7 平台的关键词搜索、指定帖子、二级评论与创作者主页抓取，带登录态缓存、IP 代理池、评论词云与 WebUI，数据可存 CSV/JSON/Excel/SQLite/MySQL 并可下载封面/视频/图文；70.7k star，自定 Non-Commercial Learning License 1.1（仅限非商业学习研究、禁止商用与大规模爬取，抓取可能碰各平台 ToS、风控自担；另有付费 Pro 版含断点续爬/多账号；2026-11-09 收录，只索引未本地装） | https://github.com/NanmiCoder/MediaCrawler |
| short_videos | 多平台短视频去水印解析 API（工具项目，非 Skill）：分享链接/文案进、无水印直链 + 封面/作者/音乐/时长等元数据出，统一 JSON、聚合入口自动识别平台分发；覆盖抖音（免 Cookie、原画/图集/实况，另有 Cloudflare Workers 版）、快手、小红书、B站、微博、头条、皮皮虾/搞笑、最右、网易云及豆包/即梦 AI 视频，PHP 8+ 零依赖自部署、另有公共实例 api.bugpk.com；1.0k star，MIT（2026-11-05 收录，只索引未本地装；去水印下载碰平台 ToS 与原作者版权，仅供学习研究、二创须自担授权，解析靠平台未公开接口、易随平台改版失效） | https://github.com/jiuhunwl/short_videos |

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
