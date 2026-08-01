# 汽车商业保险（车险理赔）与机械工程设计基础 — 免费资源汇总

本文件为为考试与自学准备的免费/开源教材与课程汇总，已整理为两部分：一是汽车商业保险（重点车险理赔、理赔实务、行业规范）；二是机械工程设计基础（机械制图、材料力学、机械原理、CAD 等）。所有资源均为合法免费在线阅读或开源/可下载版本（按站点政策可能需注册）。

---

## 一、汽车商业保险（车险理赔） — 优先阅读项（中文）

1. 人民大学 / 学堂在线：保险学（慕课）
   - 简述：系统讲授保险学基础、保险合同、理赔与风险管理，偏中国制度与实务。
   - 访问：免费在线课程（需注册）
   - 链接：https://www.xuetangx.com/course/CMRU08003003041/8221517

2. 中国银行保险监督管理委员会（CBIRC） — 监管文件与行业规范
   - 简述：权威监管政策、理赔规范、消费者保护等官方文件（必读）。
   - 访问：官网公开文档
   - 链接：http://www.cbirc.gov.cn/

3. 中国保险行业协会（行业报告、理赔指引）
   - 简述：行业白皮书、理赔实践指引与统计报告，了解业务实践与反欺诈趋势。
   - 链接：http://www.iachina.cn/

4. Internet Archive — 保险学/保险实务的历史教材与可借阅资料
   - 简述：可借阅/下载若干保险学教材（需注册 Internet Archive 借阅或下载）。
   - 链接：https://archive.org/

5. 高校公开课与课件（检索示例）
   - 搜索关键词：保险理赔 实务 课程 PPT / 保险理赔 案例
   - 常用入口：中国大学MOOC https://www.icourse163.org/、学堂在线 https://www.xuetangx.com/。

---

## 二、面向车险技术类（便于实现理赔自动化）

推荐先从车牌识别与照片结构化入手（这些模块常用作理赔证据抽取）：

1. PlateRecognition（车牌识别）
   - 语言：Python / C++，许可证：MIT
   - 链接：https://github.com/pcb9382/PlateRecognition

2. HyperLPR（中文车牌识别）
   - 语言：Python / C++，许可证：MIT
   - 链接：https://github.com/szad670401/HyperLPR

3. cnlpr（Gitee：中文车牌识别实现）
   - 语言：Python，许可证：Apache-2.0
   - 链接：https://gitee.com/live106/cnlpr

4. yolo26-plate（YOLO 系列车牌工程化实现）
   - 语言：Python，许可证：AGPL-3.0
   - 链接：https://github.com/we0091234/yolo26-plate

5. 说明与扩展建议
   - 端到端车损估价/自动定损的开源仓库较少，通常需把车牌识别 + 事故照片的目标检测/语义分割（Detectron2、YOLO segmentation、SAM 等）结合，再按零部件/人工工时表做估价。

---

## 三、机械工程设计基础（用于考试与工程练习）

1. MIT OpenCourseWare — Mechanical Engineering
   - 内容：机械工程、力学、材料、设计课程讲义与视频（英文）
   - 访问：免费：https://ocw.mit.edu/
   - 课程查找：https://ocw.mit.edu/courses/find-by-topic/#cat=engineering&subcat=mechanicalengineering

2. OpenStax — University Physics（力学部分）
   - 内容：经典力学（动力学/静力学）基础教材，开放许可（CC BY）
   - 链接：https://openstax.org/details/books/university-physics-volume-1

3. Autodesk Design Academy（CAD / Fusion 360 / AutoCAD 入门）
   - 内容：官方免费 CAD 教程与项目
   - 链接：https://academy.autodesk.com/

4. LibreCAD（开源 2D CAD）与教程
   - 内容：开源二维 CAD 软件，适合工程制图练习（GPL 许可）
   - 链接：https://librecad.org/ 和 https://github.com/LibreCAD/LibreCAD

5. 高校公开讲义（机械设计/工程制图/材料力学）
   - 建议检索词：机械设计 讲义 PDF、工程制图 讲义、材料力学 讲义（同济/清华/华中科技等高校常有公开课件）

---

## 四、考试复习与 7 天速成计划（建议）

车险业务方向（6 天）
- Day 1：完成人民大学保险学慕课前两章（理解保险基本概念、保险合同）。
- Day 2：阅读 CBIRC 与行业协会的理赔规范与样例文件（摘录要点）。
- Day 3：做 2-3 个理赔流程图（立案—查勘—鉴定—核损—理赔/拒赔），并记住关键时限与证据要求。 
- Day 4：阅读高校“保险理赔实务”PPT/Cases，做题练习。 
- Day 5：复盘反欺诈要点（证据链、异常交易/时间/地点、图像比对思路）。
- Day 6：整理一页考试速记卡（流程、法规、常见题型）。

机械设计基础（7 天）
- Day 1：阅读 OpenStax 力学基础章节（静力学）。
- Day 2：学习工程制图基础（投影、尺寸标注），使用 LibreCAD 练习绘制投影图。 
- Day 3：材料力学—应力/应变基础与常见断面计算。 
- Day 4：机械原理/运动传递基础（齿轮、轴承、联轴器）。
- Day 5：CAD 实操（Autodesk Design Academy 上完成 1 个入门项目）。
- Day 6：做 5 个典型计算题（轴强度/弯矩/轴承选型）。
- Day 7：整理考试速记卡与常错题集。

---

## 五、我的操作记录与后续可选项

我已将本汇总作为文件添加到仓库：
路径：`auto-insurance-and-mechanical-design/README.md`

下一步我可以为你继续做：
- 将本文件拆分为两个独立 Markdown（车险资源、机械设计资源），并添加更多直达 PDF/章节链接；
- 在仓库中添加 `exam-prep/` 目录，包含 7 天速成计划的可打印速查卡（Markdown / PDF）；
- 自动生成一个 bookmark HTML（包含所有链接，便于离线保存）；
- 帮你 fork 上述技术型 GitHub 仓库（如 PlateRecognition）到你的账号并在仓库内添加快速运行指南。

请告诉我你要我继续做哪一项（或允许我一次性全部添加）。
