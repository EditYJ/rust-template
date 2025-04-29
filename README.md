# - {{ project-name }} -

## 环境配置

### 安装 Rust

```shell
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

### 安装 cargo generate
```shell
cargo install cargo-generate
```
cargo generate 是一个用于生成项目模板的工具。它可以使用已有的 github repo 作为模版生成新的项目。

安装完成后，可以通过此模版生成项目

```shell
cargo generate EditYJ/rust-template
```

### 安装 pre-commit
pre-commit 是一个代码检查工具，可以在提交代码前进行代码检查。

```shell
brew install pre-commit
// 或者
pip install pre-commit
```
安装成功后运行 `pre-commit install` 即可。

### 安装 Cargo deny
Cargo deny 是一个 Cargo 插件，可以用于检查依赖的安全性。

```shell
cargo install cargo-deny --locked
```

### 安装 typos

typos 是一个拼写检查工具。

```shell
cargo install typos-cli
```

### 安装 cargo nextest

cargo nextest 是一个 Rust 增强测试工具。

```shell
cargo install cargo-nextest --locked
```

## 🌟 进阶之路
🔥 关注公众号「哈希茶馆」解锁配套教程，实时获取后续章节更新

📌 **Star本仓库不迷路** → 开发技巧持续更新中！

![white_full.png](https://s2.loli.net/2025/04/19/MIJQjzq3RkLb1xB.png)