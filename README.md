# husky

规范建设-可以放置错误的 git commit，git push

- 中文文档：[Husky](https://www.breword.com/typicode-husky)
- 英文文档：[Husky](https://typicode.github.io/husky/#/)
- 详细配置可参考：https://juejin.cn/post/7038143752036155428#heading-8

## git commit 指南

```bash
<类型>[可选 范围]: <描述>
```

**commit 类型**

- feat: 新增特性或功能
- fix: 修复问题
- docs: 修改文档
- style: 修改代码格式
- refactor: 代码重构，不引入新功能和修复问题
- perf: 性能优化
- test: 新增、修改测试用例
- chore: 构建过程或者辅助工具的变动
- merge: 代码合并
- build: 主要目的是修改项目构建系统(例如 glup，webpack，rollup 的配置等)的提交
- test: 增加测试
- merge: 分支合并 Merge branch ? into ?
- revert: 回滚某个更早之前的提交
- sync: 同步主线或分支的 Bug
- ci: 与 CI(持续集成服务)有关的改动
