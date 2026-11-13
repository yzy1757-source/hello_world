# hello_world

这是一个入门示例项目，用于学习和练习 Git 与 GitHub 的基本使用流程。

## 项目简介

- 创建仓库并编写第一个文件
- 提交（commit）更改
- 推送（push）到 GitHub 远程仓库

## 使用方法

```bash
git clone https://github.com/yzy1757-source/hello_world.git
cd hello_world
```

欢迎以此为起点，继续探索更多功能！

## 如何参与

### 提交 Issue

1. 打开仓库的 **Issues** 页面，点击 **New issue**。
2. 填写清晰的标题，并在正文中说明问题或建议；如果是 Bug，请附上复现步骤和期望结果。
3. 点击 **Submit new issue** 提交。

### 提交 Pull Request

1. 点击右上角 **Fork** 将仓库复制到自己的账号下，然后克隆到本地：
   ```bash
   git clone https://github.com/<你的用户名>/hello_world.git
   cd hello_world
   ```
2. 新建分支并修改：
   ```bash
   git checkout -b my-feature
   ```
3. 提交并推送：
   ```bash
   git add .
   git commit -m "描述你的修改"
   git push origin my-feature
   ```
4. 在 GitHub 上打开你的分支，点击 **Compare & pull request**，填写标题和说明（可关联相关 Issue，如 `Closes #1`），然后提交。
5. 等待维护者审阅，并根据反馈继续修改。
