# PLMCodeTemplate
给部门制定的代码框架模板

## 编程规范
1. 所有的接口返回ResultBean，并且ResultBean只允许出现在Controller
2. 

## 接口规范
1. 所有接口都必须返回ResultBean，就是说一开始就考虑好成功和失败的场景。
2. ResultBean只允许出现在controller，不允许到处传。
3. 对外接口可以考虑使用细分错误码，对内接口使用异常信息即可

## 日志打印规范
1. 关键参数必须打印日志
2. 对一个集合处理的时候必须打印处理的数据量
3. 可能耗时长的函数需要在前后打印日志以方便收集耗时
4. 