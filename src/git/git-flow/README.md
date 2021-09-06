## Git commit message 提交日志规范

### 使用 commitlint + husky 工具对 commit message 进行检查

- 配置使用 vscode 进行 commit log 的编写，`git config --global core.editor code -w`

- 使用 npm init -y 初始化工程，生产 packag.json
- 安装 husky，使用我们可以对 git hooks 进行配置(vue-cli 的 yorkie 也行)
- 安装 commitlint 对提交日志进行检查

```bash
npm init -y
npm install @commitlint/cli @commitlint/config-conventional husky -D
```

### 使用 standard-version 自动生成 CHANGELOG
