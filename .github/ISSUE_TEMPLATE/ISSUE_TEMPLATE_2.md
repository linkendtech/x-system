---
name: 详情页面需求模板
about: 详情页面需求模板
---
xx页面功能列表

数据展示区域
---
- 展示数据

顶部操作区域
---
- 点击`返回上一页`返回`[客户管理] - 客户列表页面`

特殊操作区域
---

数据操作区域
---
- 点击`编辑`按钮, 弹出数据编辑panel
- 点击`删除`按钮, 弹出确认modal
  - 点击`取消`关闭modal
  - 点击空白区域关闭modal
  - 点击`确认`, 删除该条数据, 并返回`[客户管理] - 客户列表页面`

数据编辑panel
---
- 点击空白区域关闭panel
- 点击`取消`按钮关闭panel
- 点击`确认`按钮进行表单验证
  - 表单验证成功 - 更新该数据
  - 表单验证失败 - 展示报错信息

