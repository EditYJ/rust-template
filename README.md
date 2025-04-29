# {{ project-name }}

环境配置
安装 Rust
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

安装 cargo generate
```shell
cargo install cargo-generate
```
cargo generate 是一个用于生成项目模板的工具。它可以使用已有的 github repo 作为模版生成新的项目。

然后可以通过模版生成项目

```shell
cargo generate EditYJ/rust-template
```

安装 [pre-commit](https://pre-commit.com/)
pre-commit 是一个代码检查工具，可以在提交代码前进行代码检查。

brew install pre-commit
// 或者
pip install pre-commit

pre-commit 初始化配置文件

```shell
pre-commit sample-config > .pre-commit-config.yaml
```

安装成功后运行 pre-commit install 即可。

安装 Cargo deny
Cargo deny 是一个 Cargo 插件，可以用于检查依赖的安全性。

cargo install cargo-deny --locked

生成默认的 deny 配置文件

cargo-deny init

安装 typos
typos 是一个拼写检查工具。

cargo install typos-cli

安装 git cliff
git cliff 是一个生成 changelog 的工具。

cargo install git-cliff

安装 cargo nextest
cargo nextest 是一个 Rust 增强测试工具。

cargo install cargo-nextest --locked
