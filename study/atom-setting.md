### 保存时自动eslint检测

1. 下载linter-eslint插件
2. 进入设置->fix errors on save 选项打钩

### emmet失效问题解决

1. File->Keymap
2. 将以下代码复制到keymap.cson:
	```
		'atom-text-editor:not([mini])':
  		'tab': 'emmet:expand-abbreviation-with-tab'
	```
