# 👋 你好，我是秦岭

🎓 华东师范大学 软件工程硕士在读  
💻 Java 后端 / AI 应用开发 / 大数据与智能系统方向  
🚀 关注 Spring Boot、Redis、RAG、Agent、MCP、分布式系统与工程化落地  

---

## 🙋‍♂️ 关于我

我是一名软件工程方向的研究生，目前主要关注 **Java 后端开发、AI 应用开发、RAG 知识库系统与智能体工程化**。

我有较完整的后端项目开发经验，熟悉 Spring Boot、MySQL、Redis、RabbitMQ、WebSocket 等技术栈，也参与过工业测试用例生成、可视化测试用例编写工具、智能协同云图库和旅游 AI 智能体等项目。

目前我正在持续学习和实践：

- Java 后端开发与微服务工程化
- Redis + Caffeine 多级缓存与高并发优化
- RAG 知识库、Tool Calling、MCP 与智能体架构
- AI 应用开发中的 Prompt Engineering 与 Vibe Coding
- Vue / Electron 等前端与桌面端应用开发

---

## 🛠 技术栈

### 后端开发

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring%20AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

### AI 应用开发

![RAG](https://img.shields.io/badge/RAG-4B8BBE?style=flat-square)
![LLM](https://img.shields.io/badge/LLM-000000?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-1E90FF?style=flat-square)
![Agent](https://img.shields.io/badge/Agent-8A2BE2?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-FFB000?style=flat-square)

### 前端与工具

![Vue](https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

---

## 📌 项目经历

### 🖼️ 共影智能协同云图库

基于 **Spring Boot + Redis + COS + AI + WebSocket + Vue** 的智能协同图片管理平台，支持公共图库、私有图库、团队图库、图片管理、团队协作和 AI 生图等功能。

项目亮点：

- 使用 Redis + Caffeine 构建多级缓存，将热门图片查询接口平均响应时间从约 200ms 优化至 50ms 以内
- 基于 Sa-Token 多 LoginType 机制设计用户 / 团队双账号体系
- 构建 RBAC 权限模型，实现统一鉴权中间层，降低业务代码权限耦合
- 基于腾讯云 COS 生命周期策略、WebP / AVIF 压缩和 MD5 去重机制，降低存储成本
- 使用 WebSocket 实现多人实时协作编辑
- 引入 Disruptor 无锁队列进行消息异步处理，降低线程竞争与延迟
- 集成内容安全 API 与 RabbitMQ 人工审核队列，实现审核流程自动化

---

### 🧭 灵旅 AI 智能体

基于 **Spring Boot + Spring AI + RAG + Tool Calling + MCP + Vue** 的旅游智能体项目，为用户提供出行规划、旅游攻略、多轮对话和知识库问答能力。

项目亮点：

- 构建 RAG 旅游攻略知识库，实现文档 ETL、PGVector 向量存储和自动元信息标注
- 结合多查询扩展、实体扩展和查询重写机制，提升知识检索召回率和回复准确度
- 基于文件系统和 Kryo 序列化实现 ChatMemory 持久化，解决服务重启后记忆丢失问题
- 使用 Spring AI MCP Server 集成 Pexels 图片 API，支持 AI 联网检索图片资源
- 实现 Stdio 和 SSE 两种 MCP 传输模式，适配不同部署场景
- 参考 OpenManus 实现支持 Human-in-the-Loop 的分层智能体架构
- 通过步骤限制、状态管理和死循环检测提升智能体运行稳定性

---

### 🧪 工业测试用例自动生成方案

在工业控制安全相关实习中，基于大模型 Prompt Engineering 构建工业测试用例自动生成方案。

主要工作：

- 针对真实工业场景设计多轮 Prompt 模板与约束策略
- 引导大模型生成结构化中间表示
- 结合规则驱动与约束搜索生成可执行测试用例
- 通过 Few-shot 示例增强和规则校验机制减少大模型幻觉
- 提升测试用例覆盖率，增强工业场景下测试生成的可靠性

---

### ✈️ 可视化测试用例编写工具

在机电软件与电子硬件相关实习中，参与基于 **Node.js + Electron + Vue** 的可视化测试用例编写工具设计与开发。

主要工作：

- 支撑上千条测试用例的高效管理与编写
- 支持约束求解工具和大模型自动生成结构化测试用例
- 针对本地 JSON 存储场景设计加载性能优化方案
- 通过“摘要 + 详情懒加载 + 本地缓存”机制减少全量 IO 和重复解析开销
- 将系统加载响应时间从约 80ms 优化至 20ms 以内

---

## 🎓 教育经历

- 华东师范大学 软件工程 硕士  
  2024.09 - 2027.06

- 河海大学 软件工程 本科  
  2020.09 - 2024.06

---

## 📊 GitHub 数据

## 📊 GitHub 数据

![Profile Views](https://komarev.com/ghpvc/?username=FishMoun&style=flat-square)

![GitHub followers](https://img.shields.io/github/followers/FishMoun?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/FishMoun?style=flat-square)

<!-- GitHub Readme Stats 公共服务偶尔会限流，若显示异常可暂时注释 -->
<!--
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=FishMoun&show_icons=true&theme=transparent)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs?username=FishMoun&layout=compact&theme=transparent)
-->

---

## 📫 联系方式

- GitHub: [github.com/FishMoun](https://github.com/FishMoun)
- Email: qinling321@foxmail.com

---

## 🌱 最近关注

- Java 后端高并发与缓存优化
- RAG 知识库系统与检索增强生成
- Spring AI、MCP 与智能体工程化
- AI Coding / Vibe Coding 在实际项目中的落地
- 大模型在测试用例生成、自动化分析和软件工程中的应用
