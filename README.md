# 基于Gin、Gorm、Vue 实现的在线练习系统


接口访问地址：http://localhost:8080/swagger/index.html
```text
// GetProblemList
// @Tags 公共方法
// @Summary 问题列表
// @Param page query int false "page"
// @Param size query int false "size"
// @Success 200 {string} json "{"code":"200","msg","","data":""}"
// @Router /problem-list [get]
```


## 系统模块
- [x] 用户模块
  - [x] 密码登录
  - [x] 邮箱注册
  - [x] 用户详情
- [x] 题目管理模块
  - [x] 题目列表、题目详情
  - [x] 题目创建、题目修改
- [x] 分类管理模块
  - [x] 分类列表
  - [x] 分类创建、分类修改、分类删除
- [x] 判题模块
  - [x] 提交记录列表
  - [x] 代码的提交及判断
- [x] 排名模块
  - [x] 排名的列表情况
