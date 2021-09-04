# Migration Page - 迁移页

> A simple, hosted, customisable migration page service.
> 简单，托管，可自定义的的迁移页服务。

Demo 演示页面：[https://migration-page.pages.dev](https://migration-page.pages.dev/?oldroot=justhx.com&newroot=huangxin.dev&name=惶心博客（演示）&count=10&location=past-stories/the-winter-memory.html)

![Demo Screenshot 演示屏幕截图](https://vip2.loli.io/2021/09/05/bOcgl67JUzkyTuE.png)

## Usage 用法

```bash
https://migration-page.pages.dev/?oldroot=old-domain.com&newroot=new-domain.com&name=YOUR-SITE-NAME&count=999&location=some_url_path
```

### Parameters 参数

- `oldroot` - your old domain 你的旧域名  
- `newroot` - your new domain 你的新域名  
- `name` - intended name for your site 你的站点名称  
- `count` - time interval before the redirection 重定向前倒数的秒数  
- `location` - relative url path for the redirection  重定向的相对路径  

## Deployment 部署

You are free to deploy this service for your own.  
你可以自由地自行部署这个项目。

### Simple Usage 普通用法

Simply download the `migration-page.html` file, modify it if needed, then host it yourself via a web server.  
下载 `migration-page.html` 文件，如有需要对文件作修改，然后通过一个服务器托管它。

#### Commandline Download 命令行下载

```bash
wget https://raw.githubusercontent.com/hifocus/Migration-Page/master/migration-page.html -O index.html

# For restricted network environments 在受限的网络环境下使用
# wget https://cdn.jsdelivr.net/gh/hifocus/Migration-Page/migration-page.html -O index.html
```

### Advance Usage 进阶用法

Migration page could be use as a [NPM package](https://en.wikipedia.org/wiki/Npm_(software)).  
Migration Page 可被以一个 [NPM 包](https://zh.wikipedia.org/wiki/Npm)的形式使用。

```bash
git clone https://github.com/hifocus/Migration-Page.git
npm install
npm run-script build
```

A *compressed* [migration-page.html](https://github.com/hifocus/Migration-Page/blob/master/migration-page.html) will be output to `/docs` folder.  
一个被压缩的 [migration-page.html](https://github.com/hifocus/Migration-Page/blob/master/migration-page.html) 将会被输出到 `/docs` 目录。

You can use this feature to make ease for [Serverless Hosting](https://en.wikipedia.org/wiki/Serverless_computing), [Continuous Integration](https://en.wikipedia.org/wiki/Continuous_integration) and your further development.  
这个特性可为[无服务器托管](https://zh.wikipedia.org/wiki/%E7%84%A1%E4%BC%BA%E6%9C%8D%E5%99%A8%E8%A8%88%E7%AE%97)，[持续集成](https://zh.wikipedia.org/wiki/%E6%8C%81%E7%BA%8C%E6%95%B4%E5%90%88)和你的后续开发提供便利。

## About 相关

This project is modified from on [Dreamer-Paul/Emmm](https://github.com/Dreamer-Paul/Emmm). The original author outlined some features of the base project which could be read from [here](https://github.com/Dreamer-Paul/Emmm#%E9%A1%B9%E7%9B%AE%E7%89%B9%E6%80%A7).  
这个项目是从 [Dreamer-Paul/Emmm](https://github.com/Dreamer-Paul/Emmm) 修改而来。原作者列出了原项目的一些特性，可以从这里[查看](https://github.com/Dreamer-Paul/Emmm#%E9%A1%B9%E7%9B%AE%E7%89%B9%E6%80%A7)。

The software is released under the [MIT license](https://github.com/hifocus/Migration-Page/blob/master/LICENSE).