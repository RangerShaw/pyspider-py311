
### 说明

###### 修改版的pyspider 使其适配更高版本的python 在centos7 + python3.9环境下测试通过，其他未测试。

###### 主要修改了async关键词冲突、固定了一些依赖的版本防止报错。

###### 从collections修改为collections.abc

###### 给分组加了一个tabs切换，切换cf的cdn到字节跳动的cdn

--------------

pycurl https://www.lfd.uci.edu/~gohlke/pythonlibs/#pycurl

collections.abc

### 使用方法

1. 安装pycurl

    https://www.lfd.uci.edu/~gohlke/pythonlibs/#pycurl

2. 安装pyspider

    pip install git+https://github.com/RangerShaw/pyspider-py311

3. 安装PhantomJS，并将phantomjs.exe放置到python目录中

    https://phantomjs.org/download.html

4. 从Python 3.9起，Abstract Base Classes for Containers从collections模块
移动到collections.abc中。需要在tornado.httputil文件中修改


