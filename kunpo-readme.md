## 版本: 3.8.6
### 环境配置

* 获取 external

  ```bash
  # Cocos 原生引擎的编译，需要依赖 cocos-engine/native/external 中的库。这些库有几百 MB 大小，所以源码包内默认是没有的，可以通过以下方式
  
  # 到自定义引擎的根目录下执行命令
  cd native
  git clone https://github.com/cocos/cocos-engine-external external
  cd external
  git checkout -b v3.8.6-12
  ```

* 安装编译依赖

  ```bash
  # 请确保电脑安装了 NodeJS v12.0 以上版本
  # 在自定义引擎根目录，执行以下命令
  
  # 安装 gulp 构建工具
  npm install -g gulp
  # 安装依赖的模块
  npm install
  ```

* 修改引擎路径