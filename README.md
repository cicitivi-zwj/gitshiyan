# GIT

> 项目简介：一句话说明这个仓库用来做什么。

## 目录结构

```
.
├── .editorconfig      # 编辑器统一格式约定
├── .gitattributes     # 换行符 / 二进制文件处理规则
├── .gitignore         # 忽略规则（系统、IDE、缓存、密钥、构建产物）
└── README.md
```

## 开始使用

1. 克隆仓库：

   ```bash
   git clone <仓库地址>
   cd GIT
   ```

2. 按你的技术栈补充工程文件（依赖清单、源码目录、测试目录等）。

3. 首次提交前检查忽略规则是否生效：

   ```bash
   git status --ignored
   ```

## 约定

- 提交信息建议使用 `feat: / fix: / docs: / chore:` 等前缀，保持历史可读。
- 私有配置（`.env`、密钥、凭证）已被 `.gitignore` 排除，请改用 `.env.example` 之类的模板文件说明所需变量。
- 换行符由 `.gitattributes` 统一管理，避免跨平台 diff 噪声。

## 许可证

如需开源，请在此补充许可证信息（例如 MIT）。
