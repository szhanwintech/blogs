# 极光低版本适配之后无法 run 的解决方案

> ### 报错提示：

```
packageDebug：faild
Error:Execution failed for task ':app:packageDebug'. > !zip.isFile()
```

<br />

> ### 原因

        android的build文件夹冲突，（修改后生成的build和原先存在的build起冲突）

<br />

> ### 解决方案

         在 ionic 项目中的 platform/androd 删除 build 文件夹

         重新 run 即可
