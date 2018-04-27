# think-crypt
The ThinkPHP5 crypt

## 安装

### 一、执行命令安装
```
composer require dh2y/think-crypt
```

或者

### 二、require安装
```
"require": {
        "dh2y/think-crypt":"*"
},
```

或者
###  三、autoload psr-4标准安装
```
   a) 进入vendor/dh2y目录 (没有dh2y目录 mkdir dh2y)
   b) git clone 
   c) 修改 git clone下来的项目名称为think-crypt
   d) 添加下面配置
   "autoload": {
        "psr-4": {
            "think\\crypt\\": "vendor/dh2y/think-crypt/src"
        }
    },
    e) php composer.phar update
```


## 使用
 此扩展是tp3.2 直接拿过来的，tp5框架不内带相关加密类
 具体使用方法参考tp3.2

