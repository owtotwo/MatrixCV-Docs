## About

**MatrixCV**是一个用于简历投递的标准Web应用。MatrixCV相比传统的面试管理系统，除了支持简历投递以及面试申请等必须内容，还有以下几个特点：

1. 支持管理员处理简历投递与面试申请
2. 管理员入口与用户入口一致，但导向不同
3. 内容高聚合，功能集中，不分散到多个页面
4. 界面简单美观
5. 服务端 docker 化，可自动部署，自动重启
6. 前端高度组件化，低耦合，可复用
7. 部署需要的资源极少

我的这个项目已开源！

- [MatrixCV](https://github.com/owtotwo/MatrixCV)

## Demo

（加载时间可能比较长，请耐心等候🙂）

MatrixCV简历投递系统（包括主页、用户端与管理员端的展示）

![matrixcv-demo-GIF](https://github.com/owtotwo/MatrixCV-Docs/raw/gh-pages/matrixcv-demo.gif)

## 项目结构

项目主要分成三个部分

1. 使用nodejs开发的基于express框架的服务后端，主要特性是
    - 支持多用户同时操作，高并发处理效率高
    - 操作简单，人性化的UI设计
2. 使用 Vue + Element-UI 开发的前端（包括展示主页、用户端和管理员端），主要特性是
    - 操作简单，人性化的UI设计
    - 结构简洁、虚拟DOM成效好、充分展现响应式框架的优势
    - 各细节组件精巧（如简历筛选器、日历选择器等）

## Iterations 迭代

### Iteration 3

#### 目标

1. 前端完成管理系统开发，实现简历查询与流转
2. 前后端完成对接

#### Week 16

后台

- [x] 一键部署
- [x] 重构数据库完成
- [x] 后端基本完成
- [x] 取消docker，单npm即可，降低复杂度

前端

- [x] 完善用户界面
- [x] 完善并测试多用户使用情况
- [x] 前端基本完成

#### Week 15

后台

- [x] docker 化
- [x] 数据库功能太冗余，体积大，不符合项目定位，放弃mongodb使用lowdb重构数据库

前端

- [x] 放弃Angular，使用Vue重构
- [x] 工程加速，实现管理员界面

---

### Iteration 2

大部分时间都去看病了，一直在医院，所以停工了一段时间。

#### 目标

1. 前端完成首页 UI
2. 后台按照前期文档中的领域模型等等来完成后台设计
3. 后台完成多人同时使用的 API 设计

#### Week 14

后台

- [x] 重构代码，尝试用 `docker-compose` 构建 （结果推后了）
- [x] 测试数据库
- [x] 测试、修改 API 接口

前端

- [x] 添加用户个人页面
- [x] 处理前后端分支，前端第二次小迭代完成


#### Week 13

后台

- [x] 根据 API 文档开发
- [x] 重构数据库 （从 MySQL 转到 mongodb ）

前端

- [x] 修改首页 UI 设计，增加岗位详情
- [x] 自己核对 API 细节

#### Week 12

- [x] 首页招聘广告走马灯展示
- [x] 首页招聘岗位展示
- [x] 后台 API 接口开放一小部分

---

### Itearation 1

因为我们小组（只有我）成立于第十周，所以第一次迭代开始于第十周。

#### 目标

1. 构思项目内容与主题
2. 尝试用 Axure 绘制初步前端原型图
3. 考虑 API 的设计样式

#### Week 10

**总的来说 ...**

- 选择使用课程提供的挣闲钱主题
- 因没有电脑选择了手绘部分原型图，已丢失（后来主题变更了也就废弃了）
- API 选择了类 RESTful 的 API 设计，不适用标准的 RESTful 是因为考虑到现实情况下它并不能完全适配

**Front-end group**

- None 我一个人就是一个组

**Back-end group**

- None 我一个人就是一个组


