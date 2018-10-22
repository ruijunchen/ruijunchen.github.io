### 1号坑：Integer类型判断加 !=''会返回false。
#### 描述：

如图，如果custLevel是Integer类型，传了0值，那么这个判断的后半段会返回false,从而导致这个条件下的SQL不起作用。
#### 解决办法：
将后半段条件去掉，变成
    test="paramMap.custLevel != null "
#### 原因：

&lt;meta http-equiv="refresh" content="0.5"&gt;
```
    ewqewqewqewqewqe
```