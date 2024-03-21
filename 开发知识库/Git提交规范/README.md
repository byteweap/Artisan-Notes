# 🙄 代码提交规范

代码提交规范化, 使得整个项目的提交历史看起来更加清晰、一致，易于阅读和理解. 可以更轻松地搜索和定位特定功能、Bug修复或其他变更的历史记录. 可以帮助团队成员更好地理解彼此的工作，从而更容易进行代码审查、合并和维护. 该规范本人参阅资料自行整理，如果你有更好的想法, 欢迎探讨, 共同改进.

### 1. 模版

​`注意： ✅：必填项`​

```undefined
<type><emoji>[<scope>]: <subject>

<body>

<footer>
```

* type: 提交类型.(必填) ✅
* emoji: emoji表情. (选填)
* scope: 提交影响范围,如 router, api, model, service等. (选填)
* subject: 提交的描述内容. (必填)✅
* body: 具体修改内容, 可以分为多行. (选填)
* footer: 一些备注, 通常是 BREAKING CHANGE 或修复的 bug 的链接. (选填)

### 2. 对照表

该表中列举的 emoji 表情主要为了参考, 并非强制与type对应, 可根据实际情况进行选择合适的emoji, 更多emoji请参考: [gitmoji.dev](https://gitmoji.dev)

|   type   |        说明        |      参考emoji      |                              参考emoj代码                             |
| :------: | :--------------: | :---------------: | :---------------------------------------------------------------: |
|   feat   |      新功能、新特性     |         ✨         |                <p>​<code>:sparkles:</code>​<br></p>               |
|    fix   |       修复bug      |         🐛        |                  <p>​<code>:bug:</code>​<br></p>                  |
|   perf   |     优化代码，提高性能    |         ⚡         |                  <p>​<code>:zap:</code>​<br></p>                  |
| refactor |    代码重构 / 重大重构   |    🎨 / 🔨 / ♻️   |               ​`:art:`​ / `:hammer:`​ / `:recycle:`​              |
|   docs   |       文档修改       |         📝        |                             ​`:memo:`​                            |
|   style  |      代码格式修改      |         🌻        |                            ​`:flower:`​                           |
|   test   |     测试用例新增、修改    | <p>✅ / 🧪<br></p> |                 ​`:white_check_mark:`​ / `:test:`​                |
|   build  |    影响项目构建或依赖修改   |      ⬇️ / ⬆️      | <p>​<code>:arrow_down:</code>​ / <code>:arrow_up:</code>​<br></p> |
|  revert  |      恢复上一次提交     |         ⏪         |                            ​`:rewind:`​                           |
|    ci    |    持续集成相关文件修改    |   <p>👷<br></p>   |                     ​`:construction_worker:`​                     |
|  release |       发布版本       |         🔖        |                <p>​<code>:bookmark:</code>​<br></p>               |
|   chore  | 其它修改(不再上述类型中的修改) |                   |                                                                   |
| workflow |       工作流相关      |                   |                                                                   |

### 3. 示例

* feat✨: 添加jwt鉴权功能
* fix🐛: 修复新增用户异常Bug
* test✅: 新增xorm ping测试用例
* docs: 新增系统管理文档
* ...

通常情况下，应尽量避免单次提交极为复杂的业务逻辑, 应保持提交精细化, 故body、footer使用频率极低. 示例第1、2、3为推荐格式，加入emoji表情更美观, 如果可以请保持代码及其它看起来简单清爽又漂亮. 🌻

‍
