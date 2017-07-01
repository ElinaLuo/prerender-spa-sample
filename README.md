## prerender-spa-sample

这是vue预渲染的超简单的栗子

[prerender-spa-plugin](https://github.com/chrisvfritz/prerender-spa-plugin)框架帮我们做了很多，这里有几个需要注意的地方

需要在你的vue里面，加上
```
<div id="app"></div>

````
因为vue渲染的时候该容器会被替换掉，在页面加载的时候，为了保证js正常执行，请一定要在你的vue最外层手动加上

```
npm install

webpack

```

