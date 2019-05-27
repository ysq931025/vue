<h1 align="center">vue项目启动</h1>
## 目录
- [搭建vue项目](#搭建vue项目)
## 搭建vue项目
- 安装node环境
1.下载node直接安装;
2.检查是否安装成功：npm -v,node -v;
3.安装淘宝镜像：npm i -g cnpm --registry=https://registry.npm.taobao.org
- 搭建vue环境
1.全局安装vue-cli  npm install --global vue-cli
2.使用命令vue init webpack vue-demo 搭建vue项目, “vue-demo” 是你的项目名称。
3.此时vue项目基本上已经搭建完成， 执行npm run dev 命令，启动项目
- 遇到的坑
1.vue-cli如果没有全局安装就会报错，此时要使用命令vue -V（注意此处的V一定要大写）查看vue是否安装成功，如果不成功，则从新全局安装vue-cli
[↑ 返回目录 ↑](#目录)
	
