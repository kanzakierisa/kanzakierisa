### Hi, I'm kanzakierisa 👋

我是杭州电子科技大学软件工程 2026 级本科生（大一在读），有 C++ 算法竞赛基础。目前我把主要精力放在 **大模型 RAG（检索增强生成）/ 可评测 Agent Harness** 与 **Go 后端工程实践** 上，探索怎样做出边界清晰、结果可信、能持续迭代的 AI 产品。

#### 🏆 算法与竞赛基础
- **CCF CSP-S 2024（提高级）省一等奖** · **CCF NOIP 2024 省二等奖**
- 长期训练 C++ 图论、动态规划与数据结构，习惯先推演复杂度边界与极端 Case，再动手写工程代码。

#### 🚀 个人项目与学习轨迹
- **[knowledge-qa-harness](https://github.com/kanzakierisa/knowledge-qa-harness)** — 可评测、可溯源的多项目知识问答与文档治理工作台（进行中）
  - 这是我用纯 Go 和 MySQL 8 从零搭建的问答系统，不依赖重型编排框架：通过「先引后答」（Quote-First）协议与句级引用硬校验防止模型胡编，用 52 题基准集与 39 题对抗盲测守住拒答底线，并在文档更新时自动触发局部回归（Doc CI/CD）避免破坏原有问答。
  - **在线体验**：[交互 Demo（免配置即点即用）](https://kanzakierisa.github.io/knowledge-qa-harness/) · [3 分钟配音演示视频](https://github.com/kanzakierisa/knowledge-qa-harness/releases/download/stage13-delivered/demo_video_voiced.mp4)
- **[hdu-lostfound](https://github.com/kanzakierisa/hdu-lostfound)** — 杭电校园失物招领平台
  - 我基于 Go + Gin + sqlx + MySQL 8 与 Vue 3 独立开发，完成 19 个业务接口，重点打磨 6 位唯一身份凭证核销与数据库生成列防冒领闭环、SQL 层联系方式隐私隔离、核销后颁给拾主的「拾金不昧电子荣誉证书」，以及可解释的中文 2-gram 四维智能匹配。
- **miniledger** — 零框架手写记账应用（基础夯实中）
  - 刻意不借助 AI 与第三方 Web 框架，完全用 Go 标准库和原生 HTML/CSS/JS 独立完成全链路编码，夯实工程基本功。

#### 🛠 正在使用的工具栈
`C++` · `Go (Gin)` · `MySQL 8` · `Docker` · `RAG / BM25 / Embedding` · `Agent Evaluation`

📫 交流联系：`2382531945@qq.com`
