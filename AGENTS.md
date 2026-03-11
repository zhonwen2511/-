# AGENTS.md - 项目开发规范

## 1. 项目信息

- **项目名称**: CampusBook 校园二手书交易平台
- **技术栈**: Vue.js 3 + Node.js + Express + SQLite
- **仓库地址**: https://github.com/zhonwen2511/normalwork

## 2. 开发规范

### 2.1 代码规范
- 使用中文注释
- 保持代码简洁，避免冗余
- 遵循需求文档进行开发

### 2.2 Git 提交规范
- 使用清晰的中文提交信息
- 提交格式: `类型: 描述`
  - `feat`: 新功能
  - `fix`: 修复bug
  - `docs`: 文档
  - `refactor`: 重构

### 2.3 目录结构

```
CampusBook/
├── frontend/           # 前端 Vue.js 项目
│   ├── src/
│   │   ├── components/
│   │   ├── views/
│   │   ├── router/
│   │   ├── api/
│   │   └── store/
│   └── package.json
├── backend/            # 后端 Node.js 项目
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── database/
│   └── server.js
├── 需求文档.md
├── 需求文档v1.0.md
└── AGENTS.md
```

## 3. 功能模块

| 模块 | 优先级 | 状态 |
|------|--------|------|
| 用户系统 | P0 | 待开发 |
| 书籍发布 | P0 | 待开发 |
| 书籍浏览/搜索 | P0 | 待开发 |
| 购物车 | P1 | 待开发 |
| 订单管理 | P1 | 待开发 |

## 4. 开发流程

1. 按照需求文档开发功能
2. 进行必要的测试
3. 确保代码规范
4. 提交并推送代码

---

**维护者**: CampusBook 开发团队  
**更新日期**: 2026-03-11
