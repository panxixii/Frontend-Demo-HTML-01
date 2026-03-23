# Frontend-Demo-HTML-01

## 💡 项目简介

- 这是一个纯静态的 HTML 页面练习项目。
- 核心目的是为了抛开繁杂的框架，回归前端的最基础部分，系统性地巩固和刻意练习 HTML 表单（Form）及其相关元素的页面结构搭建。

## 📄参考

- [黑马HTML教程](https://www.bilibili.com/video/BV14J4114768?spm_id_from=333.788.videopod.episodes&vd_source=0492fb410a85e3b5ef2b8a654a88a4ad&p=56)

## 🛠️技术栈

- 纯HTML

## 🖇️预览

- [点击这里查看我的网页](https://panxixii.github.io/Frontend-Demo-HTML-01/)

## 📖 经验与总结 (Key Takeaways)

### 1.Github

- 分支创建
  - 原因：
    原子化提交会导致主干日志混乱，影响代码管理
  - 解决：
    创建功能分支保持高频记录以支持“精确存档”，将代码提交到新分支，再采用Squash Merge合并到主干分支，确保主干日志清晰、有序

- GitHub Pages
  - 作用：
    部署和展示静态网页
  - 提醒：
    支持完整前端功能（三剑客+框架+api接口）
    不能跑后端代码
  - PR信息
    - 格式：
      类型(作用域): 说明信息
      1. What does this PR do? (本次 PR 做了什么？)
      2. Why are we doing this? (为什么要做这些？)
      3. Screenshots（页面截图展示）

- readme
  - 作用：
    项目介绍等
  - 格式：
    项目名称
    项目介绍
    技术栈
    预览
    经验与总结

### 2.项目版本控制

- 原子化提交
  - 原因：
    以往“一天一提交”，一次提交包含多个功能点，代码版本耦合度过高，导致代码回滚困难
    一次提交功能点过多，提交信息过于冗长，导致代码管理困难
  - 解决：
    每次提交只包含一个功能点，确保代码版本颗粒度清晰，方便回滚

### 3.提交信息

- 格式
  类型(作用域): 说明信息

  [Technical Changes]
  本次提交的功能点

  [Learning & Reflection]
  现阶段从项目中学到的知识点
  工作流演进：学习的全过程记录
  知识点汇总

- 类型
  - feat: 新增功能
  - fix: 修复bug
  - style: 代码风格更改，不影响逻辑
  - refactor: 代码重构
  - docs：文档更新
  - perf: 性能优化
  - test: 测试相关变更
  - revert: 回退到之前的提交
  - ci: 持续集成配置更改
  - build: 构建系统或外部依赖关系的更改
  - chore: 构建过程或辅助工具的更改

- 专业表达(句式模板)
  1. 新增功能
     feat: add + 功能描述
     示例：feat: add password reset functionality

     feat: implement + 功能描述
     示例：feat: implement user profile editing

     feat: introduce + 功能描述
     示例：feat: introduce dark mode support

     feat: create + 组件/模块名称
     示例：feat: create dashboard layout component

  2. 修复问题
     fix: resolve + 问题描述
     示例：fix: resolve login error on Safari

     fix: fix + 问题描述
     示例：fix: fix broken image upload

     fix: correct + 错误描述
     示例：fix: correct validation logic in form

     fix: address + 问题描述
     示例：fix: address memory leak in chart component

  3. 样式调整
     style: adjust + 位置/布局/样式描述
     示例：style: adjust button padding on mobile

     style: update + 样式描述
     示例：style: update font size for headings

     style: fix + 样式问题描述
     示例：style: fix overlapping elements in navbar

     style: refine + 样式描述
     示例：style: refine modal shadow and border radius

  4. 重写文本内容
     docs: rewrite + 页面/文本内容 + 修改描述
     示例：docs: rewrite homepage copy for clarity

     i18n: update + 语言/文案描述
     示例：i18n: update error messages in login form

     copy: revise + 文本位置/内容描述
     示例：copy: revise tooltip text for clarity

  5. 优化用户体验
     ux: improve + 功能/体验描述
     示例：ux: improve form validation feedback

     perf: enhance + 性能/体验描述
     示例：perf: enhance image loading with lazy loading

     ux: add + 体验增强描述
     示例：ux: add loading state to submit button

- 专业表达(常用词)
  - 动词
    add 添加
    remove 移除
    delete 删除
    update 更新
    modify 修改
    fix 修复
    resolve 解决
    implement 实现
    refactor 重构
    improve 改进
    optimize 优化
    adjust 调整
    correct 纠正
    rename 重命名
    move 移动
    extract 提取
    merge 合并
    split 拆分
    replace 替换
    deprecate 弃用
    revert 回退
  - 名词（页面与组件）
    page 页面
    layout 布局
    component 组件
    module 模块
    view 视图
    route 路由
    modal 弹窗
    drawer 抽屉
    dropdown 下拉菜单
    sidebar 侧边栏
    navbar / header 导航栏 / 头部
    footer 底部
    tab 标签页
    card 卡片
    list 列表
    table 表格
    form 表单
    field 字段
    input 输入框
    button 按钮
    checkbox 复选框
    radio 单选框
    toggle 开关
    select 下拉选择框
    uploader 上传组件
    slider 滑块
    tooltip 提示框
    notification 通知
    badge 徽章
    icon 图标
    avatar 头像
    menu 菜单
    breadcrumb 面包屑
    pagination 分页
    filter 筛选器
    search bar 搜索栏
    footer 页脚
  - 名词（功能与逻辑）
    feature 功能
    logic 逻辑
    validation 校验
    authentication 认证
    authorization 授权
    permission 权限
    state 状态
    store 存储
    API 接口
    endpoint 接口地址
    service 服务
    helper 辅助函数
    utility 工具函数
    hook 钩子
    middleware 中间件
    config / configuration 配置
    constant 常量
    type 类型
    interface 接口（TypeScript）
    enum 枚举
    mock 模拟数据
    test 测试
    error handling 错误处理
    fallback 降级方案
    placeholder 占位符
    loading state 加载状态
    empty state 空状态
    edge case 边界情况
  - 名词（样式与视觉）
    style 样式
    layout 布局
    spacing 间距
    padding 内边距
    margin 外边距
    alignment 对齐
    color 颜色
    theme 主题
    dark mode 深色模式
    responsive 响应式
    breakpoint 断点
    animation 动画
    transition 过渡效果
    hover state 悬停状态
    active state 激活状态
    disabled state 禁用状态
    focus state 聚焦状态
    border 边框
    shadow 阴影
    typography 排版
    font 字体
    z-index 层级
  - 形容词 / 副词
    missing 缺失的
    broken 损坏的
    incorrect 错误的
    duplicate 重复的
    redundant 冗余的
    unused 未使用的
    legacy 遗留的
    temporary 临时的
    hardcoded 硬编码的
    dynamic 动态的
    static 静态的
    nested 嵌套的
    conditional 条件性的
    optional 可选的
    required 必填的
    readonly 只读的
    disabled 禁用的
    hidden 隐藏的
    visible 可见的
    sticky 吸顶的
    fixed 固定的
    relative 相对定位的
    absolute 绝对定位的

### 4.知识点总结

- 无障碍
  - 1：无障碍报读顺序（相关文本+标签元素本身）
  - 2：无障碍相关文本报读优先级（aria-labelledby>aria-label>label 标签>placeholder）
  - 3：语法
    - 设置aria-labelledby属性值为某标签id值（可以对应多个id值，空格隔开，依次报读。只能和同一页面的id值对应），报读对应id值标签里的文本
    - 设置aria-label属性值为某文本，报读该文本
    - 设置label标签的for属性值为某标签id值，报读对应id值标签里的文本
    - label标签包裹文本+表单元素（input、select、textarea等），报读该文本
    - 设置placeholder属性值为某文本，报读该文本

- ID 功能拓展
  - ID 在 Web 开发中作为“跨元素锚点”的底层逻辑，而非仅仅是 CSS 选择器

- 表格标签功能拓展
  - 可以当栅栏格使用，给页面添加布局

- select标签功能拓展
  - option标签组合使用 disabled、selected 和 hidden 属性，可实现Placeholder功能
