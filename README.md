# hello-play
learning play framework

- 目录说明
```
app                      → 应用源文件
 └ assets                → 可编译的前端源文件
    └ stylesheets        → 通常是 LESS 源文件
    └ javascripts        → 通常是 CoffeeScript 源文件
 └ controllers           → 控制器
 └ models                → 业务层
 └ views                 → 视图模板
build.sbt                → 构建脚本
conf                     → 配置文件、其他非编译资源 (on classpath)
 └ application.conf      → 主要配置
 └ routes                → 路由定义
dist                     → 项目发布时包含的任意文件
public                   → 公共静态资源
 └ stylesheets           → CSS 
 └ javascripts           → Javascript 
 └ images                → Image 
project                  → sbt 配置文件
 └ build.properties      → sbt 项目标记
 └ plugins.sbt           → sbt 插件，包含 Play 自身
lib                      → 不受 sbt 管理的依赖包
logs                     → 日志目录
 └ application.log       → 默认日志文件
target                   → 生成的文件等
 └ resolution-cache      → 关于项目依赖的信息
 └ scala-2.11
    └ api                → 生成的 API 文档
    └ classes            → 编译的类文件
    └ routes             → 路由生成的源文件
    └ twirl              → 模板生成的源文件
 └ universal             → 应用打包
 └ web                   → 编译的 web 资源
test                     → 单元测试、功能测试源目录
```