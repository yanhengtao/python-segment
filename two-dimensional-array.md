#### python中二维数组的初始化

 - 方法1 直接定义
```
matrix = [[0, 0, 0], [0, 0, 0], [0, 0, 0]]
```

 - 方法2 间接定义
```
matrix = [[0 for i in range(3)] for i in range(3)]
```

- 方法3
```
matrix = []
for i in range(3):
    matrix.append([0] * 3)
```
