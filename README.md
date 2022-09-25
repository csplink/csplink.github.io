CSP wiki 文档源码
=====

CSP 在线 Wiki: [csp_wiki](https://xqyjlj.github.io/csp_wiki/)


## 本地预览

```bash
git clone https://github.com/xqyjlj/csp_wiki.git
pip install teedoc
cd csp_wiki
teedoc install
teedoc serve
```

更多技巧请参阅 [teedoc](http://github.com/teedoc/teedoc)

## 对于管理员

GitHub action 会自动将更改的文档推送到云服务器

但是如果你做了一些特殊的事情，比如强制提交，服务器上可能会丢失一些文件。手动触发 publish pages 操作来构建文档并将所有文件上传到服务器。