# Hi, I'm Delanri 

独立开发者 · AI 产品工程师 · 远程工作  
Indie developer building AI companion & agent products · Remote only

我把一个想法从产品定义一路做到上线：角色与交互设计、系统架构、前后端开发、部署运维，都是一个人完成。  
日常用 Claude Code 开发：架构和判断由我负责，实现交给 AI，改完先测试验证再上线。

## Reso — 给想被记住的人

→ [reso.love](https://reso.love)

面向海外用户的 AI 伴侣，一个人不到一个月从零上线，现在邀请制内测中。

人想被记住，是因为想被看见。可大多数 AI 伴侣的记忆藏在后台：记了什么、记错了什么，用户都不知道。Reso 把记忆摊开：

- **记忆看得见**：角色记得你的每一件事都写在一页上，用平常的话写，能改、能删。
- **记之前先问**：角色学到新的事，会先问你要不要留；你换了说法，新旧两句合成一条，等你确认。
- **每天写日记**：每天夜里，角色用自己的话把这一天写下来。
- **记得准不准，有数据**：自建记忆回归评测，假用户埋 20 个细节，答对 19 个；每一次模型调用都录下来，答错了能回放到出错的那一步。

## 其他作品

- **Auren** — 我自己每天在用的 AI 陪伴系统，从 2026 年 5 月用到现在。16 路并行组装上下文，五层记忆，检索阈值按实测相似度分布标定；接入 Apple Watch 健康数据，由门控模型判断什么时候该提起。已通过 iOS TestFlight 装到手机上日常使用。→  [auren-showcase](https://github.com/delanri/auren-showcase)
- **Mira** — 雨夜咖啡馆里的实时互动角色：语音对话可打断，表情、动作、场景随对话变化，按台词实时生成照片。72 小时完成，含 58 个自动化测试。→ [mira-scene](https://github.com/delanri/mira-scene)

## 技术栈

Vue 3 · Capacitor (iOS) · Node.js / Express · Python / Flask · PostgreSQL · Qdrant · RAG · 多模型编排 · Docker · Nginx · Codemagic CI/CD

## 联系

📮 delanri1107@gmail.com · 只接受远程，偏好文字沟通
