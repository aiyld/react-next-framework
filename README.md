# react-next-framework
React full framework 主要包含以下模块：

React + NextJs + i18n + Less + Redux + Router + Eslint + Axios + Bootstrap

[![npm version](https://img.shields.io/npm/v/react-next-framework.svg?style=flat-square)](https://www.npmjs.com/package/react-next-framework) [![npm downloads](https://img.shields.io/npm/dm/react-next-framework.svg?style=flat-square)](https://www.npmjs.com/package/react-next-framework)

为能更好、快速、科学的开发项目，便研发出了此框架。它的实现的目标如下：
- [x]  1. 结合Nextjs和express实现React服务端渲染，SEO优化合理；
- [x]  2. 支持多语言功能，能自动提取项目中的中文内容，生成翻译文件；
- [x]  3. 添加Less，页面样式编辑；
- [x]  4. 添加Router，路由管理；
- [x]  5. 添加网络请求模块，各个组件和无需区别客户端还是服务端，直接调用实现数据请求；
- [x]  6. 添加Eslint，规范项目编程风格；
- [x]  7. 添加Redux，统一规范状态管理，可以在任意组件页面无需引用便可直接调用方法更新状态。

### 快速以此模板创建项目
```
npx yld-cli init <your-project-name>
```

### 目录结构说明
```
|-- assets 放置样式文件
|   |-- pages 放置页面相关样式
|   |-- common.less 公共样式
|-- components            组件
|-- lib                   相关工具
|-- locales               多语言文件文件
|-- pages                 页面
|-- server                服务端渲染
|-- static                放置静态文件
|-- store                 状态管理
|-- .eslintrc.js          Eslint配置
|-- .gitignore            git管理
|-- next.config.js        next配置
```

### 开发环境
```
npm i
npm run dev
```

### 生产环境
```
npm i
npm run build
npm run online
```

### 作者
- 英文名：YLD，又名Winter
- 邮箱：aiyld@hotmail.com
- Github：https://github.com/aiyld
- 个人网站： http://www.yanglidong.com
- 个人博客产品：[SamYoc https://www.samyoc.com](https://www.samyoc.com)
- 个人文档产品：[在线文档 https://doc.samyoc.com](https://doc.samyoc.com)

好用的工具千千万万，方便的框架万里挑一...