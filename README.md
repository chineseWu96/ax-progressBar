<p align="center">
  <a href="http://ant.design">
    <img width="200" src="./img/logo.svg">
  </a>
</p>

<h1 align="center">ax-progressBar</h1>

## 🖥 Environment Support

|[<img src="./img/node.svg" alt="node" width="50" height="30" style="    background-color: #333;padding:10px;"/>](http://nodejs.cn/)</br>Node.js </br> |
| --------- | --------- | --------- | --------- | --------- | --------- |
| Node12

## 📦 Install

```bash
npm install ax-progressBar --save
```

## 🔨 Usage

```js
let progressBar = new ProgressBar('上传进度', 100);

progressBar.render({ completed, total });
//completed：number 当前已上传成功数量
//total：total 上传总数
```
