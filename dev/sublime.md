#sublime 
##常用快捷键
* 选中当前的标签内容　　`cmd+shift+A`
* 复制历史　`ctr+alt+cmd+V`
* 纵向选择  `alt+选区`
* 跳转至对应的括号  `ctr+^+M`
* 格式化HTML  `ctr＋alt＋f`
* 选择词 `cmd + D`
* 粘贴并自动缩进 `cmd + shift + V`
* 拆分窗口  `cmd + alt + 2(3...)`

##自定义快捷方式
```
[
	{ "keys": ["super+,"], "command": "context_menu" },
	{ "keys": ["super+b"], "command": "svn_wc_commit" },
	{ "keys": ["super+u"], "command": "svn_wc_update" },
	{ "keys": ["super+alt+p"], "command": "svn_command_filter", "args": {"force_folder": true}  },
	{ "keys": ["super+alt+l"], "command": "svn_wc_log" },
	{ "keys": ["super+shift+l"], "command": "svn_log" },
	{ "keys": ["super+alt+}"], "command": "svn_merge" },
	{ "keys": ["super+6"], "command": "insert_snippet", "args": {"name": "Packages/User/filter.sublime-snippet"} },
	{ "keys": ["super+2"], "command": "insert_snippet", "args": {"name": "Packages/User/tpl.sublime-snippet"} },
	{ "keys": ["super+3"], "command": "insert_snippet", "args": {"name": "Packages/User/console.sublime-snippet"} },
	{ "keys": ["super+4"], "command": "insert_snippet", "args": {"name": "Packages/User/select.sublime-snippet"} },
	{ "keys": ["super+5"], "command": "insert_snippet", "args": {"name": "Packages/User/svn_msf.sublime-snippet"} },
	{ "keys": ["super+6"], "command": "insert_snippet", "args": {"name": "Packages/User/require_init.sublime-snippet"} },	
	{ "keys": ["ctrl+shift+]"], "command": "compact_expand_css", "args": { "action": "expand" }  },
	{ "keys": ["ctrl+alt+f"], "command": "tag_indent" },
	{ "keys": ["ctrl+shift+["], "command": "compact_expand_css", "args": { "action": "compact" } }		
]
```
##常用插件