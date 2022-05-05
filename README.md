# pypi-package

### 作用
    
    python 打包发布模版

### 推送地址

    Nexus 私服地址：http://xxx.xxx.xxx.xxxx:xxxxx/    用户名/密码 xxx/xxx。pypi 推送至pypi创建的仓库

### 打包/推送命令

```
打包
1.python setup.py sdist bdist_wheel
推送
2.twine upload --repository-url http://xxx.xxx.xxx.xxxx:1314/repository/xxxx/ dist/*
```

### 安装

```
pip install package名 -i http://xx.xxx.xxx.xxx:xxxx/repository/xxxx/simple --trusted-host xxx.xxx.xxx.xxx:Xxx
```