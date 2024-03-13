
| en                                                                                                                             | zh-CN                                                     |
| ------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------- |
| General Settings                                                                                                               | 常规设置                                                      |
| Enable Inline Queries                                                                                                          | 启用内联查询                                                    |
| Enable or disable executing regular inline Dataview queries                                                                    | 启用或禁用执行常规内联 Dataview 查询                                   |
| Enable JavaScript Queries                                                                                                      | 启用 JavaScript 查询                                          |
| Enable or disable executing DataviewJS queries                                                                                 | 启用或禁用执行 DataviewJS 查询                                     |
| Enable Inline JavaScript Queries                                                                                               | 启用内联 JavaScript 查询                                        |
| Enable or disable executing inline DataviewJS queries. Requires that DataviewJS queries are enabled.                           | 启用或禁用执行内联 DataviewJS 查询。要求启用 DataviewJS 查询                |
| Enable Inline Field Highlighting in Reading View                                                                               | 在阅读视图中启用内联字段突出显示                                          |
| Enables or disables visual highlighting / pretty rendering for inline fields in Reading View                                   | 启用或禁用阅读视图中内联字段的视觉高亮显示/美化渲染                                |
| Enable Inline Field Highlighting in Live Preview                                                                               | 在实时预览中启用内联字段突出显示                                          |
| Enables or disables visual highlighting / pretty rendering for inline fields in Live Preview                                   | 启用或禁用实时预览中内联字段的视觉高亮显示/美化渲染                                |
| Codeblock Settings                                                                                                             | 代码块设置                                                     |
| DataviewJS Keyword                                                                                                             | DataviewJS 关键字                                            |
| Keyword for DataviewJS blocks. Defaults to 'dataviewjs'. Reload required for changes to take effect                            | DataviewJS 块的关键字。默认为 dataviewjs 。需要重新加载才能使更改生效            |
| Inline Query Prefix                                                                                                            | 内联查询前缀                                                    |
| The prefix to inline queries (to mark them as Dataview queries). Defaults to '='.                                              | 内联查询的前缀(用于将其标记为 Dataview 查询)。默认为 '='。                     |
| JavaScript Inline Query Prefix                                                                                                 | JavaScript 内联查询前缀                                         |
| The prefix to JavaScript inline queries (to mark them as DataviewJS queries). Defaults to '$='.                                | JavaScript 内联查询的前缀(将它们标记为 DataviewJS 查询)。默认值为 '$='。       |
| Codeblock Inline Queries                                                                                                       | 代码块内联查询                                                   |
| If enabled, inline queries will also be evaluated inside full codeblocks.                                                      | 如果启用，内联查询也将在完整的代码块中进行评估                                   |
| View Settings                                                                                                                  | 视图设置                                                      |
| General                                                                                                                        | 常规                                                        |
| Display result count                                                                                                           | 显示结果计数                                                    |
| If toggled off, the small number in the result header of TASK and TABLE Queries will be hidden.                                | 如果关闭，则 TASK 和 TABLE 查询的结果标头中的小数字将被隐藏                      |
| Warn on Empty Result                                                                                                           | 对空结果发出警告                                                  |
| If set, queries which return 0 results will render a warning message                                                           | 如果设置，返回 0 结果的查询将呈现警告消息                                    |
| Render Null As                                                                                                                 | 将 Null 渲染为                                                |
| What null/non-existent should show up as in tables, by default. This supports Markdown notation.                               | 默认情况下，null/不存在的内容应显示在表中。这支持 Markdown 表示法                  |
| Automatic View Refreshing                                                                                                      | 自动刷新视图                                                    |
| If enabled, views will automatically refresh when files in your vault change; this can negatively affect                       | 如果启用，当 Vault 中的文档发生更改时，视图将自动刷新;这可能会产生负面影响"                |
| some functionality like embeds in views, so turn it off if such functionality is not working                                   | 某些功能（例如嵌入视图），因此如果此类功能不起作用，请将其关闭                           |
| Refresh Interval                                                                                                               | 刷新间隔                                                      |
| How long to wait (in milliseconds) for files to stop changing before updating views                                            | 在更新视图之前等待文档停止更改的时间(以毫秒为单位)。                               |
| Date Format                                                                                                                    | 日期格式                                                      |
| The default date format (see Luxon date format options).                                                                       | 默认日期格式(请参阅 Luxon 日期格式选项)。                                 |
| Currently                                                                                                                      | 目前                                                        |
| The default date format (see Luxon date format options)."                                                                      | 默认日期格式(请参阅 Luxon 日期格式选项)。                                 |
| The default date and time format (see Luxon date format options).                                                              | 默认日期和时间格式(请参阅 Luxon 日期格式选项                                |
| Table Settings                                                                                                                 | 表格设置                                                      |
| Primary Column Name                                                                                                            | 主列名称                                                      |
| The name of the default ID column in tables; this is the auto-generated first column that links to the source file             | 表中默认 ID 列的名称;这是自动生成的第一列，链接到源文档                            |
| Grouped Column Name                                                                                                            | 分组列名称                                                     |
| The name of the default ID column in tables, when the table is on grouped data; this is the auto-generated first column        | 当表位于分组数据上时，表中默认 ID 列的名称;这是自动生成的第一列                        |
| that links to the source file/group                                                                                            | 链接到源文档/组                                                  |
| Task Settings                                                                                                                  | 任务设置                                                      |
| Automatic Task Completion Tracking                                                                                             | 自动任务完成跟踪                                                  |
| If enabled, Dataview will automatically append tasks with their completion date when they are checked in Dataview views        | 如果启用，Dataview 将在 Dataview 视图中签入任务时自动附加任务的完成日期.            |
| Example with default field name and date format: - [x] my task [completion:: 2022-01-01]                                       | 默认字段名称和日期格式的示例： - [x] 我的任务 [完成：： 2022-01-01]              |
| Use Emoji Shorthand for Completion                                                                                             | 使用表情符号速记完成                                                |
| If enabled, will use emoji shorthand instead of inline field formatting to fill out implicit task field "completion".          | 如果启用，将使用表情符号简写而不是行内字段格式来填充隐式任务字段 "completion".            |
| Example: - [x] my task ✅ 2022-01-01                                                                                            | 示例：- [x] 我的任务 ✅ 2022-01-01                                |
| Disable this to customize the completion date format or field name, or to use Dataview inline field formatting.                | 禁用此功能以自定义完成日期格式或字段名称，或者使用 Dataview 行内字段格式.                |
| Only available when "Automatic Task Completion Tracking" is enabled                                                            | 仅在启用 "自动任务完成跟踪" 时可用                                       |
| Completion Field Name                                                                                                          | 完成字段名称                                                    |
| Text used as inline field key for task completion date when toggling a task's checkbox in a dataview view.                     | 在 Dataview 视图中切换任务复选框时，作为行内字段键用于任务完成日期的文本.                |
| Only available when "Automatic Task Completion Tracking" is enabled and "Use Emoji Shorthand for Completion" is disabled       | 仅当启用"自动任务完成跟踪"和禁用"使用表情符号速记完成"时可用。                         |
| Completion Date Format                                                                                                         | 完成日期格式                                                    |
| Date-time format for task completion date when toggling a task's checkbox in a dataview view (see Luxon date format options)." | 在 Dataview 视图中切换任务复选框时，用于任务完成日期的日期时间格式(参见 Luxon 日期格式选项)." |
| Only available when "Automatic Task Completion Tracking" is enabled and "Use Emoji Shorthand for Completion" is disabled.',    | 仅在启用 "自动任务完成跟踪" 且禁用 "使用表情符号简写来表示完成" 时可用.                  |
| Only available when "Automatic Task Completion Tracking" is enabled and "Use Emoji Shorthand for Completion" is disabled.      | 仅当启用"自动任务完成跟踪"和禁用"使用表情符号速记完成"时可用。                         |
| Recursive Sub-Task Completion                                                                                                  | 递归子任务完成                                                   |
| If enabled, completing a task in a DataView will automatically complete its subtasks too                                       | 如果启用，则在 DataView 中完成任务也将自动完成其子任务                          |



