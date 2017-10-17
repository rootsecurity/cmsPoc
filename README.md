# cmsPoc
[![Python 2.7](https://img.shields.io/badge/python-2.7-yellow.svg)](https://www.python.org/)
![License](https://img.shields.io/badge/license-GPLv2-red.svg)

## Requirements
- python2.7
- Works on Linux, Windows

## Usage
```
usage: cmspoc.py [-h] -t TYPE -s SCRIPT -u URL

optional arguments:
  -h, --help            show this help message and exit
  -t TYPE, --type TYPE  e.g.,phpcms
  -s SCRIPT, --script SCRIPT
                        Select script
  -u URL, --url URL     Input a target url
```

参数说明：
- -t：指定cms的类型
- -s：指定要载入的POC脚本
- -u：指定目标cms

## Examples
```
python cmspoc.py -t phpcms -s v960_sqlinject_getpasswd -u http://10.10.10.1:2500/phpcms960
```
![](https://github.com/CHYbeta/cmsPoc/blob/master/tty.gif?raw=true)

## Script
|  TYPE   | SCRIPT | DESCRIPTION  |
|:-------------:|:-------------:|:-----:|
|phpcms| v960_sqlinject_getpasswd | [phpcmsv9.6.0 wap模块 sql注入 获取passwd](https://chybeta.github.io/2017/08/04/%C2%96PHPCMS-v9-6-0-wap%E6%A8%A1%E5%9D%97sql%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/)|
|icms| v701_sqlinject_getadmin | [icmsv7.0.1 admincp.php sql注入 后台任意登陆](https://chybeta.github.io/2017/09/12/ICMSv7-0-1-admincp-class-php-sql%E6%B3%A8%E5%85%A5%E5%88%86%E6%9E%90/)|
