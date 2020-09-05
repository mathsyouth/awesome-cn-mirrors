# awesome-cn-mirrors

国内镜像资源汇总


## npm 国内镜像

1. 淘宝镜像: `echo "registry = https://registry.npm.taobao.org" > ~/.npmrc`


## pip 国内镜像

临时设置可以通过 -i 选项，全局设置有不同的层级和文件位置，以用户全局为例，在 Linux & macOS 中，配置需要写到 ~/.pip/pip.conf 文件中。

手动创建对应的目录和文件，然后写入下面的内容：

```
[global]
index-url = https://pypi.doubanio.com/simple
[install]
trusted-host = pypi.doubanio.com
```

镜像列表：

1. 豆瓣 https://pypi.doubanio.com/simple/
1. 网易 https://mirrors.163.com/pypi/simple/
1. 阿里云 https://mirrors.aliyun.com/pypi/simple/
1. 腾讯云 https://mirrors.cloud.tencent.com/pypi/simple/
1. 清华大学 https://pypi.tuna.tsinghua.edu.cn/simple/
1. 中国科技大学 https://pypi.mirrors.ustc.edu.cn/simple/
