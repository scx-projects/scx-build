# SCX Build

## Maven

``` xml
<parent>
    <groupId>dev.scx</groupId>
    <artifactId>scx-parent</artifactId>
    <version>{version}</version>
    <relativePath/>
</parent>
```

## 快速开始

#### 1. 复制 [scx-build.ps1](./scx-build.ps1) 到您的项目根目录 .

```text
your-project
    ├── src
    ├── pom.xml
    └── scx-build.ps1
```

#### 2. 编辑您的 pom.xml .

```xml
<properties>
    <scx.mainClass>{your.main.class}</scx.mainClass>
</properties>
```

#### 3. 使用 PowerShell 运行 [scx-build.ps1](./scx-build.ps1) .

```
1. 运行项目
2. 构建项目 (不包括依赖项)
3. 构建项目 (包括依赖项)
4. 仅复制依赖项
0. 退出
```
