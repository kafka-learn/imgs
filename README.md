```bash
$ git clone https://github.com/kafka-learn/imgs
```

原始图片放到`./src`目录下,执行如下命令,压缩后的图片在`/compress_src`下,并且会git提交
```
$ python tool.py
```

注意：

* 图片名称用英文名称

* 引用图片地址，例如

```
# ./src下的
https://raw.githubusercontent.com/kafka-learn/imgs/master/src/alter_partion.png
# ./compress_src下的
https://raw.githubusercontent.com/kafka-learn/imgs/master/compress_src/alter_partion.png
```
