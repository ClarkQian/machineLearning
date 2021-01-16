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



## env里面的cpu加载
```
activate tensorflow
pip install tensorflow -i https://pypi.douban.com/simple 成功

下面全部失败
pip --default-timeout=100 install tensorflow==2.0.0 -i https://pypi.tuna.tsinghua.edu.cn/simple
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple tensorflow
清华：https://pypi.tuna.tsinghua.edu.cn/simple

阿里云：http://mirrors.aliyun.com/pypi/simple/

中国科技大学 https://pypi.mirrors.ustc.edu.cn/simple/

华中理工大学：http://pypi.hustunique.com/

山东理工大学：http://pypi.sdutlinux.org/ 

豆瓣：http://pypi.douban.com/simple/
```

1.遇到了

ERROR: Cannot uninstall 'wrapt'. It is a distutils installed project and thus we cannot accurately determine which files belong to it which would lead to only a partial uninstall.

办法1：输入 pip install -U --ignore-installed wrapt enum34 simplejson netaddr

参考：https://www.cnblogs.com/xiaowei2092/p/11025155.html
