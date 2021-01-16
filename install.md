[安装链接](https://www.cnblogs.com/ming-4/p/11516728.html)
！！！完全不需要
## 环境加初步搭载
```
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/ 　　　　

conda config --set show_channel_urls yes

这两行代码用来改成连接清华镜像的。

打开C:\Users\Administrator\.condarc文件：

删除两行代码：

ssl_verify: true
- defaults

然后在Anaconda Prompt中输入：conda create -n tensorflow python=3.5
```

## env里面的cpu加载
```
activate tensorflow
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple tensorflow
清华：https://pypi.tuna.tsinghua.edu.cn/simple

阿里云：http://mirrors.aliyun.com/pypi/simple/

中国科技大学 https://pypi.mirrors.ustc.edu.cn/simple/

华中理工大学：http://pypi.hustunique.com/

山东理工大学：http://pypi.sdutlinux.org/ 

豆瓣：http://pypi.douban.com/simple/
```

## jupyter load
```
error
conda install jupyter ??
```
