# learning_notes
The codes and datas of my personal learning notes.
# ML Algorithm
## 1 - SVM
### 1.1 SVM算法的理解
>[参考博客：支持向量机—SVM原理代码实现](https://www.cnblogs.com/further-further-further/p/9596898.html)
### 1.2 SVM算法的实现
代码实现也是引用的博客中的代码，环境使用的***py2.7***,需要安装***numpy***和***matplotlib***库。  
在运行调试过程中，只修改了一行代码：  
```python
 #分割
 #lineArr = line.strip().split('\t')
        lineArr = line.strip('\t')
        lineArr = lineArr.split()
```
