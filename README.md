# 任务简介：

在这个 code test 中，希望大家利用 ant design 制作一个简单的组件。同时调用

## 主要任务：

- 在 `pages/index.js` 中，用表格的方式展示 `sample-data.json` 中的数据
- 除了 `id` field 之外，展示 `sample-data.json` 中的所有数据
- 在表格中添加一个 `Actions` 列，`Actions` 列展示一个文字为 `Delete` 的按钮
- 用户点击按钮之后弹出 confirm 提示，提供 yes / no 的选项供用户选择。
- 不需要调用任何 API，只需在用户点击 yes 后在 console 中打印出相关信息（如该订单的 id）就行
- 不需要任何的额外 style
- bonus：将点击了删除，并点击 yes 确定后，将该行从表格中移除

## Tips:

- 已经在 package.json 中添加了 ant desgin，并引入了 ant design 的相关 css，可以直接调用。
- 可以用不同文件夹如 `components` 整理不同的文件。
- 在 ant design `Table` 组件的 [columns API](https://ant.design/components/table/#Column) 中，可以通过 `render` API 在单元格内渲染自定义的组件。

## 参考文档：

- [next.js](https://nextjs.org/)
- [Ant Design](https://ant.design/)
- 可能用到的 ant design 组件：
- [Table](https://ant.design/components/table/)
- [Popconfirm](https://ant.design/components/popconfirm)
- [Button](https://ant.design/docs/spec/buttons#header)

## 提交方式：

- 你可以 clone 本 repo，然后将你的代码保存到 github 并把 repo 地址发送给我们 hello@wohu.studio
- 你可以 fork 本 repo，然后通过 Pull Request 的方式提交到本 repo
