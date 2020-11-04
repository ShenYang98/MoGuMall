## MoGuMall

**项目简介**：

* 本项目基于**Vue**、**Vue-router**、**Vuex**的生态环境开发，实现了首页、分类、详情，购物车、个人信息等模块，在**Tabbar**中使用**Vue-router**实现懒加载。

* 首页实现了轮播图展示，并通过**axios**向接口请求数据，使用防抖函数防止刷新频繁，实现了上拉加载更多，返 回顶部等效果，使用**Better-scroll**提高用户滑动体验。

* 首页导航条监听滚动距离完成吸顶效果，点击商品图片携带商品**id**跳转到详情页面，并且使用**keep-alive**保存原 本位置信息。

* 本项目使用组件化开发思想，封装了本项目使用组件和项目间通用组件。

#### 项目部分功能截图如下：

**1.首页：**

![](https://pic.downk.cc/item/5fa24a8f1cd1bbb86b0e0ef5.png)

**2.分类页面：**

![](https://pic.downk.cc/item/5fa24ad11cd1bbb86b0e21bc.png)

**3.购物车：**

![](https://pic.downk.cc/item/5fa24af61cd1bbb86b0e2d9f.png)

**4.个人中心：**

![](https://pic.downk.cc/item/5fa24b321cd1bbb86b0e3a9b.png)