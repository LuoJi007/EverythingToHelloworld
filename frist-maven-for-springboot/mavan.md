# `maven` 简单使用

## `maven` 基本命令

### 创建一个最基本的 `maven` 项目

```cmd
mvn archetype:generate
```

### 编译项目

需要在项目根目录下运行

```cmd
mvn clean compile
```

### 单元测试

`test` 前，会先执行 `compile`，即先编译，再执行单元测试.

```cmd
mvn clean test
```

### 项目打包

通常我们会把 `java` 项目打包成 `jar` 包或 `war`包，`maven` 中打包的命令为

```cmd
mvn clean package
```

### 项目运行

```cmd
mvn exec:exec
```

### 项目部署

```cmd
mvn clean jboss-as:deploy
```
