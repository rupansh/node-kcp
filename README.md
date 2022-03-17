node-kcp-x
======================================

[![Build Status][1]][2]

[1]: https://api.travis-ci.org/leenjewel/node-kcp.svg?branch=master
[2]: https://travis-ci.org/leenjewel/node-kcp


[KCP Protocol](https://github.com/skywind3000/kcp) for Node.js

修改自 [node-kcp](https://github.com/leenjewel/node-kcp)
## HowTo

### Build:

```
npm install -g node-gyp

node-gyp configure

git clone https://github.com/bruce48x/node-kcp

cd node-kcp

git submodule update --init

node-gyp build
```

## 运行示例1

```sh
npm run install
node test/udpserver.js
node test/udpclient.js
```

## 运行示例2

```sh
# 运行服务端
node examples/server.js
# 运行客户端
node examples/client.js
```

## About Pomelo and Pomelo-kcp

If you want to use [node-kcp](https://github.com/leenjewel/node-kcp) in [pomelo](https://github.com/NetEase/pomelo/) server, you need [pomelo-kcp](https://github.com/leenjewel/pomelo-kcp)