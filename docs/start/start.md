# 准备

1. 项目由 [Rust](https://www.rust-lang.org/) 所写，插件也需用 [Rust](https://www.rust-lang.org/) 写，请确保本地已安装。

2. 虽然 Kovi 上手非常简单，但是 Kovi 需要使用 Rust 进行开发，请确保你拥有 [Rust](https://www.rust-lang.org/) 基础，至少需要掌握到多线程共享状态，才能较为轻松的开发 Kovi 插件。

3. Kovi 只是一个 OneBot 插件开发框架，你需要准备 OneBot 服务端。如果没有的话，需要找找，并部署起来。

4. 将你的 OneBot 服务端，配置成正向 WebSocket 模式。

注意⚠️，Kovi 目前只支持 OneBot V11 正向 WebSocket 协议。