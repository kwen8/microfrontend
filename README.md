## 项目结构

ms-loader 为应用加载器
ms-master 为主应用
ms-submodule 为子应用

## 下载

```bash
git clone --recurse-submodules git@github.com:kwen8/microfrontend.git
```

## 启动

1. 启动加载器

```bash
cd ms-loader
yarn
yarn dev
```

2. 启动主应用

```
cd ms-master
yarn
yarn serve
```

3. 启动子应用

```
cd ms-submodule
yarn
yarn serve
```

### 预览

打开 localhost:5000
localhost:5000/sub 为子应用页面
