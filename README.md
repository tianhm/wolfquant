# wolfquant
期货接口基于pyctp，使用语言python3.6，环境linux64/ubuntu
# 使用
1）安装包
```shell
$ python setup.py
```
2) 复制配置文件，更新配置信息
```shell
$ cp etc/config-default.json config.json
```
3)使用案例
```python
# 通过以下方式使用期货版API
>>>from wolfquant.future import ApiStruct, MdApi, TraderApi
```
4) 运行测试案例
```shell
$ cd tests
$ python test_api.py
```

# 路线图
### 0.0.0
* 实现了期货python版的交易接接口
* 基于python交易接口的二次封装
* 整理交易接口的使用文档
