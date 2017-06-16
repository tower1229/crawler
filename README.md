# crawler

Nodejs crawler for [cnbeta.com](http://www.cnbeta.com/), The source code is on [Github](https://github.com/tower1229/crawler).

- 用于爬取并保存cnbeta新闻内容及图片
- 从起始文章开始爬取，异步获取上一篇文章ID并循环爬取
- 支持爬取总条数限制，默认50条
- 支持301跳转追踪
- 仅用于Nodejs学习，无意冒犯

## 使用

- 安装依赖：`npm install`
- 修改app.js中的`startId`变量为起始文章ID
- 运行抓取：`node app [limitNumber=50]`

## 示例

- 例如从该篇文章开始爬取`http://www.cnbeta.com/articles/tech/620719.htm`，修改 `startId="620719"`;
- 执行爬取10条：`node app 10`

![preview](https://raw.githubusercontent.com/tower1229/crawler/master/asset/preview.png)

## 更多
> [前端路上](http://refined-x.com)
