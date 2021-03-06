# Pocsuite3
基于 Knownsec 404 Team 编写的 [pocsuite3](http://pocsuite.org/) 框架收集整理漏洞相关POC，用于安全测试。

[Pocsuite3源码地址](https://github.com/knownsec/pocsuite3) | [使用说明](https://github.com/Snowty/pocset/blob/master/docs/USAGE.md) | [开发文档](https://github.com/Snowty/pocset/blob/master/docs/CODING.md) | [漏洞分类](https://www.seebug.org/category/)

# 基本用法
- Python 3.4+
- Works on Linux, Windows, Mac OSX, BSD
  
```
pip install -r requirements.txt
cd pocsuite3
python cli.py -r pocs/tomcat_ajp_cve_2020_1938_arbitrary_file_read.py -u $vulurl 
```

# POC列表
| 序号 | poc                                     | 说明                                                          | 创建日期       |更新日期       |
| ---- | --------------------------------------- | ------------------------------------------------------------ |--------------|--------------|
| 1    | tomcat_ajp_cve_2020_1938_arbitrary_file_read | Apache Tomcat Ajp协议 文件包含漏洞(CNVD-2020-10487 / CVE-2020-1938)| 20200228|--|
