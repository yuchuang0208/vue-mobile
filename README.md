# 这是一个NB的项目

## 憋说话，用心感受， 每一行代码都是 有灵魂的

### [开源协议区别](https://www.zhihu.com/question/19568896)

## 普通命令行的Git提交方式
1. git add .
2. git commit -m "提交消息"
3. git push

## 首页Tabbar购物车图标的制作步骤
1. 先找到 扩展图标的 页面文件，从里面拷贝对应的 购物车 图标的 类样式 ，应用给自己的元素
2. 发现 缺少 扩展图标的样式表， 需要手动拷贝 icons-extra.css
3. 发现 缺少 ttf 字体文件， 需要手动拷贝 mui-icons-extra.ttf

## 添加路由的高亮样式

## 路由的切换动画

## 制作首页的 轮播图 功能
### 绘制轮播图 结构
### 获取轮播图数据并循环渲染
### 一般功能完成的过程：
1. 先画界面
2. 调用 数据请求，从服务器获取数据
3. 把数据保存到 组件的 data 对象上
4. 使用 v- 相关的 vue 指令，来渲染数据
5. 把渲染的数据，使用 过滤器 做一下处理

## 制作Home首页的九宫格
1. 九宫格使用到了 MUI 中 grid-default.html
2. 在设置样式的时候，为了防止优先级的问题，最好通过 审查元素，把类样式直接拷贝过来，然后修改

## 设置 新闻资讯 按钮的 路由跳转
1. 把 按钮 改造成路由 router-link   to="/home/newslist"    路径中带 /home 是为了让底部的 tabbar 高亮
2. 创建对应的路由组件
3. 创建对应的路由规则，把 router-link 和 组件 做一下关联

## 制作 新闻资讯 页面的 布局
1. 使用 MUI 中的 media-list.html 中的样式

## 新闻详情页面的布局
1. 从新闻列表跳转到详情通过this.$route.params.id获取id获取信息渲染页面
2. 全局配置请求根路径和post请求时的表单数据类型