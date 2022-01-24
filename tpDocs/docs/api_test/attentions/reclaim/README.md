# 数据认领
- 项目管理 -> 待分配项目
  - 此部分为YAPI拉取数据后初始状态，各测试组需领取自己部门所关联的项目。
- 接口关联 -> 待分配的接口
  - 此部分多数为xmind导入的接口，无 项目->分组信息，需手动修改添加
  - 后期会做YAPI同步查询对应项目->分组信息，但是部分YAPI不存在的接口仍需手动处理
- 用例管理 -> 待分配用例集：需手动编辑指定用例集所属部门

::: warning 注意
1. 无部门、项目、分组的接口，新增测试步骤时无法查询到（级联查询+懒加载，需要逐级查询）
2. 无部门信息的用例集，执行后报告中显示会不在部门树下
:::