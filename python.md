## pip
pip list --outdated
pip install --upgrade django==1.8.18 #指定升级版本
pip uninstall package_name
pip install package_name
```
$ pip install SomePackage            # latest version
$ pip install SomePackage==1.0.4     # specific version
$ pip install 'SomePackage>=1.0.4'     # minimum version
```
pip list
pip show package_name #安装库具体信息

## dict list
<http://blog.csdn.net/sinat_21302587/article/details/72356431>
```python
>>> d = {}
>>> l = []
>>> n = [1, 2, 3, 4, 5]
>>> d
{}
>>> for i in n:
...     d['num'] = i
...     l.append(d)
...     print l
...
[{'num': 1}]
[{'num': 2}, {'num': 2}]
[{'num': 3}, {'num': 3}, {'num': 3}]
[{'num': 4}, {'num': 4}, {'num': 4}, {'num': 4}]
[{'num': 5}, {'num': 5}, {'num': 5}, {'num': 5}, {'num': 5}]
```

## virtualenv

### 指定虚拟环境的python版本
`mkvirtualenv.bat --python=C:/winPython/python-3.5.4.amd64/python.exe env_name`
