> [!important]
>
> 本工具已直接集成（copy）到博客仓库中，通过github action触发

# 博客同步工具
本工具基于业内博客系统较为通用的 xmlrpc 协议，提供一键同步本地 Markdown 文章到各个博客系统的功能（目前只支持cnblogs）

## 使用方式
配置见`_config.yaml`文件，将其更名为`config.yaml`即可使用

运行`python main.py 文章.md`即可同步

## 其它
博客园不支持 Markdown 的 alert 风格引用，如：
``` markdown
> [!NOTE]
> 
> alert风格引用
```
因此会自动在同步之前将转换为普通风格的引用

## 小结
怎么CSDN还不倒闭