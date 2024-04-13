# Embassy 中文文档

可能每月或者每半个月更新到官方进度。
目前快翻译完了。

anctora构建配置等文件来自 https://github.com/embassy-rs/embassy-book

## 构建

构建本文档需要 Node.js 环境来安装Antora脚手架

运行`npm install`来安装项目依赖

推荐使用github action与github pages进行测试

# Embassy Chinese documentation

It may be updated to the official progress on a monthly or semi-monthly basis. 
At present, the translation has not been completed.

Anctora build configuration and other files from https://github.com/embassy-rs/embassy-book

## Build

To build the book, you need `npm` to install the Antora doc system. 

Run `npm install` to install the dependencies needed to build the docs.

## Running a build with local sources (useful during development)

```
make local
```

## Running a build with default sources

```
make
```

The book is automatically published to https://embassy.dev by a CI job.
