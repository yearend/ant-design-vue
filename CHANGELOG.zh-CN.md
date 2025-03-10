# 更新日志

`ant-design-vue` 严格遵循 [Semantic Versioning 2.0.0](http://semver.org/lang/zh-CN/) 语义化版本规范。

#### 发布周期

- 修订版本号：日常 bugfix 更新
- 次版本号：带有新特性的向下兼容的版本。
- 主版本号：含有破坏性更新和新特性，不在发布周期内。

---

## 2.1.2

`2021-03-28`

- 🌟 使用 Vue 3.0.9 重新编译，兼容 3.0.7 及以下版本

## 2.1.1

`2021-03-27`

- 🌟 兼容 Vue 3.0.8，注意：由于 3.0.8 的破坏性更新，2.1.1 无法兼容 3.0.7 以下版本 [vue#3493](https://github.com/vuejs/vue-next/issues/3493)
- 🐞 修复 Modal.confirm 缺失 closable ts 类型 [#3684](https://github.com/vueComponent/ant-design-vue/issues/3845)
- 🐞 修复 Upload 自定义 method 不生效问题 [#3843](https://github.com/vueComponent/ant-design-vue/issues/3843)

## 2.1.0

`2021-03-20`

- 🎉🎉🎉 新增 `Typography` 组件 [#3807](https://github.com/vueComponent/ant-design-vue/issues/3807)
- 🌟 Modal 方法新增关闭图标定制 [#3753](https://github.com/vueComponent/ant-design-vue/issues/3753)
- 🐞 修复缺失包含国际化的构建文件 [#3684](https://github.com/vueComponent/ant-design-vue/issues/3684)
- 🐞 修复 Drawer 销毁后报错问题 [#848d64](https://github.com/vueComponent/ant-design-vue/commit/848d6497e68c87566790dfa889a1913199a6699a)
- 🐞 修复 BackTop 在 KeepAlive 激活时，位置不对的问题 [#3803](https://github.com/vueComponent/ant-design-vue/issues/3803)
- 🐞 修复 TreeNode class 不生效问题 [#3822](https://github.com/vueComponent/ant-design-vue/issues/3822)
- 🐞 修复 Table tags 为数组是报错问题 [#3812](https://github.com/vueComponent/ant-design-vue/issues/3812)
- 🐞 修复 Table 自定义 filterIcon 时，触发排序问题 [#3819](https://github.com/vueComponent/ant-design-vue/issues/3819)
- 🐞 修复 Select 样式在 Form 下错位问题 [#3781](https://github.com/vueComponent/ant-design-vue/issues/3781)

## 2.0.1

`2021-02-27`

- 🌟 `Badge` 新增 `Ribbon` [#3681](https://github.com/vueComponent/ant-design-vue/issues/3681)
- 🌟 调整 `SearchInput` search 事件触发顺序 [#3725](https://github.com/vueComponent/ant-design-vue/issues/3725)
- 🐞 修复 `Table` 销毁时卡死问题 [#3531](https://github.com/vueComponent/ant-design-vue/issues/3531)
- 🐞 修复 `Menu` css 中引入了 less 文件问题 [#3678](https://github.com/vueComponent/ant-design-vue/issues/3678)
- 🐞 修复 `Alert` 自定义图标错位问题 [#3712](https://github.com/vueComponent/ant-design-vue/issues/3712)

## 2.0.0

`2021-02-06`

- 🎉🎉🎉 2.0 正式版发布
- 🎉🎉🎉 支持暗黑主题 [#3410](https://github.com/vueComponent/ant-design-vue/issues/3410)
- 🎉🎉🎉 新版文档上线，使用 Composition API 完全重构文档示例，提供 TS、JS 双版本源码
- 🌟 使用 Composition API 重构 `Alert` 组件 [#3654](https://github.com/vueComponent/ant-design-vue/pull/3654)
- 🌟 `Tooltip` 支持自定义颜色 [#3603](https://github.com/vueComponent/ant-design-vue/issues/3603)
- 🐞 修复 `TimePicker` 没有自动滚动到已选位置问题 [#ab7537](https://github.com/vueComponent/ant-design-vue/commit/ab75379f0c2f5e54ab7c348284a7391939ab5aaf)

## 2.0.0-rc.9

`2021-01-24`

- 🌟 `@ant-design/icons-vue` 升级至 6.0，默认使用 es module
- 🌟 `Tabs` 增加 `centered` 居中模式 [#3501](https://github.com/vueComponent/ant-design-vue/issues/3501)
- 🐞 `Progress` 添加 opacity 动画 [#3505](https://github.com/vueComponent/ant-design-vue/issues/3505)
- 🐞 修复 npm 安装时报错问题 [#3515](https://github.com/vueComponent/ant-design-vue/issues/3515)
- 🐞 修复 `Breadcrumn` 分割线不显示问题 [#3522](https://github.com/vueComponent/ant-design-vue/issues/3522)
- 🐞 修复 `Radio` 不受控问题 [#3517](https://github.com/vueComponent/ant-design-vue/issues/3517)
- 🐞 修复 `FormItem` 不换行问题 [#3538](https://github.com/vueComponent/ant-design-vue/issues/3538)
- 🐞 修复 `Carousel` `pauseOnDotsHover` 不生效问题 [#3519](https://github.com/vueComponent/ant-design-vue/issues/3519)
- 🐞 修复 `Input.Search` `class` 不生效问题 [#3541](https://github.com/vueComponent/ant-design-vue/issues/3541)
- 🐞 修复 `InputNumber` 在微软输入法下多次触发 change 事件问题 [#3550](https://github.com/vueComponent/ant-design-vue/issues/3550)
- 🐞 修复 `Tabs` disabled 状态下依然可以通过键盘切换问题 [#3575](https://github.com/vueComponent/ant-design-vue/issues/3575)
- 🐞 修复 `Switch` 在 table 中切换不生效问题 [#3512](https://github.com/vueComponent/ant-design-vue/issues/3512)

## 2.0.0-rc.8

`2021-01-07`

- 🌟 支持 Vite 2 [#3490](https://github.com/vueComponent/ant-design-vue/issues/3490)
- 🌟 使用 Composition API 重构 Affix 组件 [#3447](https://github.com/vueComponent/ant-design-vue/issues/3447)
- 🐞 修复 Image 组件类型定义错误 [#3488](https://github.com/vueComponent/ant-design-vue/issues/3488)
- 🐞 升级 icons-vue 修复 IconFont 组件类型错误 [#3474](https://github.com/vueComponent/ant-design-vue/issues/3474)
- 🐞 修复 less 4 下 Tooltip 箭头样式错误问题 [#3477](https://github.com/vueComponent/ant-design-vue/issues/3477)
- 🐞 修复 Vue 3.0.5 下 DatePicker 类型定义解析错误问题 [#bf7c62](https://github.com/vueComponent/ant-design-vue/commit/bf7c62f457fc14624881f69c5baf9a62219383f7)

## 2.0.0-rc.7

`2020-12-28`

- 🐞 修复 Switch `change`、`click` 不生效问题 [#3453](https://github.com/vueComponent/ant-design-vue/issues/3453)

## 2.0.0-rc.6

`2020-12-27`

- 🌟 支持 Less 4 [#3449](https://github.com/vueComponent/ant-design-vue/issues/3449)
- 🌟 新增 Image 组件 [#3235](https://github.com/vueComponent/ant-design-vue/issues/3235)
- 🌟 函数式组件，添加 displayName 属性 [#3445](https://github.com/vueComponent/ant-design-vue/issues/3445)
- 🐞 Message 新增自定义 class style 功能 [#3443](https://github.com/vueComponent/ant-design-vue/issues/3443)
- 🐞 修复 Tabs 组件初始 disabled 状态没生效 [#3366](https://github.com/vueComponent/ant-design-vue/issues/3366)
- 🐞 修复 Slider 精准度问题 [#3346](https://github.com/vueComponent/ant-design-vue/issues/3346)
- 🐞 修复 Select 滚动高度不正确问题 [#3419](https://github.com/vueComponent/ant-design-vue/issues/3419)
- 🐞 修复 Input small 大小时，高度偏大 2px 问题 [#3396](https://github.com/vueComponent/ant-design-vue/issues/3396)
- 🐞 修复 TreeSelect 触发两次 change 事件问题
- 🐞 修复 TreeSelect 通过 slot 定义 title 死循环问题
- 🐞 修复 Drawer handle slot 触发两次 click 事件问题
- 🌟 新增 Checkbox、Switch 事件声明

## 2.0.0-rc.5

`2020-12-13`

- 🐞 修复 Drawer 组件控制台输出 this.dom 未定义的 warning 问题
- 🐞 修复 Menu 在 Vue 3.0.3 及以上版本，出现显示错乱问题 [#3354](https://github.com/vueComponent/ant-design-vue/issues/3354)

## 2.0.0-rc.4

`2020-12-10`

- 🌟 Input.Password 支持自定义图标 [#3320](https://github.com/vueComponent/ant-design-vue/issues/3320)
- 🐞 修复 Select Option click 事件不触发问题 [#4ea00d](https://github.com/vueComponent/ant-design-vue/commit/4ea00d3a70d0afd7bea07f814df03ab7d0b25ebd)
- 🐞 修复 Menu 超出宽度后 dark 主题不生效问题 [#10f35a](https://github.com/vueComponent/ant-design-vue/commit/10f35a1fa510de91e9484b07fcfff253920cee29)
- 🐞 修复 Menu 控制台 vue key some waring [#520d6a](https://github.com/vueComponent/ant-design-vue/commit/520d6a5e85eb391e5294211c9d7b2ea598c59119)
- 🐞 移除控制台 passive 提示日志 [#8d1669](https://github.com/vueComponent/ant-design-vue/commit/8d1669b8896d84a67c61d3a00d0b13c42d70f30f)

## 2.0.0-rc.3

`2020-12-05`

- 🐞 修复函数式组件在 Vue 3.0.3 下报类型错误问题 [#f5cf7e](https://github.com/vueComponent/ant-design-vue/commit/f5cf7e0920a51f0ac024046996c99260aa41becf)
- 🐞 修复 Menu 超出宽度后显示错误问题 [#3262](https://github.com/vueComponent/ant-design-vue/issues/3262)
- 🐞 修复 Menu subMenuOpenDelay subMenuCloseDelay 不生效问题 [#3291](https://github.com/vueComponent/ant-design-vue/pull/3291)
- 🐞 修复 TreeSelect 堆栈溢出问题 [#28aeea](https://github.com/vueComponent/ant-design-vue/commit/28aeea6f0b142ed68950a3738f7cf2c1581a7a5b)
- 🐞 修复 Input 自定义 style class 被覆盖问题 [#3273](https://github.com/vueComponent/ant-design-vue/issues/3273)
- 🐞 修复 InputNumber 在生产环境下 parse 错误 [#3249](https://github.com/vueComponent/ant-design-vue/issues/3249)

## 2.0.0-rc.2

`2020-11-24`

- 🌟 优化 Menu 性能，默认开启懒加载 [#3243](https://github.com/vueComponent/ant-design-vue/pull/3243)
- 🌟 Tag 支持通过 slot 定义 icon [#3185](https://github.com/vueComponent/ant-design-vue/pull/3185)
- 🌟 small 类型的 table 改成无边框 [#3221](https://github.com/vueComponent/ant-design-vue/issues/3221)
- 🌟 @ant-design/icons-vue 升级到 5.1.6，支持 SSR，支持 spin 属性简写
- 🐞 修复 Alert 的关闭按钮在 Safari 下样式问题 [#3184](https://github.com/vueComponent/ant-design-vue/issues/3184)
- 🐞 修复 Notification top 属性类型错误问题 [#3187](https://github.com/vueComponent/ant-design-vue/issues/3187)
- 🐞 修复 DirectoryTree 自定义图标不生效问题 [#3183](https://github.com/vueComponent/ant-design-vue/issues/3183)
- 🐞 修复 Button loading delay 不生效问题 [#3194](https://github.com/vueComponent/ant-design-vue/issues/3194)
- 💄 Select optionFilterProp 不在支持按照 children 来过滤 [#3204](https://github.com/vueComponent/ant-design-vue/issues/3204)
- 🐞 修复 Select labelInValue 时报错问题 [#3216](https://github.com/vueComponent/ant-design-vue/issues/3216)
- 🐞 修复 ConfigProvider transformCellText 丢失问题 [#3206](https://github.com/vueComponent/ant-design-vue/issues/3206)
- 🐞 修复 Dropdown Button 混合使用时，样式错乱问题 [#3244](https://github.com/vueComponent/ant-design-vue/issues/3244)
- 🐞 修复 RangePicker 自定义宽度失效问题 [#3244](https://github.com/vueComponent/ant-design-vue/issues/3245)
- 🐞 修复多处 Ts 类型错误或缺失问题

## 2.0.0-rc.1

`2020-11-14`

- 🎉🎉🎉
- 🌟 Menu 取消默认懒加载，提升首次动画效果，优化贝塞尔曲线函数，更加流畅 [#3177](https://github.com/vueComponent/ant-design-vue/pull/3177)
- 🐞 修复 Select 搜索功能失效问题 [#3144](https://github.com/vueComponent/ant-design-vue/issues/3144)
- 🐞 修复 Drawer 组件没有自动 focus，导致不能直接通过 ESC 按键关闭 [#3148](https://github.com/vueComponent/ant-design-vue/issues/3148)
- 🐞 修复 Popover 弹出元素位置不正确问题 [#3147](https://github.com/vueComponent/ant-design-vue/issues/3147)
- 🐞 修复 CountDown 不更新问题 [#3170](https://github.com/vueComponent/ant-design-vue/pull/3170)
- 🐞 修复多处 Ts 类型错误或缺失问题

## 2.0.0-beta.15

`2020-11-08`

- 🌟 优化 Menu 动画，更加流畅 [#3095](https://github.com/vueComponent/ant-design-vue/issues/3095)
- 🌟 优化 VirtualList，避免无效 render [#2e61e9](https://github.com/vueComponent/ant-design-vue/commit/2e61e9cb502f2bb6910f59abfb483fd2517e594f)
- 🐞 修复 Menu overflowedIndicator 未生效问题 [#689113](https://github.com/vueComponent/ant-design-vue/commit/689113b3c9c19e929607567a4c8252c6511bff5c)
- 🐞 Select
  - 修复 dropdownRender 不支持 slot 问题 [#3098](https://github.com/vueComponent/ant-design-vue/issues/3098)
  - 修复 tag 模式下，空值异常问题 [#3100](https://github.com/vueComponent/ant-design-vue/issues/3100)
  - 修复单选模式下选择项不更新问题 [#3099](https://github.com/vueComponent/ant-design-vue/issues/3099)
  - 修复特殊场景下 foucs 状态不生效问题 [#3099](https://github.com/vueComponent/ant-design-vue/issues/3099)
- 🐞 修复 DatePicker 默认格式化失效问题 [#3091](https://github.com/vueComponent/ant-design-vue/issues/3091)
- 🐞 修复 Table customRow 配置事件不生效问题 [#3121](https://github.com/vueComponent/ant-design-vue/issues/3121)
- 🐞 修复 TreeSelect 搜索框样式错乱问题 [ee4cd3c](https://github.com/vueComponent/ant-design-vue/commit/ ee4cd3c35a84658cbbb148ce368bc247a927d528)
- 🐞 修复 Ts 类型错误或缺失问题

## 2.0.0-beta.13

`2020-11-02`

- 🐞 修复 npm install 报错问题 [#3080](https://github.com/vueComponent/ant-design-vue/issues/3080)
- 🐞 修复 Select maxPlaceHolder 显示错误问题 [#3085](https://github.com/vueComponent/ant-design-vue/issues/3085)
- 🐞 修复弹窗类组件，弹出位置不更新问题 [#3085](https://github.com/vueComponent/ant-design-vue/issues/3085)
- 🐞 修复 Table 数据为空时的 warning 问题 [#3082](https://github.com/vueComponent/ant-design-vue/issues/3082)
- 🐞 修复 Input 在 Form 中显示多个边框问题 [#3084](https://github.com/vueComponent/ant-design-vue/issues/3084)

## 2.0.0-beta.12

`2020-11-01`

- 🐞 修复 dist/antd.css 缺失组件样式问题 [#3069](https://github.com/vueComponent/ant-design-vue/issues/3069)
- 🐞 修复 Input 样式问题 [#3074](https://github.com/vueComponent/ant-design-vue/issues/3074)
- 🐞 修复 Form layout="vertical" 样式问题 [#3075](https://github.com/vueComponent/ant-design-vue/issues/3075)
- 🐞 修复 Select 无法打开弹窗问题 [#3070](https://github.com/vueComponent/ant-design-vue/issues/3070)

## 2.0.0-beta.11

`2020-10-30`

- 🎉🎉🎉 重构 Select、AutoComplete 组件，支持虚拟列表，性能大幅提升
- 🔥🔥🔥 使用 Typescript 重构所有组件，类型支持更加友好
- 🔥 优化底层动画组件，性能更好，更流畅
- 🌟 Textarea 组件添加 showCount 支持统计字数功能
- 🌟 递归 Menu 组件，支持任意嵌套其他元素 [#1452](https://github.com/vueComponent/ant-design-vue/issues/1452)
- 🇮🇪 添加爱尔兰语国际化支持
- 🐞 修复 webpack 5 兼容问题。
- 🐞 修复 Upload method 属性不生效问题 [#2837](https://github.com/vueComponent/ant-design-vue/issues/2837)
- 🐞 修复 Table 组件 filter 不支持 number 类型问题 [#3052](https://github.com/vueComponent/ant-design-vue/issues/3052)
- 🐞 修复 Table 固定列 ellipsis 不生效问题 [#2916](https://github.com/vueComponent/ant-design-vue/issues/2916)
- 🐞 修复 Table 自定义 expandIcon 不生效问题 [#3013](https://github.com/vueComponent/ant-design-vue/issues/3013)
- 🐞 修复 TreeSelect 不能自定义 slot 问题 [#2827](https://github.com/vueComponent/ant-design-vue/issues/2827)
- 🛎 更改 Avatar 的 srcSet 为 srcset

## 2.0.0-beta.10

`2020-09-24`

- 🌟 更新 Vue 依赖到 release 版本
- 🐞 修复 Menu 在 Layout 中不折叠问题 [#2819](https://github.com/vueComponent/ant-design-vue/issues/2819)
- 🐞 修复 Tabs 切换时出现 warning 问题 [#2865](https://github.com/vueComponent/ant-design-vue/issues/2865)
- 🐞 修复输入框在 compositionend 时不触发 change 事件问题
- 🐞 修复 Upload 上传按钮不消失问题 [#2884](https://github.com/vueComponent/ant-design-vue/issues/2884)
- 🐞 修复 Upload 自定义 method 不生效问题 [#2837](https://github.com/vueComponent/ant-design-vue/issues/2837)
- 🐞 修复若干 ts 类型错误

## 2.0.0-beta.8

- 🐞 修复 ts 类型错误

## 2.0.0-beta.7

- 🐞 修复 Descriptions Item 不支持 v-for 问题 [#2793](https://github.com/vueComponent/ant-design-vue/issues/2793)
- 🐞 修复 Modal button loading 效果不生效问题 [9257c1](https://github.com/vueComponent/ant-design-vue/commit/9257c1ea685db4339239589153aee3189d0434fe)
- 🐞 修复 Steps 组件使用 v-model 时不可点击的问题 [ec7309](https://github.com/vueComponent/ant-design-vue/commit/ec73097d9b6ea8e2f2942ac28853c19191ca3298)
- 🌟 Checkbox、Radio 添加事件声明
- 🐞 修复 ts 类型错误 [802446](https://github.com/vueComponent/ant-design-vue/commit/8024469b8832cfc4fe85498b639bfb48820531aa)

## 2.0.0-beta.6

- 🐞 修复 TreeSelectNode 子组件 TreeSelectNode 没有注册的问题

## 2.0.0-beta.5

- 🔥 支持 Vite。

## 2.0.0-beta.4

- 🌟 移除不再使用的 polyfill
- 🐞 修复 `Modal` afterClose 调用两次的问题
- 🐞 补充 ts 类型文件缺少原生属性的声明

## 2.0.0-beta.3

- 🔥 支持 Typescript。
- 🔥 新增 `Space` 组件。
- 🐞 修复部分组件无法使用 css scope 问题 [4bdb24](https://github.com/vueComponent/ant-design-vue/commit/4bdb241aa674b50fafa29b3b98e291643f2a06cc)。
- 🐞 修复 `List.Meta` 注册失败的问题 [03a42a](https://github.com/vueComponent/ant-design-vue/commit/03a42a5b35e7d42a39aedb1aba8346995be2c27e)
- 🐞 修复 `Table` 固定列情况下错位问题 [#1493](https://github.com/vueComponent/ant-design-vue/issues/1493)
- 🐞 修复 `Button` 没有垂直居中的问题 [bd71e3](https://github.com/vueComponent/ant-design-vue/commit/bd71e3806b73881f9a95028982d17a10b2cd0b5c)
- 🐞 修复 `Tabs` 多次出发 `change` 事件问题 [8ed937](https://github.com/vueComponent/ant-design-vue/commit/8ed937344a57142a575e5272f50933c9c4459a43)

## 2.0.0-beta.2

`2020-08-14`

### 设计规范调整

- 行高从 `1.5`(`21px`) 调整为 `1.5715`(`22px`)。
- 基础圆角调整，由`4px` 改为 `2px`。
- 分割线颜色明度降低，由 `#E8E8E8` 改为 `#F0F0F0`。
- Table 默认背景颜色从透明修改为白色。

### 兼容性调整

- IE 最低支持版本为 IE 11。
- Vue 最低支持版本为 Vue 3.0。

#### 调整的 API

- 移除了 LocaleProvider，请使用 `ConfigProvider` 替代。
- 移除了 Tag 的 afterClose 属性。
- 合并了 FormModel、Form，详见下方的 Form 重构部分。
- `tabIndex`、`maxLength`、`readOnly`、`autoComplete`、`autoFocus` 更改为全小写。
- 为了在 template 语法中更友好的使用插槽，所有涉及到 xxxRender, renderXxxx 的均改成单参数，涉及到 `itemRender`、`renderItem`、`customRender`、`dropdownRender`、`dateCellRender`、`dateFullCellRender`、`monthCellRender`、`monthFullCellRender`、`renderTabBar`。
- 所有配置 scopedSlots 的地方统一改成 slots。
- `{ on, props, attrs, ... }` 配置进行扁平化处理，如 `{ props: {type: 'xxx'}, on: {click: this.handleClick}}` 改成 `{ type: 'xxx', onClick: this.handleClick }`, 涉及相关字段：`okButtonProps`、`cancelButtonProps`。
- xxx.sync 改成 v-model:xxx
- v-model 更改成 v-model:xxx，具体涉及组件：

  - v-model 改成 v-model:checked 的组件有: CheckableTag、Checkbox、Switch
  - v-model 改成 v-model:value 的组件有: Radio、Mentions、CheckboxGroup、Rate、DatePicker
  - v-model 改成 v-model:visible 的组件有: Tag、Popconfirm、Popove、Tooltip、Moda、Dropdown
  - v-model 改成 v-model:activeKey 的组件有: Collaps、Tabs
  - v-model 改成 v-model:current 的组件有: Steps
  - v-model 改成 v-model:selectedKeys 的组件有: Menu

#### 图标升级

在 `ant-design-vue@1.2.0` 中，我们引入了 svg 图标（[为何使用 svg 图标？](https://github.com/ant-design/ant-design/issues/10353)）。使用了字符串命名的图标 API 无法做到按需加载，因而全量引入了 svg 图标文件，这大大增加了打包产物的尺寸。在 2.0 中，我们调整了图标的使用 API 从而支持 tree shaking，减少默认包体积约 150 KB(Gzipped)。

旧版 Icon 使用方式将被废弃：

```html
<a-icon type="smile" /> <a-button icon="smile" />
```

2.0 中会采用按需引入的方式：

```html
<template>
  <smile-outlined />
  <a-button>
    <template v-slot:icon><smile-outlined /></template>
  </a-buttom>
</template>
<script>
import SmileOutlined from '@ant-design/icons-vue/SmileOutlined';
export default {
  components: {
    SmileOutlined
  }
}
</script>
```

#### 组件重构

在 1.x 中我们提供了 Form、FormModel 两个表单组件，原有的 Form 组件使用 v-decorator 进行数据绑定，在 Vue2 中我们通过上下文进行强制更新组件，但是在 Vue3 中，由于引入 patchFlag 等优化方式，强制刷新会破坏 patchFlag 带来的性能优势。所以在 2.0 版本中我们将 Form、FormModel 进行合并，保留了 FormModel 的使用方式，丰富了相关功能，并改名成 Form。

涉及改动：

- Form 新增 `scrollToFirstError`,`name`,`validateTrigger` 属性，新增 `finish`、`finishFailed` 事件，新增 `scrollToField` 方法。
- Form.Item 新增 `validateFirst`, `validateTrigger`, 废弃 `prop` 属性，使用 `name` 替换。
- 嵌套字段路径使用数组，过去版本我们通过 . 代表嵌套路径（诸如 user.name 来代表 { user: { name: '' } }）。然而在一些后台系统中，变量名中也会带上 .。这造成用户需要额外的代码进行转化，因而新版中，嵌套路径通过数组来表示以避免错误的处理行为（如 ['user', 'name']）。
- validateFields 不再支持 callback。validateFields 会返回 Promise 对象，因而你可以通过 async/await 或者 then/catch 来执行对应的错误处理。不再需要判断 errors 是否为空：

```js
// v1
validateFields((err, value) => {
  if (!err) {
    // Do something with value
  }
});
```

改成

```js
// v2
validateFields().then(values => {
  // Do something with value
});
```

## 1.6.4

`2020-07-21`

- 🐞 修复面包屑 `Breadcrumb` 重复 key 问题 [#2505](https://github.com/vueComponent/ant-design-vue/issues/2505)
- 🐞 修复 MenuItem title 为空时，依然有 Tooltip 问题 [#2526](https://github.com/vueComponent/ant-design-vue/issues/2505)
- 🐞 修复 Input textarea 激活 allow-clear 时无法向上拖动的问题。[#2563](https://github.com/vueComponent/ant-design-vue/issues/2563)
- 🌟 添加 less 变量 @select-item-selected-color [#2458](https://github.com/vueComponent/ant-design-vue/issues/2458)
- 🌟 Grid 中 Col 添加 flex 属性 [#2558](https://github.com/vueComponent/ant-design-vue/issues/2558)

## 1.6.3

`2020-07-05`

- 🐞 修复 Input.Password focus 位置移位问题 [#2420](https://github.com/vueComponent/ant-design-vue/pull/2420)
- 🐞 修复 Drawer maskstyle 不生效问题 [#2407](https://github.com/vueComponent/ant-design-vue/issues/2407)
- 🐞 修复 Drawer maskstyle 不生效问题 [#2407](https://github.com/vueComponent/ant-design-vue/issues/2407)
- 🌟 Button 支持自定义 Icon [#2245](https://github.com/vueComponent/ant-design-vue/pull/2245)
- 🌟 DatePicker 支持自定义 format [#2276](https://github.com/vueComponent/ant-design-vue/pull/2276)
- 🐞 修复 DatePicker 年份时间不正确问题 [#2488](https://github.com/vueComponent/ant-design-vue/issues/2488)
- 🌟 优化 Menu 组件，动画更加流畅
- 🐞 修复 Dropdown 弹窗位置错误问题 [#2359](https://github.com/vueComponent/ant-design-vue/issues/2359)
- 🐞 修复 Breadcrumb 名称相同时重复 key 问题 [#2505](https://github.com/vueComponent/ant-design-vue/issues/2505)

## 1.6.2

`2020-06-02`

- 🐞 修复弹窗 dialogClass 类型错误 [#2298](https://github.com/vueComponent/ant-design-vue/issues/2298)
- 🐞 修复 RangePicker 面板展示错误 [#2318](https://github.com/vueComponent/ant-design-vue/issues/2318)

## 1.6.1

`2020-05-25`

- 🐞 修复 DatePicker blur 时填充当前时间的问题 [#2246](https://github.com/vueComponent/ant-design-vue/issues/2246)
- 🐞 修复 Drawer 销毁时报错问题 [#2254](https://github.com/vueComponent/ant-design-vue/issues/2254)
- 🐞 修复 Tabs 不能移除已 0 作为 key 的选项卡 [55bbf9](https://github.com/vueComponent/ant-design-vue/commit/55bbf940401cf2a67114102da1c035abc4152f06)
- 🐞 修复 Menu 触发两次 click 事件的问题 [#2266](https://github.com/vueComponent/ant-design-vue/issues/2266)
- 🐞 修复 Menu active 类名没有添加问题 [ffc002](https://github.com/vueComponent/ant-design-vue/commit/ffc002f09454a56b531aeb08530303d566cf24f2)
- 🌟 TreeSelect 添加自定义数据字段功能 [#2253](https://github.com/vueComponent/ant-design-vue/issues/2253)
- 🌟 Modal 新增 dialogStyle、dialogClass 代替重构前的 style、class [#2285](https://github.com/vueComponent/ant-design-vue/issues/2285)
- 🐞 修复 Table 排序触发无限更新问题 [#2270](https://github.com/vueComponent/ant-design-vue/issues/2270)

## 1.6.0

`2020-05-15`

- 🌟 Tootip 支持自定义组件 [741897](https://github.com/vueComponent/ant-design-vue/commit/741897be6742c752f0b0d29481add702ee7e7fb0)
- 🐞 重构 Modal、Drawer 底层 Portal 组件，解决 Modal、Drawer 内容更新延迟问题 [#2244](https://github.com/vueComponent/ant-design-vue/issues/2244)
- 🐞 修复 Input.Group 中 Select 选项 focus 边框样式 [#2224](https://github.com/vueComponent/ant-design-vue/pull/2224)
- 🐞 修复 Cascader 选项图标禁用时的颜色 [#2223](https://github.com/vueComponent/ant-design-vue/pull/2223)
- 🐞 修复 DatePicker 分隔符禁用时颜色 [#2222](https://github.com/vueComponent/ant-design-vue/pull/2222)
- 🐞 修复 Carousel 键盘切换到非活跃 slide 上的 Radio/Checkbox 的问题。
- 🐞 修复 Table 筛选菜单在 less 版本为 `2.x` 时不显示的问题。[#23272](https://github.com/ant-design/ant-design/pull/23272)
- 🐞 修复 Table `column.filtered` 失效的问题。
- 🐞 修复 Select `multiple` 模式下，Input 在 Safari 浏览器的样式问题。[#22586](https://github.com/ant-design/ant-design/pull/22586)
- 🐞 修复 Descriptions 在小尺寸下无法自适应的问题。[#22407](https://github.com/ant-design/ant-design/pull/22407)

## 1.5.6

`2020-05-09`

- 🐞 修复 dist 文件夹丢失 css、min.js 等文件问题

## 1.5.5

`2020-05-08`

- 🐞 修复 `Tabs` 在 safari 13 下不展示问题 [#2199](https://github.com/vueComponent/ant-design-vue/issues/2199)
- 🐞 修复 `Input` 在 FireFox 下第一次输入失败问题 [#2151](https://github.com/vueComponent/ant-design-vue/issues/2151)
- 🐞 修复 `Input` 在 Modal 组件中光标移位问题 [#2207](https://github.com/vueComponent/ant-design-vue/issues/2207)

## 1.5.4

`2020-04-30`

- 🌟 `DatePicker` 支持 align 属性，设置弹窗位置 [#1112f2](https://github.com/vueComponent/ant-design-vue/commit/1112f2f791fd64866284ec82def90baefe81e798)
- 🌟 `DatePicker` 支持 inputReadOnly 属性 [#138eae](https://github.com/vueComponent/ant-design-vue/commit/138eae594dd440ce815e45d811a0778cb3e7583f)
- 🌟 `DatePicker` `TimePicker` `Calendar` 支持字符串类型的绑定值 [#718](https://github.com/vueComponent/ant-design-vue/issues/718)
- 🌟 `Table` `ConfigProvider` 新增 `transformCellText` 用于转换表格渲染值, 如对空数据的处理 [#2109](https://github.com/vueComponent/ant-design-vue/issues/2109)
- 🌟 `FormModel` 新增 validateMessages 属性 [#2130](https://github.com/vueComponent/ant-design-vue/issues/2130)
- 🌟 优化弹窗动画效果 [#bf52f73](https://github.com/vueComponent/ant-design-vue/commit/bf52f73c5c2f8d05981e426b41a5f46d66e096db)
- 🐞 修复 `Tabs` 组件的 `tabBarGutter` 属性不生效问题 [#2083](https://github.com/vueComponent/ant-design-vue/issues/2083)
- 🐞 修复 `Tabs` 组件的 renderTabBar 不生效问题 [#2157](https://github.com/vueComponent/ant-design-vue/issues/2157)
- 🌟 `Tabs` 组件支持数字 0 作为 key [#2167](https://github.com/vueComponent/ant-design-vue/issues/2167)
- 🐞 修复 `Input.Search` 组件的样式错位问题 [#2077](https://github.com/vueComponent/ant-design-vue/issues/2077)
- 🐞 修复 `Slider` 组件的样式错位问题 [#2097](https://github.com/vueComponent/ant-design-vue/issues/2097)
- 🐞 修复 `Tree.TreeNode` customTitle 作用域插槽无法获取 selected 状态问题 [#2006](https://github.com/vueComponent/ant-design-vue/issues/2006)
- 🐞 修复 `SelectTree` showSearch 时报错问题 [#2082](https://github.com/vueComponent/ant-design-vue/issues/2082)
- 🐞 修复 `Badge` dot 状态的原圆点位置不一致问题 [#2121](https://github.com/vueComponent/ant-design-vue/issues/2121)

## 1.5.3

`2020-04-13`

- 🐞 修复 `Dropdown` visible 不变时，内容不响应更新的问题 [#81eb40](https://github.com/vueComponent/ant-design-vue/commit/81eb401a8899aa3fe0acca88340b323f6e09db45)

## 1.5.2

`2020-04-09`

- 🐞 修复 `FormModel` 的 ts 类型未引入 [#1996](https://github.com/vueComponent/ant-design-vue/issues/1966)
- 🐞 修复 `DatePicker.WeekPicker` 的类型文件错误 [#2044](https://github.com/vueComponent/ant-design-vue/issues/2044)
- 🐞 修复 `Tabs` tabClick 事件不生效问题 [#2030](https://github.com/vueComponent/ant-design-vue/issues/2030)
- 🐞 修复 `Table` resize 时报错问题 [#2033](https://github.com/vueComponent/ant-design-vue/issues/2033)

## 1.5.1

`2020-04-02`

- 🐞 修复 `PageHeader` 不能隐藏 backIcon 问题 [#1987](https://github.com/vueComponent/ant-design-vue/pull/1987)
- 🐞 修复 `Pagination` 的 total 变化时，不更新问题 [#1989](https://github.com/vueComponent/ant-design-vue/pull/1989)
- 🐞 修复 `TreeSelect` 输入中文时 placeholder 不消失问题 [#1994](https://github.com/vueComponent/ant-design-vue/pull/1994)
- 🐞 修复 `Table` customRender 不能自定义 class style 问题 [#2004](https://github.com/vueComponent/ant-design-vue/pull/2004)
- 🐞 修复 `Form` 使用 Form.create 时，丢失插槽内容问题 [#1998](https://github.com/vueComponent/ant-design-vue/pull/1998)
- 🐞 修复 `Textarea` 滚动条闪动问题 [#1964](https://github.com/vueComponent/ant-design-vue/pull/1964)
- 🌟 添加 `FormModel` 的 ts 类型文件 [#1996](https://github.com/vueComponent/ant-design-vue/issues/1966)
- 🌟 添加 `Modal` 的 destroyAll 类型声明 [#1993](https://github.com/vueComponent/ant-design-vue/pull/1963)

## 1.5.0

`2020-03-29`

- 新增了五个组件：
  - 🔥🔥🔥 [Mentions](https://antdv.com/components/mentions-cn/) 新增提及组件并废弃原有 Mention 组件。
  - 🔥🔥🔥 [Descriptions](https://antdv.com/components/descriptions-cn/) 成组展示多个只读字段。
  - 🔥🔥🔥 [PageHeader](https://antdv.com/components/page-header-cn/) 可用于声明页面主题、展示用户所关注的页面重要信息，以及承载与当前页相关的操作项。
  - 🔥🔥🔥 [Result](https://antdv.com/components/result) 用于反馈一系列操作任务的处理结果。
  - 🔥🔥🔥 [FormModel](https://antdv.com/components/form-model) 使用 v-model 进行自动校验的表单组件，相较于 v-decorator 形式的表单，更加简洁。
- 🔥 Descriptions 支持垂直布局。
- 🔥 Progress.Circle 支持渐变色。
- 🔥 Progress.Line 支持渐变色。
- Breadcrumb
  - 🎉 Breadcrumb.Item 支持 `overlay` 属性来定义下拉菜单。
  - 🌟 新增 `Breadcrumb.Separator` 组件，可进行 `separator` 自定义。
- 🌟 TreeSelect 的 `showSearch` 支持多选模式。
- 🌟 Timeline.Item 新增 `gray` 色彩类型，可用于未完成或失效状态。
- 🌟 Modal 支持 `closeIcon` 属性用于自定义关闭图标。
- 🌟 Upload
  - 🌟 Upload 提供 `previewFile` 属性以自定义预览逻辑。
  - 🌟 Upload 新增 `transformFile` 支持上传之前转换文件。
  - 🌟 Upload 支持预览 `jfif` 格式图片。
  - 🌟 新增 `showDownloadIcon` 属性，用于展示下载图标。
- 🌟 Input.Search 新增 `loading` 属性，用于展示加载中的状态。
- 🌟 Grid 的 `gutter` 属性新增垂直间距的支持，现在你可以给 `gutter` 设置一个数组，数组的第二个值就表示垂直间距。
- 🌟 message 新增支持通过唯一的 `key` 来更新内容。
- 🌟 TextArea 支持 `allowClear`。
- 🌟 Dropdown.Button 支持 `icon` 属性来自定义图标。
- Drawer
  - 🌟 支持 `afterVisibleChange` 属性，在抽屉动画完成后触发。
  - 🌟 支持 `ESC` 关闭。
  - 🌟 新增 `keyboard`，允许打开关闭对键盘事件的响应。
- 🌟 TreeNode 支持 `checkable` 属性。
- 🌟 Transfer 支持 `children` 来自定义渲染列表。
- 🌟 Pagination 支持 `disabled` 属性。
- 🌟 Steps 支持点击切换功能。
- Slider
  - 🌟 支持 `tooltipPlacement` 以定义提示所在位置。
  - 🌟 支持 `getTooltipPopupContainer` 以允许自定义提示所在容器。
  - 🌟 当 Sider 在右边时，翻转 `trigger` 方向。
- 🌟 Calendar 支持 `headerRender` 以自定义头部。
- 🌟 Carousel 支持自定义面板指示点的位置。
- 🌟 Collapse 支持 `expandIconPosition` 属性。
- 🌟 Popconfirm 增加 `disabled` props，用于控制点击子元素是否弹出。
- 🌟 Select 在多选模式下支持 `showArrow`。
- 🌟 Collapse.Panel 新增了 `extra`。
- Card
  - 🌟 Card 组件新增了 `tabBarExtraContent` 属性。
  - 🌟 Card.Grid 新增 `hoverable` 属性允许禁用浮动效果。
- 🌟 Anchor.Link 增加 `target` 属性。
- 🌟 TimePicker 新增了 `clearIcon` prop，用于自定义清除图标。
- Form
  - 🌟 支持直接在 Form 上面配置 `colon` 属性。
  - 🌟 支持 `labelAlign` 属性。
- Table
  - 🌟 Table 新增 `getPopupContainer` 属性用于设置表格内的各类浮层渲染节点。
  - 💄 调整 Table 展开按钮的样式。
  - 🌟 新增 `tableLayout` 属性，支持设置表格的 `table-layout` 布局，并在固定表头/列下默认开启 `tableLayout="fixed"`，解决因为表格自动根据内容排版造成的列对齐问题。
  - 🌟 新增 `column.ellipsis` 支持单元格内容自动省略。
  - 🌟 新增 `scroll.scrollToFirstRowOnChange` 属性，用于设置在翻页后是否滚动到表格顶部。
  - 🌟 `filterDropdown` 新增 `visible` 参数，用于获取下拉框的显示状态。
  - 🌟 `title` 方法新增 `sortColumn` 参数，用于获取当前排序的列。
  - 🌟 排序时 `onChange` 的 `sorter` 参数将始终包含 `column` 信息。
- 🌟 Tree 组件支持 `blockNode` 属性。
- 🌟 RangePicker 添加 `separator` 定义。
- Empty
  - 🌟 Empty 支持 `imageStyle` 属性。
  - 🌟 Empty `description` 支持 `false`。
  - 🌟 Empty 支持通过 `Empty.PRESENTED_IMAGE_DEFAULT` 和 `Empty.PRESENTED_IMAGE_SIMPLE` 访问预置图片。
- 🌟 Badge 支持自定义颜色。
- 🐞 修复 Steps 的 label 不居中的问题。
- 🐞 修复 DatePicker 和 TimePicker 的 cursor 样式问题。
- 🐞 修复 TreeSelect 自定义图标无效的问题 [#1901](https://github.com/vueComponent/ant-design-vue/issues/1901)
- 🐞 修复 Tabs 键盘左右切换错误问题 [#1947](https://github.com/vueComponent/ant-design-vue/issues/1947)

## 1.4.12

`2020-03-03`

- 🐞 修复 `Modal` 组件 ts 类型报错问题 [#1809](https://github.com/vueComponent/ant-design-vue/issues/1809)

## 1.4.11

`2020-02-12`

- 🌟 DirectoryTree 新增自定义 switcherIcon 功能 [#1743](https://github.com/vueComponent/ant-design-vue/issues/1743)
- 🌟 新增可拖拽调整表格列宽[示例](https://www.antdv.com/components/table/#components-table-demo-resizable-column)
- 🌟 替换所有组件的 `this.$listeners` 避免组件重复渲染 [#1705](https://github.com/vueComponent/ant-design-vue/issues/1705)
- 🐞 修复 ConfigProvider 组件更改属性时，报错问题 [7a4003](https://github.com/vueComponent/ant-design-vue/commit/7a40031955d520487dcaf9054a1280ae72230049)
- 🐞 修复 AutoComplete 组件自定义输入框时，placeholder 不消失问题 [#1761](https://github.com/vueComponent/ant-design-vue/issues/1761)
- 🐞 修复 Statistic.Countdown 不触发 finish 事件的问题 [#1731](https://github.com/vueComponent/ant-design-vue/pull/1731)
- 🐞 修复 Upload 组件预览图片不刷新问题 [f74469](https://github.com/vueComponent/ant-design-vue/commit/f744690e929d9d6da03c5c513b3ac5497c6490ef)
- 🐞 修复 TimePicker id 不唯一问题 [#1566](https://github.com/vueComponent/ant-design-vue/pull/1566)
- 🐞 修复 Pagination 分页无动画问题 [#1540](https://github.com/vueComponent/ant-design-vue/issues/1540)
- 🐞 修复 Cascader 的 option 为空数组时,下拉列表不展示空元素问题 [#1701](https://github.com/vueComponent/ant-design-vue/issues/1540)
- 🐞 修复 Input 组件的 spellcheck 渲染不正确问题 [#1707](https://github.com/vueComponent/ant-design-vue/issues/1707)
- 🐞 修复 Tree 组件无法自定义 icon 问题 [#1712](https://github.com/vueComponent/ant-design-vue/pull/1712)
- 🐞 修复 SubMenu forceSubMenuRender 属性失效问题 [#1668](https://github.com/vueComponent/ant-design-vue/issues/1668)
- 🐞 修复 Upload 按钮样式错位问题 [#1742](https://github.com/vueComponent/ant-design-vue/pull/1742)

## 1.4.10

`2019-12-11`

- 🐞 修复 `MonthPicker` 左右箭头切换月份失效问题 [#1543](https://github.com/vueComponent/ant-design-vue/issues/1543)

## 1.4.9

`2019-12-10`

- 🐞 修复 `Modal` 打开时，body 滚动问题 [#1472](https://github.com/vueComponent/ant-design-vue/issues/1472)
- 🐞 修复 `Drawer` wrapStyle 不生效问题 [#1481](https://github.com/vueComponent/ant-design-vue/issues/1481)
- 🐞 修复 `InputNumber` id 挂载位置不正确的问题 [#1477](https://github.com/vueComponent/ant-design-vue/issues/1477)
- 🐞 修复 `Tabs` nextClick 事件不触发的问题 [#1489](https://github.com/vueComponent/ant-design-vue/pull/1489)
- 🐞 修复 `MonthPicker` 在 open 状态下，不能更改值的问题 [#1510](https://github.com/vueComponent/ant-design-vue/issues/1510)
- 🐞 修复 `AutoComplete` 在输入中文时 `placeholder` 不消失的问题 [#1506](https://github.com/vueComponent/ant-design-vue/issues/1506)
- 🐞 修复在引用不同 Vue 变量时，无法弹出内容的问题 [6362bf](https://github.com/vueComponent/ant-design-vue/commit/6362bf9edb441c0c0096beca1d2c8727003dbb15)
- 🌟 `Table` `customRender` 添加第三个 column 参数 [#1513](https://github.com/vueComponent/ant-design-vue/pull/1513)
- 🌟 `InputPassword` 添加 focus、blur 方法 [#1485](https://github.com/vueComponent/ant-design-vue/pull/1485)
- 🐞 修复 `Tooltip` 使用在原生 html 元素时报错的问题 [#1519](https://github.com/vueComponent/ant-design-vue/issues/1519)
- 🐞 修复 `Menu` 在 edge 浏览器下报错的问题 [#1492](https://github.com/vueComponent/ant-design-vue/issues/1492)
- 🐞 修复 `Select` 的 empty 不居中的问题 [#1445](https://github.com/vueComponent/ant-design-vue/pull/1445)
- 🐞 修复弹窗类组件内存泄漏问题 [#1483](https://github.com/vueComponent/ant-design-vue/pull/1483)

## 1.4.8

`2019-11-28`

- 🐞 修复 `Menu` click 事件不触发的问题 [#1470](https://github.com/vueComponent/ant-design-vue/issues/1470)
- 🐞 修复 `Tooltip` 在 keep-alive 下不消失的问题 [16ec40](https://github.com/vueComponent/ant-design-vue/commit/16ec40a012d7c400bf3028e6c938050dd6d7de2f)

## 1.4.7

`2019-11-27`

- 🌟 `ConfigProvider` 的 `getPopupContainer` 新增弹窗上下文做为第二个参数，用于统一配置 `Modal` 内的 `getPopupContainer` [7a3c88](https://github.com/vueComponent/ant-design-vue/commit/7a3c88107598b4b1cf6842d3254b43dc26103c14)
- 🐞 修复 `ConfigProvider` 在 Vue 2.5 版本下报错问题 [309baa](https://github.com/vueComponent/ant-design-vue/commit/309baa138a9c9a1885c17ef636c9132349024359)
- 🐞 修复 `Menu` click 事件触发两次的问题 [#1450](https://github.com/vueComponent/ant-design-vue/issues/1427)
- 🐞 修复 `Select` 内的 input 框宽度不正确的问题 [#1458](https://github.com/vueComponent/ant-design-vue/issues/1458)
- 🐞 修复 `Select` 在输入中文时 `placeholder` 不消失的问题 [#1458](https://github.com/vueComponent/ant-design-vue/issues/1458#issuecomment-557477782)
- 🌟 添加 `Comment` 组件的 TS 类型声明 [#1453](https://github.com/vueComponent/ant-design-vue/pull/1453)

## 1.4.6

`2019-11-20`

- 🐞 修复 `Cascader` 不能输入空格的问题 [#1427](https://github.com/vueComponent/ant-design-vue/issues/1427)
- 🐞 修复 `AutoComplete` 不能删除最后一个字符的问题 [#1429](https://github.com/vueComponent/ant-design-vue/issues/1427)
- 🐞 更新 `Tree` 的 `expandAction` 中的 `dbclick` 为 `dblclick` [#1437](https://github.com/vueComponent/ant-design-vue/issues/1437)
- 🐞 更新 `Table` 文档中的 `dbclick` 为 `dblclick` [#1437](https://github.com/vueComponent/ant-design-vue/issues/1437)
- 🌟 添加 `Empty` 组件的 TS 类型声明 [#1439](https://github.com/vueComponent/ant-design-vue/pull/1439)

## 1.4.5

`2019-11-16`

- 🌟 `Form` 支持 `labelCol` `wrapperCol` 统一设置布局 [#1365](https://github.com/vueComponent/ant-design-vue/pull/1365)
- 🌟 `Input` `Select` `DatePicker` 输入中文完毕后触发相关事件，减少不必要的性能消耗[#1281](https://github.com/vueComponent/ant-design-vue/issues/1281)
- 🐞 修复 `Input` `Select` 的 placeholder 为中文时，在 ie 下自动触发 change 事件问题 [#1387](https://github.com/vueComponent/ant-design-vue/issues/1387)
- Tree

  - 🌟 添加 replaceFields 字段用来自定义 title children。[#1395](https://github.com/vueComponent/ant-design-vue/issues/1395)
  - 🌟 更新事件 doubleclick 为 dbclick [5e27ff](https://github.com/vueComponent/ant-design-vue/commit/5e27ff8da4419f490ab5c6ebeaf43d933519fcd7)

- 🐞 修复 Input 在 ie9 下删除内容不触发 change 事件问题 [#1421](https://github.com/vueComponent/ant-design-vue/issues/1421)
- 🐞 修复 Dropdown disabled 无效问题 [#1400](https://github.com/vueComponent/ant-design-vue/issues/1400)
- 🐞 修复 Select lableInValue 时类型校验错误 [#1393](https://github.com/vueComponent/ant-design-vue/pull/1393)
- 🐞 修复 Comment 样式问题 [#1389](https://github.com/vueComponent/ant-design-vue/pull/1389)
- 🐞 修复 `Statistic` `Password` TypeScript 类型定义。

## 1.4.4

`2019-10-30`

- 🌟 Progress format 支持 v-slot [#1348](https://github.com/vueComponent/ant-design-vue/issues/1348)
- 🐞 修复 RangePicker 年份面板失效问题 [#1321](https://github.com/vueComponent/ant-design-vue/issues/1321)
- 🐞 修复 Pagination simple 模式失效问题 [#1333](https://github.com/vueComponent/ant-design-vue/issues/1333)
- 🐞 修复 AutoComplete 快速输入时闪动现象 [#1327](https://github.com/vueComponent/ant-design-vue/issues/1327)
- 🐞 修复 Button loading 模式下不居中问题 [#1337](https://github.com/vueComponent/ant-design-vue/issues/1337)
- 🐞 修复 Menu margin 间距重叠，以及导致的展开时卡顿问题 [#873](https://github.com/vueComponent/ant-design-vue/issues/873)
- 🐞 修复 Checkbox v-model 参数校验失败问题 [#1356](https://github.com/vueComponent/ant-design-vue/issues/1356)
- 🐞 修复 Checkbox.Group 更新 value undefined 时报错问题 [#1356](https://github.com/vueComponent/ant-design-vue/issues/1356)

## 1.4.3

`2019-10-22`

- 🐞 修复 Input 导致的 Cascader 组件样式问题 [#1293](https://github.com/vueComponent/ant-design-vue/issues/1280)
- 🐞 修复部分组件不能使用 `<template slot="xxx" />` 问题 [041839](https://github.com/vueComponent/ant-design-vue/commit/041839b90131d3a4e6a5663986b811d60d4e6ba2)

## 1.4.2

`2019-10-21`

- 🐞 修复 Radio.Group 触发多次 change 回调问题 [#1280](https://github.com/vueComponent/ant-design-vue/issues/1280)
- 🐞 修复 Pagination 输入框跳转无效问题 [#1316](https://github.com/vueComponent/ant-design-vue/issues/1316)

## 1.4.1

`2019-10-17`

- 🐞 修复 `Input.Password` 无法使用 `v-model` 的问题 [#1306](https://github.com/vueComponent/ant-design-vue/issues/1306)
- 🌟 优化 `Input` 的清除按钮显示逻辑 [#1296](https://github.com/vueComponent/ant-design-vue/issues/1296)
- 🌟 点击清除按钮后 `Input` 变为 `focus` 状态
- 🐞 修复 `Progress` 的 `strokeWidth` 属性失效问题 [#1301](https://github.com/vueComponent/ant-design-vue/issues/1301)
- 🐞 修复 Radio.Group 触发多次 change 回调问题 [#1280](https://github.com/vueComponent/ant-design-vue/issues/1280)
- 🐞 修复 Form initialValue 报错问题 [#1291](https://github.com/vueComponent/ant-design-vue/issues/1291)

## 1.4.0

`2019-10-14`

- 🎉 新的组件 `Empty`，同时优化了各个组件的空数据状态样式！
- 🎉 新增 `Statistic` 统计/倒计时组件。
- 🎉 添加新的国际化资源北印度语（kn_IN）和坎那达语（kn_IN）。
- 🌟 ConfigProvider 组件添加 `prefixCls` 属性。
- Button
  - 🌟 Button 添加圆边形状。
- Collapse
  - 🌟 新增 `expandIcon` 属性，允许用户自定义 Collapse 折叠图标。
- ConfigProvider
  - 🌟 支持 Content Security Policy (CSP) 配置。
  - 🌟 提供 `autoInsertSpaceInButton` 属性以移除按钮中 2 个汉字时字间的空格。
- DatePicker
  - 🌟 将会读取本地化格式配置作为默认日期格式。
- Icon
  - 🌟 Icon 组件添加 `aria-label` 属性以提升无障碍体验。
  - 🌟 新增 `rotate` 属性，允许用户修改图标旋转角度。
  - 🌟 新增 Icon `eye-invisible`。
- Input
  - 🌟 添加 Input.Password 密码输入组件。
  - 🌟 支持 `allowClear`。
- Modal
  - 🌟 添加 `forceRender` 属性。
  - 🌟 添加 `destroyAll` 方法。
  - 🌟 Modal.confirm/info/warning/error 新增 `icon` 属性。原有的 `iconType` 废弃。
- 🌟 Card 组件添加 `small` 类型。
- Form
  - 🌟 添加 `name` 选项到 `Form.create`。
  - 🌟 新增 `selfUpdate` 属性，用于提升表单性能 [#1049](https://github.com/vueComponent/ant-design-vue/issues/1049)
  - 🐞 修复当 `FormItem` 通过 slot 传递时浏览器卡死问题 [#1271](https://github.com/vueComponent/ant-design-vue/issues/1271)
- 🌟 Tree 添加 `switcherIcon` 属性。
- Dropdown
  - 🌟 Dropdown.Button 支持 `href` 属性。
  - 🌟 添加 `openClassName` 属性。
- Table
  - 🌟 添加属性 `sortDirections` 到 Table 和 Table.Column。
  - 🐞 修复 Badge 组件遮盖 Table 固定列的问题。
  - 🐞 修复行选择器列的 `columnWidth` 设置不生效的问题。
- DatePicker
  - 🌟 DatePicker component 添加 `renderFooter` 属性。
  - 🐞 修复 WeekPicker 不支持 `dateRender` 的问题。
  - 🐞 修复禁用按钮在 DatePicker 面板中的样式问题。
  - 🌟 在所有模式中支持 `renderExtraFooter` 属性。
  - 🐞 修复月份选择器在开始年份和结束年份相等时的显示问题。
- TimePicker
  - 🌟 TimePicker 添加新的属性 `popupStyle` 和事件 `amPmChange`。
  - 🐞 修复 TimePicker 在跟 Input.Group 一起使用时图标会消失的问题。
  - 🌟 废弃 `allowEmpty` 属性，改用 `allowClear` 替代。并与 DatePicker 统一样式。
- 🌟 组件 Rate 支持 `tooltips`。
- Upload
  - 💄 添加新的 Less 变量 `upload-picture-card-border-style` 并修复 `upload-picture-card-size` 的拼写错误。
  - 🐞 修复在 Upload 组件中无法识别 `dpg` 后缀文件为图片的问题。
- Modal
  - 🌟 Modal 函数组件新增 `mask` 属性支持。
  - 🌟 Modal 函数组件新增 `transitionName` 和 `maskTransitionName` 属性支持。
  - 🐞 修复鼠标移动到遮罩层自动关闭的问题 [#842](https://github.com/vueComponent/ant-design-vue/issues/842)
- Spin
  - 🐞 修复 Table 在低版本 IE 中 spinning 会遮挡操作的问题。
- Progress
  - 🌟 所有类型都支持 `successPercent` 属性。
- Pagination
  - 🐞 修复省略号不居中的样式问题。
- 🐞 修复 Radio 组件在 Chrome 下的样式问题。
- 🐞 修复 Steps 组件在 IE9 下的样式问题。
- 🐞 修复嵌套的 TimeLine 最后一条线丢失的问题。
- 🐞 修复 Spin 组件初始设置 `delay` 属性后不显示的问题。
- 🐞 修复水波纹在 Edge 下的样式问题。

## 1.3.17

`2019-09-29`

- 🌟 `Form` 新增 `selfUpdate` 属性，用于提升表单性能 [#1049](https://github.com/vueComponent/ant-design-vue/issues/1049)
- `Select`
  - 🐞 修复 keydown 键盘事件失效问题
  - 🐞 修复箭头图标无法关闭弹出框问题 [#1067](https://github.com/vueComponent/ant-design-vue/issues/1176)
  - 🐞 修复 IE 浏览器自动收起问题 [#1223](https://github.com/vueComponent/ant-design-vue/issues/1223)
  - 🌟 添加 maxTagTextLength 属性 [#1217](https://github.com/vueComponent/ant-design-vue/pull/1217)
- 🐞 修复 `TimePicker` 输入时报错的问题 [#1176](https://github.com/vueComponent/ant-design-vue/issues/1176)
- 🐞 修复 `Tooltip` 组件的 `defaultVisible` 属性失效问题 [#1232](https://github.com/vueComponent/ant-design-vue/issues/1232)
- 🐞 修复 `Comment` `ConfigProvider` TypeScript 类型定义问题。

## 1.3.16

`2019-08-25`

- 🐞 修复 `Select` 组件在没有 input 时，卸载组件报错问题 [#1091](https://github.com/vueComponent/ant-design-vue/pull/1091)
- 🐞 修复 `Collapse` 无子元素时报错问题 [#1116](https://github.com/vueComponent/ant-design-vue/pull/1116)
- 🐞 修复 TypeScript 类型定义。

## 1.3.15

`2019-08-17`

- 🐞 修复 `Select` 组件在 IE 下无法滚动问题 [#999](https://github.com/vueComponent/ant-design-vue/issues/999)
- 🐞 修复 `Form` `initialValue` 为空时报 warning 问题 [#1076](https://github.com/vueComponent/ant-design-vue/issues/1076)
- 🐞 修复 `Form` 校验 Number 类型时错误问题 [#1090](https://github.com/vueComponent/ant-design-vue/issues/1090)

## 1.3.14

`2019-08-12`

- 🐞 修复 `MenuItem` 解析数组 `class` 不正确问题 [#1009](https://github.com/vueComponent/ant-design-vue/issues/1009)
- 🐞 修复 npm install 时报错问题 [#997](https://github.com/vueComponent/ant-design-vue/issues/997)
- 🐞 修复 `Select` 组件在 IE 下无法滚动问题 [#999](https://github.com/vueComponent/ant-design-vue/issues/999)
- 🐞 修复 `Select` 组件不触发 focus 事件问题 [#999](https://github.com/vueComponent/ant-design-vue/issues/999)
- 🐞 修复 `DropdownButton` `size` 属性不生效问题 [#71b7c9](https://github.com/vueComponent/ant-design-vue/commit/71b7c9d33895f55694e28aaba4b2cfca7228771b)
- 🐞 修复 `Table` 组件不支持 vue 2.6 v-slot 语法问题 [#1058](https://github.com/vueComponent/ant-design-vue/issues/1058)
- 🌟 `Popover` 添加 `builtinPlacements` 属性 [#1073](https://github.com/vueComponent/ant-design-vue/issues/1073)
- 🌟 `Button` 支持 `link` 类型 [#1077](https://github.com/vueComponent/ant-design-vue/pull/1077)
- 🌟 `Modal.confirm` `title` and `content` 支持 function

## 1.3.13

`2019-07-22`

- 🐞 修复 dist 缺少 antd.less 文件问题 [#995](https://github.com/vueComponent/ant-design-vue/issues/995)

## 1.3.12

`2019-07-22`

- 🐞 `package.json` `files` 添加 `scripts`

## 1.3.11

`2019-07-22`

- Dropdown
  - 🐞 修复 `disable` 时的样式问题 [#912](https://github.com/vueComponent/ant-design-vue/pull/912) [#921](https://github.com/vueComponent/ant-design-vue/pull/921)
  - 🐞 修复 `SubMenu` 闪动问题 [#975](https://github.com/vueComponent/ant-design-vue/issues/970)
- 🌟 `AutoComplete` `Cascader` `DatePicker` `DropDown` `Select` `TimePicker` 添加弹出内容的实例引用 `popupRef` [f9373e](https://github.com/vueComponent/ant-design-vue/commit/f9373e44ce229ab0ba94ababbd686e6ad6e9f10f)
- 🐞 修复 `DatePicker` 在 ie 10 11 下 placeholder 为中文时不能打开的问题 [#865](https://github.com/vueComponent/ant-design-vue/issues/865)
- 🌟 `DatePicker` 添加自定义渲染触发器功能 [#957](https://github.com/vueComponent/ant-design-vue/pull/957)
- 🌟 `@ant-design/icons-vue` 升级为 `^2.0.0`
- 🌟 `Icon` 添加属性 `focusable="false"` [#924](https://github.com/vueComponent/ant-design-vue/issues/924)
- 🐞 修复自定义 `Form` 校验自定义组件时提示 `warning` 问题 [#915](https://github.com/vueComponent/ant-design-vue/issues/915)
- 🐞 修复 `FormItem` `v-decorator` 指令报错问题 [#930](https://github.com/vueComponent/ant-design-vue/issues/930)
- 🐞 修复 `Upload` 组件在 `form.resetFields()` 时报错问题 [#929](https://github.com/vueComponent/ant-design-vue/pull/929)
- 🐞 修复 `Select` 显示跳动问题 [#970](https://github.com/vueComponent/ant-design-vue/issues/970)
- 🐞 修复 TypeScript 类型定义。

## 1.3.10

`2019-06-11`

- 🐞 移除打包后多余的 `module.export` [#850](https://github.com/vueComponent/ant-design-vue/issues/850)

## 1.3.9

`2019-05-26`

- 🐞 修复 `TreeSelect` 没有 `dataRef` 的问题 [#712](https://github.com/vueComponent/ant-design-vue/issues/712)
- 🌟 `Tooltip` 添加 `destroyTooltipOnHide` 用于标识隐藏后是否销毁 tooltip [#727](https://github.com/vueComponent/ant-design-vue/issues/727)
- 🐞 修复 `Avatar` 动态设置 src 时不更新问题 [#731](https://github.com/vueComponent/ant-design-vue/issues/731)
- 🐞 修复 `LocaleProvider` 更改 `moment` 语言不生效问题 [28b7a6](https://github.com/vueComponent/ant-design-vue/commit/28b7a68dc48a0a994e98063d462b99380e3ee547)
- 🌟 `Modal.confirm` 新增 `closable` 配置 [#798](https://github.com/vueComponent/ant-design-vue/pull/798)
- 🐞 修复 `Select` 自定义 `dropdownRender` 时，没能自动关闭的问题 [#644](https://github.com/vueComponent/ant-design-vue/issues/644)
- 🐞 修复在 ie9 下移除 Dom 报错问题，无需单独引入 polyfill [#705](https://github.com/vueComponent/ant-design-vue/issues/705)
- 🐞 修复 `Input.Search` 重复挂载 id 问题 [#726](https://github.com/vueComponent/ant-design-vue/issues/726)
- 🐞 修复 `Table` 使用函数形式自定义 expandIcon 时不生效问题 [#751](https://github.com/vueComponent/ant-design-vue/issues/751)
- 🐞 修复 `Icon` extraCommonProps 属性不生效问题 [#737](https://github.com/vueComponent/ant-design-vue/issues/737)
- 🐞 修复 `DirectoryTree` expandAction="doubleclick" 不生效问题 [#745](https://github.com/vueComponent/ant-design-vue/issues/745)

## 1.3.8

`2019-04-04`

- 🐞 修复 `Table` 在 IE 下不可点击问题 [#504](https://github.com/vueComponent/ant-design-vue/issues/504)
- 🐞 修复 `Table` 在 Firefox 下 Header 没对齐问题 [#579](https://github.com/vueComponent/ant-design-vue/issues/579)
- 🌟 抽屉 `Drawer` 添加自定义 `handel` 功能
- 🐞 修复 TypeScript 类型定义。

## 1.3.7

`2019-03-18`

- 🐞 修复 `Select` `selectedKeys` 类型校验错误 [#597](https://github.com/vueComponent/ant-design-vue/issues/597)

## 1.3.6

`2019-03-17`

- 🐞 修复 `Select` title 属性显示错乱问题 [#588](https://github.com/vueComponent/ant-design-vue/issues/588)
- 🐞 修复 `InputSearch` 不支持 slot 方式自定义 addonAfter 和 addonBefore 问题 [#581](https://github.com/vueComponent/ant-design-vue/issues/581)
- 🐞 修复 `Input` 重复 class 问题 [#faf9ba](https://github.com/vueComponent/ant-design-vue/commit/faf9ba0033eed9ae6ac17879f2e39dd341db847f)
- 🐞 修复 `Message` 通过函数自定义 content 不生效问题 [#554](https://github.com/vueComponent/ant-design-vue/issues/554)
- 🌟 `Cascader` 的 `option.value` 同时支持 `String` `Number` 类型 [#595](https://github.com/vueComponent/ant-design-vue/issues/595)
- 🐞 修复 TypeScript 类型定义。

## 1.3.5

`2019-02-23`

- 🌟 优化 `Popover` `Popconfirm` 组件箭头样式。
- 🐞 修复在 postcss（vue-cli）中使用 autoprefixer 9.4.5 会抛出错误 `Replace text-decoration-skip: ink to text-decoration-skip-ink: auto, because spec had been changed` 的问题。[#471](https://github.com/vueComponent/ant-design-vue/pull/471)
- Tree
  - 🐞 修复 Tree 节点内底部边距叠加的问题。[#502](https://github.com/vueComponent/ant-design-vue/issues/502)
  - 🐞 修复 `Tree` 结点无法拖拽插入目标结点问题。[#469](https://github.com/vueComponent/ant-design-vue/issues/502)
  - 📝 更新文档：`Tree` 组件 `dragxxx` 事件改成全小写。[#467](https://github.com/vueComponent/ant-design-vue/issues/467)
- 🐞 修复 `Modal.confirm` `class` 不生效问题。[#475](https://github.com/vueComponent/ant-design-vue/pull/475)
- 🐞 修复 TypeScript 类型定义。

## 1.3.4

`2019-01-31`

🎉 🎉 🎉 祝大家新年快乐！

- 🐞 修复 AutoComplete 组件 disabled 时，placeholder 不显示的问题。[#402](https://github.com/vueComponent/ant-design-vue/issues/402)。
- 🐞 添加 `BreadcrmbItem` ts 类型文件。[#452](https://github.com/vueComponent/ant-design-vue/issues/452)。
- 🐞 修复当 FormItem 在子组件中时不更新问题。[#446](https://github.com/vueComponent/ant-design-vue/issues/446)。
- 🐞 修复一些组件 TypeScript 定义。

## 1.3.3

`2019-01-26`

- 🐞 修复 message 在配置 maxcount 时，不能关闭提示窗问题。[#428](https://github.com/vueComponent/ant-design-vue/pull/428)。
- 🐞 修复一些组件 TypeScript 定义。[#422](https://github.com/vueComponent/ant-design-vue/pull/422)。
- 🌟 Anchor 组件新增`warpperClass` `wrapperStyle`属性。[1aa42d](https://github.com/vueComponent/ant-design-vue/commit/1aa42dfe18bd7ac7893a765b6ee341844ea02550)
- 📝 更新文档：form 增加 preserve 说明，icon 修改自定义组件引用文档说明。

## 1.3.2

`2019-01-17`

- 🐞 修复 Form 在使用废弃 API `autoCreateForm` 时报错问题。[#413](https://github.com/vueComponent/ant-design-vue/issues/413)。
- 🐞 修复 Slider 点击 mark 时报错问题。[#407](https://github.com/vueComponent/ant-design-vue/issues/407)。

## 1.3.1

`2019-01-15`

- 🐞 修复 Table 组件在 ie 下滚轮失效的问题。[#390](https://github.com/vueComponent/ant-design-vue/issues/390)。
- 🐞 修复 Form 没有清除不在需要校验字段问题。[#367](https://github.com/vueComponent/ant-design-vue/issues/367)。

## 1.3.0

`2019-01-12`

- 🎉 🎉 🎉 发布 vscode 插件 [ant-design-vue-helper](https://marketplace.visualstudio.com/items?itemName=ant-design-vue.vscode-ant-design-vue-helper)
- 🎉 🎉 🎉 优化官网文档交互

  1.3.0 版本带来了两个新组件，还有很多激动人心的变化和新特性。

- 🔥 增加了一个新组件 [Comment](https://www.antdv.com/components/comment-cn/)。
- 🔥 增加了一个新组件 [ConfigProvider](https://www.antdv.com/components/config-provider-cn/) 为组件提供统一的全局化配置。

组件修复/功能增强：

- 🌟 Avatar 组件增加 `srcSet` 属性，用于设置图片类头像响应式资源地址。
- 🌟 Notification 组件增加 `onClick` 属性，点击通知时触发的回调函数。
- Transfer
  - 🌟 增加 `search` 事件，搜索框内容时改变时的回调函数，并废弃 `searchChange` 事件。
  - 🌟 增加 `disabled` 属性，用于禁用搜索框。
- 🌟 Badge 进行了重构，`count` 支持自定义组件。
- Slider
  - 🌟 增加 `tooltipVisible` 属性，用于 Tooltip 是否始终显示。
  - 🌟 优化 focus 效果
  - 🐞 修复键盘 tab 键聚焦时，Tooltip 不显示问题。
  - 🐞 修复拖动时 Tooltip 不停的显隐切换问题。
- Calendar
  - 🌟 支持多种时间格式。
  - 🌟 showSearch 方法增加 `limit` 参数，用于限制搜索结果展示数量。
- Table
  - 🌟 增加 `expandIcon` 属性，用于自定义表格展开图标。
  - 🌟 customCell 方法增加 `index` 参数。
- Select
  - 🌟 增加 `removeIcon`、`clearIcon`、`menuItemSelectedIcon` 属性，用于自定义删除、清空、选中的图标。
  - 🌟 增加 `dropdownRender` 属性， 用于自定义下拉框内容。
  - 🌟 增加 `loading` 属性， 用于展示加载中状态。
- 🌟 优化 Button 在含有 Icon 时的显示效果。
- ⚡️ 重构 Tag 组件，简化代码并提升性能。
- 💄 Menu.Item 组件增加 `title` 属性，用于在收缩时展示的悬浮标题。
- 💄 微调 Card 头部和加载中的样式细节。
- 💄 优化 Spin 样式并略微提升了切换状态的性能。
- 🐞 修复 TextArea 组件高度不能自适应问题。
- 🐞 修复 Tooltip 在 disabled 状态下 Button 中，样式错误问题。[#389](https://github.com/vueComponent/ant-design-vue/issues/389)
- 🐞 修复一些组件 TypeScript 定义。

## 1.2.5

`2019-01-06`

- 🌟 新增`Typescript`类型文件[#250](https://github.com/vueComponent/ant-design-vue/issues/250)
- 🐞 修复`Icon`组件不能同时支持 static class 和 dynamic class 问题[#371](https://github.com/vueComponent/ant-design-vue/issues/371)

## 1.2.4

`2018-12-29`

- 🐞 修复`Select`组件没有触发`popupScroll`事件问题[#350](https://github.com/vueComponent/ant-design-vue/issues/350)
- 🐞 修复自定义`Icon`组件不支持`class` `style`问题。[#351](https://github.com/vueComponent/ant-design-vue/issues/351)
- 🌟 `Tree` `TreeSelect` 支持`number`类型的`key`。[#343](https://github.com/vueComponent/ant-design-vue/issues/343)
- 🌟 `Tree`组件`selectedKeys`、`expandedKeys`支持`.sync`修饰符。[6373ce](https://github.com/vueComponent/ant-design-vue/commit/6373ce8e92a979abb1f5dc94fa9697ee64b08dc2)
- `TreeSelect`
  - 🌟 `treeExpandedKeys`支持`.sync`修饰符。[983318](https://github.com/vueComponent/ant-design-vue/commit/983318b985ad727c008232c75a8598d52d0f924b)
  - 🐞 修复第一次`focus`时触发页面滚动问题。[139356](https://github.com/vueComponent/ant-design-vue/commit/1393563c9b7f8cb7d7ddc0409aa5422c53fca60b)
- 🐞 移除`Menu`组件初始化时的展开动画。[#338](https://github.com/vueComponent/ant-design-vue/issues/338)

## 1.2.3

`2018-12-25`

- 📝 移除圣诞彩蛋。
- 🐞 修复部分组件不支持数组类型`class`问题[#322](https://github.com/vueComponent/ant-design-vue/issues/322)
- 🌟 `TreeSelect` 组件新增 `treeExpandedKeys` 属性和 `treeExpand` 事件，用于控制树的展开收起。
- 🐞 修复`Tree`组件使用`TreeNode`时报重复`Key`问题。

## 1.2.2

`2018-12-19`

- 🐞 修复`Datepicker`渲染两次 footer 问题。[#315](https://github.com/vueComponent/ant-design-vue/issues/315)
- `Menu`
  - 🐞 修复在 `horizontal` 模式下不能自动收起来适应宽度的问题。[aa1b24](https://github.com/vueComponent/ant-design-vue/commit/aa1b2462cb333505d3efc53af1afb30fd0574dc7)。
  - 🐞 修复在 `inline` 模式下首次展开时没有动画的问题。[d63935](https://github.com/vueComponent/ant-design-vue/commit/d63935e50671fab2aa561a013c35af878c610c7c)
  - 🐞 修复`Menu`组件在`collapse=true` `openKeys=[]`时闪动问题。[3393f0](https://github.com/vueComponent/ant-design-vue/commit/3393f0e1513c5d29e2734397bb9e0c0b272c259f)
- 🐞 修复 `Form` 组件在设置`validateStatus`时缺少`Icon`问题。 [#321](https://github.com/vueComponent/ant-design-vue/issues/321)
- 🐞 修复 Upload 缩略图图标样式错误。[f1e130](https://github.com/vueComponent/ant-design-vue/commit/f1e130bdc0c12c625573c08a35c895b2d5d47568)
- 🐞 `Icon` 支持 native event [cffef3](https://github.com/vueComponent/ant-design-vue/commit/cffef392e5605de8d342787d7562e81ca8588800)

## 1.2.1

`2018-12-17`

- 🐞 修复`Menu`在`Layout`下伸缩时闪动问题
- 🐞 修复`Icon`报 Warning 问题

## 1.2.0

`2018-12-16`

- 🔥🔥🔥 使用了 svg 图标替换了原先的 font 图标，从而带来了以下优势：
  - 可以离线化使用，不需要从支付宝 cdn 下载字体文件，图标不会因为网络问题呈现方块，也无需字体文件本地部署。
  - 在低端设备上 svg 有更好的清晰度。
  - 支持多色图标。
  - 对于内建图标的更换可以提供更多 API，而不需要进行样式覆盖。
  - 😓 但同时带来打包文件过大问题，相关解决方案和讨论可以查看 React 版 ant-design [issue](https://github.com/ant-design/ant-design/issues/12011)。
  - 🌟 新增 `theme` 属性，可以设置图标的主题风格。
  - 🌟 新增 `component` 属性，可以外部传入一个组件来自定义控制渲染结果。
  - 🌟 新增 `twoToneColor` 属性，可以控制双色图标的主题色。
  - 🌟 新增静态方法 `Icon.getTowToneColor()` 和 `Icon.setTwoToneColor(...)`，可以全局性的获取和设置所有双色图标的主题色。
  - 🌟 新增静态方法 `Icon.createFromIconfontCN({...})`，可以更加方便地使用 [`iconfont.cn`](http://iconfont.cn/) 上托管的图标。
- 🔥 增加了一个新组件`Skeleton`
- 🔥 Menu 在 `horizontal` 模式下会自动收起来适应宽度。
- 🔥 Drawer 的 `placement` 支持 `top` 和 `bottom`，可以适应更多场景。
- 🌟 以下组件均新增了 `suffixIcon` 属性，用于设置输入框后面的图标，具体用法可以参考文档。
  - Cascader
  - DatePicker
  - Select
  - TreeSelect
  - TimePicker
- 🌟 新增 Modal.open 方法，用于可自定义图标的快捷对话框。
- 🌟 Modal.info 增加 `getContainer` 的配置。
- 🌟 合并优化了 RangePicker 的日历页脚 UI。
- 🌟 Anchor 组件增加 `click` 事件。
- 🌟 Tab 组件增加 `renderTabBar` 属性。
- 🌟 Input 组件增加 `select` 方法。
- 🌟 Steps 增加 `initial` 属性。
- 🌟 Upload 组件新增 `openFileDialogOnClick` 属性，用于设置点击组件时是否打开上传对话框。
- 🌟 InputNumber 组件新增 `decimalSeparator` 属性，用于设置自定义的小数点。
- 🐞 修复众多隐蔽暂未提 issue 的 bug，再此不在一一列出

## 1.1.10

`2018-12-7`

- 🔥🔥🔥 在 1.1.10 版本中`Form`组件更好地支持单文件 tempalte 语法，在以往版本中，对于复杂的组件需求，需要使用 JSX 才可以实现。为了更好地在 template 中使用 Form 表单的自动收集校验功能，我们优化了组件的使用方式。文档全部 Demo 使用最新语法重构。不过对于以往 API，还是继续支持，你可以不用担心 API 的改变，导致已有系统出现问题。

```html
<template>
  <a-form :form="form">
    <a-form-item>
      <a-input v-decorator="[id, options]">
    </a-form-item>
  </a-form>
</template>
<script>
export default {
  beforeCreate () {
    this.form = this.$form.createForm(this, options)
  },
}
</script>
```

- 🐞 修复`Steps`组件`labelPlacement`不生效问题 [#281](https://github.com/vueComponent/ant-design-vue/issues/281)
- 🐞 修复`Timeline`组件样式问题，添加`reverse` `mode`属性 [#8e37cd](https://github.com/vueComponent/ant-design-vue/commit/8e37cd89f92ee2541f641fd860785cfd2361b2b3)
- `Tree`
  - 🐞 修复`treeDefaultExpandedKeys`不生效问题 [#284](https://github.com/vueComponent/ant-design-vue/issues/284)
  - 🐞 修复`expandedKeys` `selectedKeys`等其它数组属性通过组件变异方法改变时组件不更新问题 [#239](https://github.com/vueComponent/ant-design-vue/issues/239)

## 1.1.9

`2018-11-26`

- 🐞 修复`TreeSelect`组件 getPopupContainer 不生效问题 [#265](https://github.com/vueComponent/ant-design-vue/issues/265)
- 🐞 修复`Carousel`组件按需加载不生效问题 [#271](https://github.com/vueComponent/ant-design-vue/issues/271)
- 🐞 修复`Upload`组件 remove 事件无返回值问题 [#259](https://github.com/vueComponent/ant-design-vue/issues/259)

## 1.1.8

`2018-11-11`

- `Progress`
  - 🐞 修复 circle 类型不支持 strokeColor 问题 [#238](https://github.com/vueComponent/ant-design-vue/issues/238)
  - 🐞 添加`normal`类型 [#257](https://github.com/vueComponent/ant-design-vue/issues/257)
- 🐞 修复`Cascader`组件 getPopupContainer 不生效问题 [#257](https://github.com/vueComponent/ant-design-vue/issues/257)
- 🌟 `Tooltip`支持 align [#252](https://github.com/vueComponent/ant-design-vue/issues/252)

## 1.1.7

`2018-10-27`

- 🐞 修复`Cascader`组件类型错误问题 [#219](https://github.com/vueComponent/ant-design-vue/issues/219)
- 🐞 修复`Tree`组件自定义 Icon 时回调参数顺序错误问题 [#223](https://github.com/vueComponent/ant-design-vue/issues/223)
- 🐞 修复`Table`组件多次触发翻页回调问题 [#228](https://github.com/vueComponent/ant-design-vue/issues/228)
- 🌟 优化`Tabs`组件新增 tab 默认滚动到可视区域 [#215](https://github.com/vueComponent/ant-design-vue/issues/215)
- 🐞 修复`RadioGroup`组件不支持数字 0 问题 [#226](https://github.com/vueComponent/ant-design-vue/issues/226)
- 🐞 修复`Slider`组件当设置 zoom 不为 1 时，位置错误问题，部分浏览器需要 visualViewport Polyfill [#227](https://github.com/vueComponent/ant-design-vue/issues/227)

## 1.1.6

`2018-10-10`

- 🐞 修复`Select`组件键盘事件报错问题 [#217](https://github.com/vueComponent/ant-design-vue/issues/217)
- 🐞 修复`Drawer`组件 children 更新问题 [#209](https://github.com/vueComponent/ant-design-vue/issues/209)

## 1.1.4

`2018-09-29`

- 🛠 重构`vc-tree`组件，并新增目录树组件
- 🐞 修复`tabs`组件属性`tabBarGutter`不生效问题 [#205](https://github.com/vueComponent/ant-design-vue/issues/205)
- 🐞 修复`table`组件数据同步出错问题 [#202](https://github.com/vueComponent/ant-design-vue/issues/202)

## 1.1.3

`2018-09-22`

- 🎉 优化组件注册方式，如 Vue.use(Form) [a6620c](https://github.com/vueComponent/ant-design-vue/commit/a6620cbbe58cc1694a994e6714853906d1d794be)
- 🐞 `Select.Option` 组件`value`属性支持`0` [#194](https://github.com/vueComponent/ant-design-vue/issues/194)
- 🐞 修复 `Layout.Sider` 折叠按钮宽度不生效问题 [#201](https://github.com/vueComponent/ant-design-vue/issues/201)
- 🐞 修复 `Menu` 切换 inlineCollapsed 时，纵向无动画问题 [#200](https://github.com/vueComponent/ant-design-vue/issues/200)
- 🐞 修复 `Steps` `dot`模式下样式问题 [#199](https://github.com/vueComponent/ant-design-vue/issues/199)

## 1.1.2

`2018-09-17`

- 🎉 同步 antd3.8.4 样式
- 🌟 Tag 组件新增`visible`属性及 wave 效果
- 🐞 修复`Cascader`组件，已选中项未展开问题 [#195](https://github.com/vueComponent/ant-design-vue/issues/195)

## 1.1.1

`2018-09-13`

- 🐞 修复窗口大小改变导致弹窗位置错位问题 [#184](https://github.com/vueComponent/ant-design-vue/issues/184)
- 🐞 tabs 容器添加自定义事件监听 [#189](https://github.com/vueComponent/ant-design-vue/issues/189)
- 🐞 修复通过 API 形式调用 Modal 窗口时，`centered`不生效问题 [#183](https://github.com/vueComponent/ant-design-vue/issues/183)
- 🐞 Slider marks 支持{number: function}形式 [#171](https://github.com/vueComponent/ant-design-vue/issues/171)

## 1.1.0

`2018-09-11`

- 🎉 从[3.4.0](https://github.com/ant-design/ant-design/releases/tag/3.4.0)同步组件到 antd [3.8.2](https://github.com/ant-design/ant-design/releases/tag/3.8.2)
- 🌟 新增`Drawer 抽屉`组件
- 🐞 修复`Spin`内容闪烁问题 [#174](https://github.com/vueComponent/ant-design-vue/issues/174)
- 🐞 修复`RangePicker`选择项未禁用问题 [#158](https://github.com/vueComponent/ant-design-vue/issues/158)
- 🐞 修复`Form`值为 `null`时报错问题 [#153](https://github.com/vueComponent/ant-design-vue/issues/153)
- 🐞 修复`Modal`子组件重复`mounted`问题 [#152](https://github.com/vueComponent/ant-design-vue/issues/152)
- 🐞 修复`Transfer`搜索过滤后不能正确显示问题 [#148](https://github.com/vueComponent/ant-design-vue/issues/148)
- 🐞 修复多级`Tabs`组件嵌套导致`size`不生效问题 [#144](https://github.com/vueComponent/ant-design-vue/issues/144)
- 🐞 修复`TreeSelect`searchPlaceholder 不生效 [#125](https://github.com/vueComponent/ant-design-vue/issues/125)
- 🛠 其它未出现在 issue 中的问题，详见 antd changelog

## 1.0.3

`2018-08-11`

- 🐞 修复`Select`子元素不更新问题 [#106](https://github.com/vueComponent/ant-design-vue/issues/106)
- 🐞 修复`Badge` offset 属性 X Y 轴顺序错误问题，并新增支持 number 类型 [#99](https://github.com/vueComponent/ant-design-vue/issues/99)
- 🐞 修复`Input`在 ie 下中文 placeholder 触发 input 事件问题 [#92](https://github.com/vueComponent/ant-design-vue/issues/92)
- 🐞 修复`Avatar`不接受事件问题 [#102](https://github.com/vueComponent/ant-design-vue/issues/102)
- 🐞 修复`grid.row`gutter 类型错误问题 [4af03c4](https://github.com/vueComponent/ant-design-vue/commit/4af03c4ab9596ede9d1b79c8308d0a3ed58b7a11)
- 🐞 修复`CheckboxGroup`在`Form`中报 defaultValue warning 问题 [#110](https://github.com/vueComponent/ant-design-vue/issues/110)

## 1.0.2

`2018-08-04`

- 🎉 修改组件库名称为`ant-design-vue`
- 🌟 官方站点支持 IE9 访问[a8a5f8](https://github.com/vueComponent/ant-design-vue/commit/a8a5f854c3b6a78df526caf2fb391e5c9d0848ac)
- 🐞 修复导出未定义变量引起的提醒问题[#87](https://github.com/vueComponent/ant-design-vue/issues/87)
- 🐞 修复部分组件类名重复问题[b48bbac](https://github.com/vueComponent/ant-design-vue/commit/b48bbac695dabec9160d947f9b27b2d91028c455)
- 🐞 修复`Select`组件 label 不更新问题[da1b924](https://github.com/vueComponent/ant-design-vue/commit/da1b924cba0fcc871b73590ac3ebd96af81b3897)
- 🛠 更正了若干文档错误

## 1.0.1

`2018-07-27`

- 🌟 针对`Input`组件优化中文输入(仅在 v-model 绑定时生效) [4a5154](https://github.com/vueComponent/ant-design-vue/commit/4a51544bd6470ab628dda80e9d7593e4603dd0b6)
- 🐞 修复`TreeSelect` `treeeData[i].children`为`null`时报错问题[#81](https://github.com/vueComponent/ant-design-vue/issues/81)
- 🐞 修复`Calendar`组件的 change 事件触发两次的问题[#82](https://github.com/vueComponent/ant-design-vue/issues/82)
- 🐞 修复`Card`组件的`description`和`title`属性 slot 不生效问题[#83](https://github.com/vueComponent/ant-design-vue/issues/83)
- 🐞 修复`DataPicker`组件的`dropdownClassName`属性不生效问题[02ab242](https://github.com/vueComponent/ant-design-vue/commit/02ab242197b923f2157f41d98a7930512475a799)

## 1.0.0

`2018-07-21`

- 🌟 新增`Carousel 走马灯`组件[edddbd](https://github.com/vueComponent/ant-design-vue/commit/edddbd982a279b62229ce825855c14c556866ece)
- 更正了若干文档错误

## 0.7.1

`2018-07-17`

- 🐞 修复`Tooltip`包含`Button`时的样式及功能问题[#73](https://github.com/vueComponent/ant-design-vue/issues/73)
- 🐞 add `Table` panagation deep watch[#b464c6](https://github.com/vueComponent/ant-design-vue/commit/b464c6f6ee4df6df1b6c55f29ac85b2f462763bc)

## 0.7.0

`2018-07-11`

- 🌟 新增`TreeSelect`组件
- 🌟 `Select`组件新增`options`，方便直接生成选择列表[#37](https://github.com/vueComponent/ant-design-vue/issues/37)
- 🐞 修复`Tooltip`中使用`Select`组件时，`blur`事件报错问题[#67](https://github.com/vueComponent/ant-design-vue/issues/67)
- 🐞 修改`Upload`组件`action`属性为可选[#66](https://github.com/vueComponent/ant-design-vue/issues/66)

## 0.6.8

`2018-07-05`

- 🐞 修复`notification` h is not defined[#63](https://github.com/vueComponent/ant-design-vue/issues/63)
- 🐞 修复`Transfer`国际化缺少 titles 问题[#64](https://github.com/vueComponent/ant-design-vue/issues/64)

## 0.6.7

`2018-07-03`

- 🐞 修复`Form`使用模板语法时组件不能更新[#62](https://github.com/vueComponent/ant-design-vue/issues/62)

## 0.6.6

`2018-07-03`

- 🐞 修复`Upload`的类型校验错误问题并更新相关 demo[#61](https://github.com/vueComponent/ant-design-vue/issues/61)
- 🐞 修复`Upload`图片预览不能正确跳转问题[1584b3](https://github.com/vueComponent/ant-design-vue/commit/1584b3839e500d2d6b07abf704f5cd084ca00e87)

## 0.6.5

`2018-07-01`

- 🐞 修复`Select`的`getPopupContainer`不生效问题[#56](https://github.com/vueComponent/ant-design-vue/issues/56)
- 🐞 修复`Select`的弹出框位置不更新问题[8254f7](https://github.com/vueComponent/ant-design-vue/commit/8254f783a32189b63ffcf2c53702b50afef1f3db)

## 0.6.4

`2018-06-28`

- 🐞 修复`InputSearch`的`v-model`返回值错误问题[#53](https://github.com/vueComponent/ant-design-vue/issues/53)

## 0.6.3

`2018-06-26`

- 🐞 修复`Popover`的`v-model`不生效问题[#49](https://github.com/vueComponent/ant-design-vue/issues/49)

## 0.6.2

`2018-06-24`

- 🌟 `Form`组件数据自动校验功能支持`template`语法[7c9232](https://github.com/vueComponent/ant-design-vue/commit/7c923278b3678a822ff90da0cb8db7653d79e15c)
- `Select`: 🐞 添加`focus` `blur`方法[52f6f5](https://github.com/vueComponent/ant-design-vue/commit/52f6f50dbe38631c0e698a6ea23b3686f6c2a375)
- `Radio`
  - 🐞 修复 Radiogroup `disabled` className[9df74b](https://github.com/vueComponent/ant-design-vue/commit/9df74bedd7640b6066010c498f942ce544c658b7)
  - 🐞 修复`autoFoucs` `focus` `blur` `mouseenter` `mouseleave` 不生效问题[f7886c](https://github.com/vueComponent/ant-design-vue/commit/f7886c7203730bedf519bc45f5f78726735d3aac)
- `TimePicker`: 🐞 修复`autoFoucs` `focus` `blur`不生效问题[28d009](https://github.com/vueComponent/ant-design-vue/commit/28d009d3ced807051a86a2c09cd2764303de98f7)

## 0.6.1

`2018-06-17`

- 🌟 新增`List`列表组件
- `Table`
  - 🐞 修复更新高度时报错问题[#33](https://github.com/vueComponent/ant-design-vue/issues/33)
  - 🐞 修复`defaultChecked`不生效问题[ec1999](https://github.com/vueComponent/ant-design-vue/commit/ec1999dea4cea126b78e3fd84bef620b876e9841)
  - `columns key`支持数字类型[9b7f5c](https://github.com/vueComponent/ant-design-vue/commit/9b7f5c2f81b6f83190e5b022b2b1e28de3f68a2b)
- `Tooltip`
  - 🛠 更新事件 API`change`为`visibleChange`
- `Textarea`: 🐞 修复`autoFoucs`不生效问题[787927](https://github.com/vueComponent/ant-design-vue/commit/787927912307db7edb9821a440feacd216e3a6a2)
- `InputSearch`: 🐞 添加`focus` `blur`方法[3cff62](https://github.com/vueComponent/ant-design-vue/commit/3cff62997d16811ae17618f9b41617973d805d7d)
- `InputNumber`: 🐞 修复`autoFoucs`不生效问题[88f165](https://github.com/vueComponent/ant-design-vue/commit/88f165edb5c3993f4dba90c3267a1ea037e0869b)
- `DatePicker`: 🐞 修复`autoFoucs`不生效问题[264abf](https://github.com/vueComponent/ant-design-vue/commit/264abff59791181b9190ca0914b780a8df6aa81a)
- `Cascader`: 🐞 修复`autoFoucs`不生效问题[be69bd](https://github.com/vueComponent/ant-design-vue/commit/be69bd9af1bae184a4ebe8c4ef9560479ab11027)
- `Rate`: 🐞 修复`autoFoucs`不生效问题，及`blur`报错问题[c2c984](https://github.com/vueComponent/ant-design-vue/commit/c2c9841eb9b8e5ce4decff57a925e60d4bd7d809)
- `RangePicker`: 🐞 修复值类型校验出错问题[228f44](https://github.com/vueComponent/ant-design-vue/commit/228f4478a5d169d22960c97d1d8a8320c58da9cc)

## 0.6.0

`2018-06-04`

- 🌟 新增`Anchor`锚点组件
- `Table`
  - 🐞 修复`loading.spinning`时显示`emptyText`问题[17b9dc](https://github.com/vueComponent/ant-design-vue/commit/17b9dc14f5225eb75542facdb5053f4916b9d77f)
  - 🐞 修复`header style`不生效问题[#30](https://github.com/vueComponent/ant-design-vue/pull/30)
- `DatePicker`: 🐞 修复属性`showTime`为`true`时，重复调用`change`事件问题[81ab82](https://github.com/vueComponent/ant-design-vue/commit/81ab829b1d0f67ee926b106de788fc5b41ec4f9c)
- `InputNumber`: 🐞 修复`placeholder`不生效问题[ce39dc](https://github.com/vueComponent/ant-design-vue/commit/ce39dc3506474a4b31632e03c38b518cf4060cef#diff-c9d10303f22c684e66d71ab1f9dac5f9R50)

## 0.5.4

`2018-05-26`

- 🐞 修复 dist 目录缺少 less 文件问题[ca084b9](https://github.com/vueComponent/ant-design-vue/commit/ca084b9e6f0958c25a8278454c864ac8127cce95)

## 0.5.3

`2018-05-25`

- 🐞 修复构建`antd-with-locales.js`包含测试文件的问题[90583a3](https://github.com/vueComponent/ant-design-vue/commit/90583a3c42e8b520747d6f6ac10cfd718d447030)

## 0.5.2

`2018-05-25`

- 🐞 `Timeline`: 修复重复显示 loading 组件 bug[fa5141b](https://github.com/vueComponent/ant-design-vue/commit/fa5141bd0061385f251b9026a07066677426b319)
- `Transfer`
  - 🐞 修复搜索框的清除按钮不起作用问题[4582da3](https://github.com/vueComponent/ant-design-vue/commit/4582da3725e65c47a542f164532ab75a5618c265)
  - 💄 重写了属性变化监听逻辑，避免不必要的[0920d23](https://github.com/vueComponent/ant-design-vue/commit/0920d23f12f6c133f667cd65316f1f0e6af27a33)
- 💄 `Select`: 优化`title`显示逻辑[9314957](https://github.com/vueComponent/ant-design-vue/commit/931495768f8b573d12ce4e058e853c875f22bcd3)
- `Form`
  - 🐞 修复 Form 组件指令报错问题[#20](https://github.com/vueComponent/ant-design-vue/issues/20)
  - 🌟 优化获取 Form 包装组件实例功能[c5e421c](https://github.com/vueComponent/ant-design-vue/commit/c5e421cdb2768e93288ce7b4654bee2114f8e5ba)
- 🐞 `DatePicker`: 修复日历键盘事件不起作用问题[e9b6914](https://github.com/vueComponent/ant-design-vue/commit/e9b6914282b1ac8d84b4262b8a6b33aa4e515831)
- `Avatar`: 修复字体大小自适应问题[#22](https://github.com/vueComponent/ant-design-vue/pull/22)
- 🌟 添加了部分组件的单测
- 🌟 整理了组件库依赖(dependencies、devDependencies)，删除不再使用的包，并添加 peerDependencies

## 0.5.1

`2018-05-10`

- 🐞 `Table`: 修复 `customRow` 自定义事件不生效问题[#16](https://github.com/vueComponent/ant-design-vue/issues/16)

## 0.5.0

`2018-05-08`

- 🌟 `Form`新增 Form 表单组件
- 💄 `Upload.Dragger`: 修改组件 name 名称为`a-upload-dragger`
- 🐞 `Upload`: 修复 Upload name 属性失效问题

## 0.4.3

`2018-05-02`

- 🐞 修复组件样式丢失问题
- 🌟 站点添加 babel-polyfill

## 0.4.2

`2018-04-24`

- 🐞 修复 menu 非 inline 模式下的 click bug

## 0.4.1

#### bug

- 将 Vue 依赖转移到 devDependencies，避免与业务版本不一致导致的不稳定 bug

## 0.4.0

#### Layout

- 新增 Layout 组件

#### 其它

- 支持导入所有组件[Vue.use(antd)](https://github.com/vueComponent/ant-design-vue/issues/3)

## 0.3.1

#### Features

- 对外第一个版本，提供常用 45 个[组件](https://github.com/vueComponent/ant-design-vue/blob/c7e83d6142f0c5e72ef8fe794620478e69a50a8e/site/components.js)
