# .github
这个仓库包含了 Osynicite 组织范围的配置和模板。它提供了在组织的所有仓库中共享的默认社区健康文件、模板和工作流程。

## 📂 仓库结构
```plaintext
.github/
├── actions/                # 自定义 Actions
│   ├── rust-bench/        # Rust 基准测试
│   ├── rust-doc/          # Rust 文档生成
│   ├── rust-lint/         # Rust 代码检查
│   ├── rust-setup/        # Rust 环境设置
│   └── rust-test/         # Rust 测试运行
├── ISSUE_TEMPLATE/        # Issue 模板
│   ├── bug_report.md      # 缺陷报告模板
│   ├── config.yml         # Issue 配置
│   └── feature_request.md # 功能请求模板
├── PULL_REQUEST_TEMPLATE/ # PR 模板
│   └── pull_request.md    # PR 模板
├── profile/              # 组织简介
│   └── README.md         # 公开的组织简介
├── SECURITY/             # 安全政策
│   ├── policy.md         # 安全政策 (英文)
│   ├── policy-cn.md      # 安全政策 (中文)
│   └── policy-ru.md      # 安全政策 (俄文)
├── workflow-templates/   # 工作流模板
│   ├── rust-project.properties.json
│   └── rust-project.yml
├── workflows/           # 组织级工作流
│   ├── benchmark.yml    # 基准测试
│   ├── ci.yml          # 持续集成
│   └── release.yml     # 发布流程
├── CODE_OF_CONDUCT.md   # 行为准则 (英文)
├── CODE_OF_CONDUCT_RU.md # 行为准则 (俄文)
├── CODE_OF_CONDUCT_ZH.md # 行为准则 (中文)
├── CODEOWNERS           # 代码所有者
├── CONTRIBUTING.md      # 贡献指南 (英文)
├── CONTRIBUTING_CN.md   # 贡献指南 (中文)
├── CONTRIBUTING_RU.md   # 贡献指南 (俄文)
├── FUNDING.yml         # 赞助配置
├── LICENSE             # 许可证
├── README.md           # 主说明文件
└── SUPPORT.md          # 支持指南
```

## 🔍 包含内容
### 社区健康文件
在组织的所有仓库中使用的默认文件：
- 多语言贡献指南（英文、中文、俄文）
- 多语言行为准则
- 工作流配置
- 赞助配置
- 代码所有者

### 工作流模板
针对 Rust 项目的现成 GitHub Actions 工作流：
- 持续集成
- 基准测试
- 发布流程

### 自定义 Actions
常见任务的可重用 actions：
- Rust 环境设置
- 代码检查
- 测试运行
- 文档生成
- 基准测试

## 🛠️ 使用方法
### 仓库维护者
1. 创建新工作流时，请查看 Actions 标签中的工作流模板
2. 在工作流中引用自定义 actions：
   ```yaml
   - uses: ./.github/actions/rust-setup
   ```
3. 遵循贡献指南以保持一致性
4. 通过提出 issue 或 PR 帮助我们改进这些配置

### 贡献者
1. 在做出贡献之前阅读 CONTRIBUTING.md
2. 使用提供的 issue 和 PR 模板
3. 设置新项目时查看工作流模板

## 📝 注意事项
- 这些配置作为默认值，可以被单个仓库覆盖
- 创建新工作流时，工作流模板在 "Actions" 标签中可用
- 自定义 actions 可以从组织中的任何仓库引用

## 🔄 维护
此仓库由 Osynicite 团队维护。如果您有改进建议：
1. 打开 issue 讨论提议的更改
2. 提交带有更新的 PR
3. 确保相应更新文档

## 📮 联系方式
- [团队讨论板](https://github.com/orgs/Osynicite/discussions)
- Discord: [加入我们的 Discord](https://discord.gg/osynicite)