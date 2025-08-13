# 双创项目申报平台（Innovation & Entrepreneurship Project Platform）

这是一个完整的“双创项目申报平台”，支持全球人才申报创业/创新项目、浏览政策、提交简历和创业计划书，并支持中英文界面切换。

## 🧩 技术栈

- **前端**：React + TypeScript + i18next + Ant Design
- **后端**：Node.js + Express + JWT + Swagger UI
- **数据库**：MySQL
- **部署**：Docker + Nginx + Ubuntu 服务器
- **多语言**：中英文切换按钮

## 📁 项目结构
innovation-entrepreneurship-platform/ ├── frontend/ # React 前端 ├── backend/ # Node.js 后端 ├── database/ # 数据库脚本 ├── docker-compose.yml # Docker 部署配置 ├── README.md └── 部署指南.md
## 📦 安装说明

请参考 `部署指南.md` 文档，了解如何本地运行和部署到服务器。

## 🌐 接口文档

后端提供 Swagger UI 接口文档，访问 `/api-docs` 即可查看。

## 🌍 多语言支持

支持中英文切换按钮，页面内容和接口响应均为中英文。
