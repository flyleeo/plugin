# plugin
这是插件   PluginAPP 是宿主  这个是插件


  加载布局的插件app
	
	将PluginActivity 和PluginResources 放到插件APP中   activity继承PluginActivity 不需要manifest声明
	
	加载布局 只需将布局名称 设置到setContentName("布局名称")

	初始化控件调用 findViewByName("控件名称")

	获取图片可用 getDrawable("图片名称")

	示例可看 TestActivity
