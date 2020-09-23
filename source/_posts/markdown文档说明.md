---
title: markdown说明文档
---

# test
## title2
### title3
___
这是一段**加粗**的文字，这也是 __加粗__ 文字，这是 _倾斜_ 文字
>注释文字
>> 注释二层
>>>注释三层
>>>>>注释五层

```C
#include<iostream>
void main(){
    cout<<123<<endl;
}
```
```javascript
console.log(666)
```
```python
def func():
    print('nihao')
```

+ 无序列表z
    - 世界
    - 上帝
        - 书店
            - 美食
        - 紧急
+ 无序列表j

+ 无续列表1
    - 你好
        - 啦啦啦
    - 你得得得
        
+ 无序列表2
- 无序列表3
- 无序列表4

1. 有序1
    + hell
    + o
    + 你好
3. 有序3
2. 有序2

1992\.3发生了一件奇怪的事。  
hello  
[baidu](http://www.qq.com)  
[google](http://google.com/ "googletitle")

```mermaid
    graph TB
        id1(圆角矩形)--普通线-->id2[矩形]
        subgraph 子图表
            id2==粗线==>id3{菱形}
            id3-.虚线.->id4>右向旗帜]
            id3--无箭头---id5((圆形))

    end
```

```mermaid
graph TB
　　client-->|2 findConfigServices|LoadBalancer;

```
```mermaid
sequenceDiagram
    participant z as 张三
    participant l as 李四
    loop 日复一日
        z->>l: 吃了吗您呐？
        l-->>z: 吃了，您呢？
        activate z
        Note left of z: 想了一下
        alt 还没吃
            z-xl: 还没呢，正准备回去吃
        else 已经吃了
            z-xl: 我也吃过了，哈哈
        end
        opt 大过年的
            l-->z: 祝您新年好啊
        end
    end
```

