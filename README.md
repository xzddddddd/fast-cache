# fast-cache
短小精悍的前端缓存工具，防止内存泄漏

# 使用文档

##初始化

```js
var FC=window.FastCache;
var cache=new FC();
```

##设置

```js
cache.set('a',100);
```

##获取

```js
cache.get('a')
```

[如何使用](./doc/use/README.md) [二次开发](./doc/dev/README.md)