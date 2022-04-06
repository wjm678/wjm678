在Vue安装和搭建过程
首先需要安装node.js
然后在nodejs文件中新建两个文件一个是node_global一个是node_cache
全局模块目录和缓存目录配置到我们刚才创建的那两个目录
npm config set prefix "D:\Program Files\nodejs\node_global"
npm config set cache "D:\Program Files\nodejs\node_cache"
然后对环境进行变量配置，先在个人path配置D:\nodejs\node_global
然后在系统环境定义一个NODE_PATH路径为D:\nodejs\node_global\node_modules 
最后在系统path把NODE_PATH定义进去
最后运行npm install -g cnpm --registry=https://registry.npm.taobao.org进行安装cnpm
运行npm install -g @vue/cli进行脚手架安装
最后运行vue ui即可vue版本大于3，版本查询vue -V
