## 综述

KScroll基于KISSY的滚动条组件。支持滚轮、拖拽、上下箭头加速滚动。样式可定制，支持hover,active两种状态。自适应内容区大小调整。

* 版本：1.1
* 基于：kissy1.3（兼容kissy2.0.0，不兼容kissy1.1.6）
* 作者：常胤 承玉

## 组件Demo

* [Kscrolldemo演示](../demo/index.html)


## 组件快速上手

kissy2.0.0下需要kg的包配置：

```
KISSY.config({
    packages:[
        {
            name   : 'kg',
            path   : 'http://a.tbcdn.cn/s/kissy/',
            charset: 'utf-8'
        }
    ]
});
```

kissy1.3就不需要该配置。

### 1.加载 Kscroll

```
KISSY.use('kg/kscroll/1.1/index', function(S, Kscroll) {
    var scroll = new Kscroll(container, config);
});
```



## 组件属性说明

使用很简单，直接看demo吧
