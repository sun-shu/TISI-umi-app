#### 项目流程

- 全局环境

> node版本 >= 18.19.1
>
> 全局安装 umi pnpm
>
>

- clone项目

> [项目地址](111.33.127.102:8090/tisihcsp/PROD01-TISIHCSP-EVA-MCS)

- 切换分支

> git checkout main

- 构建依赖

> pnpm install

- 项目运行

> pnpm dev
>
>
>
> store文件夹使用的是zustand
> models文件夹使用的是umi的useModel
> useModel的实现原理是上层注入方式，所以在一开始就会加载
> zustand是在组件内部使用的，所以只有在组件内部使用的时候才会加载

> TODO:

- 接口一键mock
- 401路由跳转登录页 √
- 接口interface拆分到单独文件 √
- 综合评估是否有下一项计算 √
-
    - 时间题 √
- 单项评估的评估结果展示 √
- 查看表单的回显 √
- 表单必填项校验提示 √
- 列表页增加空数据兼容 √
-
    - 模板列表页筛选 √
-
    - 骨架屏展示√
- 综合评估名称展示√
-
- 从长者入口进入填写评估 逻辑捋顺
- 表格题√
    - 是不是一定要传那两个字段
    - 如何回显
- 进度条吸顶 √
- 综合评估名称展示 √
- 时间题 回显字符串 √
- 根据性别展示头像 √
- 404页面新增
- 长者列表页筛选 （复杂 √
- 长者详情头像兜底方案
- 整理缺失的字段
- 评估参数整理，现在太乱了
- 下拉加载 （复杂 √
- LOGO替换
- 进度条吸顶 √
- 综合评估名称展示 √
- 时间题 回显字符串 √
- 跳题逻辑 （复杂
- 综合评估查看 √
- 根据性别展示头像√
- 表格必填项判断√
- 添加时上一次填写数据的回显（复杂 √
- 筛选最小 √
