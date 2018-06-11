# 小程序组件化开发框架 wepy 示例demo
	WePY借鉴了Vue.js（后文简称Vue）的语法风格和功能特性，如果你之前从未接触过Vue，建议先阅读[Vue的官方文档](https://cn.vuejs.org/v2/guide/)，以熟悉相关概念

# 参考文档
- [github](https://github.com/Tencent/wepy)
- [官方文档] (https://tencent.github.io/wepy/document.html#/)

# 项目创建与使用
全局安装 npm install wepy-cli -g
初始化一个项目 wepy init standard my-project
安装依赖  npm  install
开启实时编译 wepy build --watch

# WePY项目的目录结构
├── dist                   小程序运行代码目录（该目录由WePY的build指令自动编译生成，请不要直接修改该目录下的文件）
├── node_modules           
├── src                    代码编写的目录（该目录为使用WePY后的开发目录）
|   ├── components         WePY组件目录（组件不属于完整页面，仅供完整页面或其他组件引用）
|   |   ├── com_a.wpy      可复用的WePY组件a
|   |   └── com_b.wpy      可复用的WePY组件b
|   ├── pages              WePY页面目录（属于完整页面）
|   |   ├── index.wpy      index页面（经build后，会在dist目录下的pages目录生成index.js、index.json、index.wxml和index.wxss文件）
|   |   └── other.wpy      other页面（经build后，会在dist目录下的pages目录生成other.js、other.json、other.wxml和other.wxss文件）
|   └── app.wpy            小程序配置项（全局数据、样式、声明钩子等；经build后，会在dist目录下生成app.js、app.json和app.wxss文件）
└── package.json           项目的package配置


