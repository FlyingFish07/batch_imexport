#Batch Import and Export 

这个drupal模块用来实现对于内容进行批量导入和导出功能，仅仅是为了熟悉一下drupal的batch API，后面处理耗时较长的任务会有用。
具体功能如下：

	1.通过form api实现文件上传，解析，并通过batch接口将这些数据加载到node中
	2.通过batch接口实现对于节点的title、body信息的导出，并实现文件的下载。
