skill-creator-methodology
将教材 / 规范 / 文档转化为 TRAE AI Skill 的通用方法论

📖 简介
本仓库是一个 TRAE AI Skill，提供将任意教材、规范、文档转化为 TRAE AI Skill 的通用方法论与标准模板。

当用户要求"创建 skill"、"把规范做成技能"、"编写 skill 文件"时，AI 将自动遵循本方法论的 5 步流程，输出符合 TRAE 规范的 SKILL.md 及配套 README.md。

✨ 功能特性
5 步标准流程 — 调研格式 → 提炼要点 → 编写 SKILL.md → 编写 README.md → 打包交付
SKILL.md 标准模板 — 含 frontmatter、适用范围、规范正文、示例、自检清单
README.md 标准模板 — 含简介、特性、安装、触发场景、参考来源
6 大设计原则 — 触发明确、强制与建议分离、抽象与具象结合、保留原典风格、可自检、命名语义化
自检清单 — 创建完成后快速校验规范符合性
📁 仓库结构
skill-creator-methodology/
├── SKILL.md    # 技能主文件（AI 遵循的完整方法论）
└── README.md   # 技能说明文档
🚀 安装使用
全局安装（推荐）
git clone https://github.com/your-username/skill-creator-methodology.git ~/.trae/skills/skill-creator-methodology
项目级安装
mkdir -p .trae/skills
git clone https://github.com/your-username/skill-creator-methodology.git .trae/skills/skill-creator-methodology
手动安装
下载 最新 Release 的压缩包，解压到 ~/.trae/skills/ 或项目的 .trae/skills/ 目录下即可。

🎯 触发场景
当 AI 识别到以下关键词或场景时，本技能将自动启用：

创建 skill / 编写技能 / 制作 skill 文件
把规范/教材/文档做成 skill
skill 方法论 / skill 编写规范
如何写一个 skill / skill 怎么创建
🔧 核心流程速览
第 1 步  调研 Skill 规范格式（文件格式、字段、存储位置）
第 2 步  分析源材料，提炼规范要点（语法要素 + 书写规范 + 示例）
第 3 步  编写 SKILL.md（按标准模板）
第 4 步  编写 README.md（按标准模板）
第 5 步  打包与交付（tar.gz + 仓库 README）
📐 关键设计原则
原则	说明
触发条件要明确	description 写清"何时用"+"何时不用"
强制与建议分离	"必须/不得" vs "建议/可以"
抽象与具象结合	表格给规则，代码块给示例
保留原典风格	保留术语和命名约定
可自检	末尾清单让 AI 自我校验
命名要语义化	skill 名体现来源与用途
📚 适用领域
本方法论适用于任何"将教材/规范/文档转化为 AI Skill"的场景，例如：

编程语言规范（类 C 语言、伪代码风格）
代码风格指南（Google Style、Airbnb Style）
学术写作规范（GB/T 7714 引注格式）
框架使用约定（Vue 组件规范、React Hooks 规范）
任何需要 AI 一致遵循的规则集
📄 许可证
MIT License