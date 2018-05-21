npm init

npm install --g browser-sync (http://www.browsersync.cn/#install)

npm install --save browser-sync （安装在当前目录下面）

在项目中的"scripts": {}处添加：
"dev":"browser-sync start --server --files *.*"

  "server": {
    "baseDir": "./",
    "index": "intex.html"
  },

npm run dev