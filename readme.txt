atom 问题收集
功能描述:Synchronize settings, keymaps, user styles, init script, snippets and installed packages across Atom instances.
(简言之就是可以同步Atom的设置文件,自定义快捷键,用户风格,初始化脚本及代码片段,还支持已安装的插件同步)

Features

Sync Atom's and package settings
Sync installed packages
Sync user keymaps
Sync user styles
Sync user init script
Sync snippets
Sync user defined text files
Manual backup/restore to a gist

获取安装方式

命令行安装: $ apm install sync-settings
设置中心: 搜索sync-settings

设置及使用方法

初始化设置

进入设置中心找到该插件,进去setting
打开自己的github创建一个personal access token – 然后复制生成的token序列,粘贴到插件的setting里面的(最后再放图,一目了然)
再打开github的gist服务,创建一个gist–复制生成gistID,也粘贴到二步设置里面

使用方法(配置完毕后)

在文档编辑页面,按下全局命令搜索面板(Ctrl+shift+p)
搜索sync- ,会有可选项
sync-settings:backup – 这条命令是备份当前的配置
sync-settings:restore – 这条命令是回复配置,是直接覆盖的;
sync-settings:view-backup – 这条是当你执行备份后到线上查询你的备份的,也就是到你的gist code里面
sync-settings:check-backup – 这条是查询最后一次是否正常
备份成功和失败都有一条信息提醒,看图
