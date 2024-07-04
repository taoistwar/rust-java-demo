Rust 和 Java 交互的 Demo 工程

## 构建 & 运行

1. `cargo build` 编译 Rust 的 JNI 模块
2. `mvn compile` 编译 Java 代码
3. `java -Djava.library.path=target/debug -classpath target/classes pers.metaworm.RustJNI` 运行 demo
   - 注：在 PowerShell 中执行失败，在 cmd 中执行成功。

## 文章

[Rust 与 Java 交互-JNI 模块编写-实践总结](https://zhuanlan.zhihu.com/p/568062165)
