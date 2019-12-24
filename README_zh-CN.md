简体中文 | [English](./README.md)

# 下载github中指定的文件夹

<a href="https://circleci.com/gh/ykfe"><img src="https://img.shields.io/circleci/build/github/ykfe/dclone/master.svg" alt="Build Status"></a>
<a href="https://codecov.io/gh/ykfe/dclone"><img src="https://codecov.io/gh/ykfe/dclone/branch/master/graph/badge.svg" alt="Coverage Status"></a>

dclone是github上最简单的命令去下载github仓库中指定的文件夹(使用依赖git)，你可以用它来缩短你的下载速度

![](./image/time.png)

## 如何使用

非常简单，你只需要找到你需要下载的文件夹的github url地址即可

![](./image/example.png)

```bash
$ npm i -g dclone
$ dclone https://github.com/ykfe/egg-react-ssr/tree/dev/example/ssr-with-loadable
```

![](./image/dg.png)