简易模板引擎(共8个标签)
1，{inc:header.htm}					包含模板
2，{hook:header_before.htm}			模板钩子(方便插件修改模板)
3，{php}{/php}						模板支持PHP代码 (不支持<??><?php?>的写法)
4，{block:}{/block}					模板模块
5，{loop:}{/loop}					数组遍历
6，{if:} {else} {eleseif:} {/if}	逻辑判断
7，{$变量}							显示变量
8，{@$k+1}							显示逻辑变量 (用于运算时的输出，一般用的很少)

整形 (INT):可不用设置，设置后可作为表单的默认值
浮点型 (FLOAT):可不用设置，设置后可作为表单的默认值
单行文本框 (VARCHAR):可不用设置，设置后可作为表单的默认值
文本区域 (VARCHAR):可不用设置，设置后可作为表单的默认值
下拉菜单 (VARCHAR):必须填写，格式为key=value,使用|作为分割符，如 1=是|0=否，存储的时候存储key

下拉菜单 模型数据 (INT):必须填写，格式为"分类模型标识|作为显示文本的字段标识"

联动下拉菜单 (VARCHAR):必须填写，格式为"分类模型标识|作为显示文本的字段标识|分类层级|最大选择个数"

单选按钮 (VARCHAR):必须填写，格式为key=value,使用|作为分割符，如 1=是|0=否，存储的时候存储key

单选按钮 模型数据 (INT):必须填写，格式为"分类模型标识|作为显示文本的字段标识"

复选框 (VARCHAR):必须填写，格式为key=value,使用|作为分割符，如 1=是|0=否，存储的时候存储key

复选框 ** 模型数据** (VARCHAR):必须填写，格式为"分类模型标识|作为显示文本的字段标识"

编辑器 (TEXT):可不用设置，设置后可作为表单的默认值
编辑器 简 (TEXT):可不用设置，设置后可作为表单的默认值
日期时间 (VARCHAR):可不用设置，设置后可作为表单的默认值
颜色选择器 (VARCHAR):可不用设置，设置后可作为表单的默认值
内容模型调用 (INT):必须填写，格式为"内容模型标识|作为显示文本的字段标识"
