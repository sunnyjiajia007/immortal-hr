⚔️ 职场修真录 | 凡人飞升版

“凡人看简历，仙师看根骨。”

还在用冷冰冰的 Excel 表格管理团队？
职场修真与炼器 Pro —— 一款基于 Google Gemini AI 的组织进化法器，将枯燥的人力资源管理转化为一场热血的凡人流修仙游戏。

📸 宗门图录 (Screenshots)

<div align="center">
<img src="https://www.google.com/search?q=https://via.placeholder.com/800x450%3Ftext%3DImmortal%2BDashboard%2BPreview" alt="主界面预览：韩立的属性面板" width="800"/>
<p><i><img width="1488" height="933" alt="image" src="https://github.com/user-attachments/assets/ce7de225-ff8c-4c3d-9d49-a91a5f2d0340" />
</i></p>
</div>

🔮 核心神通 (Features)

1. 识海灵气监测 (Soul Energy & Burnout)

拒绝道心破碎（猝死/离职）。系统首创 [灵气值算法]，结合 [意志坚韧] (Toughness) 与 [因果负荷] (Stress)，精准计算员工的“道心”状态。

灵气充盈：道心稳固，可担重任。

灵气枯竭：心魔已生，速速介入！

2. 天道酬勤算法 V3.0 (Roots vs Karma)

我们将能力拆解为 [先天根骨] (天赋，权重 0.7) 与 [后天造化] (技能，权重 1.3)。

勤能补拙：正如韩立靠小绿瓶逆天改命，后天技能的提升对战力的加成是天赋的近两倍！

单项专精：任一属性修至大圆满（90+），触发额外战力加成。

3. 洞察天机 (AI Divination)

接入 Google Gemini 2.0 Flash 模型，AI 化身“藏经阁长老”。

深度推演：根据当前属性，一针见血指出晋升瓶颈（如：“此子虽神识强大，但由于不善言辞，难当大任”）。

仙音垂怜：集成 TTS 语音合成，让 AI 导师用温润如玉的声音抚慰员工（已修复音色为 Puck）。

战果洗炼：自动将流水账日志提炼为符合 STAR 原则 的专业业绩描述，并辅以修真术语润色。

4. 凡人角色预设 (Pre-set Characters)

为了方便演示，宗门名册已预置 5 位经典角色，各有千秋：

韩立：心思缜密，执行力与生存能力极强（抗压王）。

厉飞雨：虽然根骨一般，但靠透支潜力达成目标（卷王）。

南宫婉：气质高雅，领导力出众（管理型）。

大衍神君：才情惊艳，技术造诣登峰造极（技术大牛）。

🛠️ 法宝构造 (Tech Stack)

本项目采用 单文件 (Single-File) 纯前端架构，无后端，无数据库，即开即用！

界面 (UI): HTML5 + Tailwind CSS (CDN) - 暗黑玻璃拟态风格。

图表 (Charts): Chart.js - 动态雷达图与成长曲线。

灵智 (AI Core): Google Gemini API (GenerateContent + TTS)。

字体 (Font): 引入 "Ma Shan Zheng" 毛笔字体，仙气飘飘。

🚀 修炼法门 (Quick Start)

1. 获取法器

克隆本仓库或直接下载 index.html 文件。

2. 注入灵力 (配置 API Key)

为了开启 AI 功能，您需要一个 Google Gemini API Key。

用文本编辑器打开 index.html。

找到代码顶部的配置区（约第 285 行）：

const apiKey = "在此处填入你的_GOOGLE_API_KEY"; 


保存文件。

3. 开宗立派

直接用浏览器（推荐 Chrome/Edge）打开 index.html 即可开始使用。

📖 宗门秘籍 (Customization)

自定义职级：在页面左侧底部的“宗门法则”按钮中，您可以直接修改文本框内容来定义公司的 P 序列或 M 序列。

格式：职级名称 (战力:分数)

示例：P1 杂役弟子 (战力:40)

数据存档：点击右上角的“刻录道果”，当前状态会自动保存到内存中（刷新即逝，如需持久化可对接 localStorage）。

📜 藏经阁守则 (License)

MIT © 2026 - 欢迎各路道友 Fork 修改，共证大道。
