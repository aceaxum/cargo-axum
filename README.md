# cargo-axum

快速创建 axum 脚手架

## 安装

```bash
cargo install cargo-axum
```

## 使用

```bash
cargo axum [选项] <子命令>
```

## 子命令

- `new`：创建一个新的 axum 应用

- `init`：在已存在的目录里初始化一个 axum 应用

- `db <NAME>`：创建一个数据库操作模块



## 选项

- `--no-db`：创建或初始化时，不使用数据库

- `--no-redis`：创建或初始化时，不使用redis

- `--no-session`：创建或初始化时，不使用session

- `--no-template`：创建或初始化时，不使用模板引擎

- `--json`：创建一个返回 json 响应的应用

- `--with-json`：创建一个同时响应 HTML 和 JSON 的应用

