# PostCSS中文文档

### 参与翻译
* [关于翻译/校对 - 任务认领](https://github.com/guoyueting)


### 关于需要翻译文件的目录结构

以下是翻译人员需要了解的目录结构

```
.
├── API/                            // API目录
│   ├── CLASSES/..                  // CLASSES的API接口说明 
│   ├── GLOBAL/..                   // GLOBAL的API接口说明
│   ├── NAMESPACES/..               // NAMESPACES的API接口说明
├── Docs/ 					        // 官方文档
│   ├── guidelines/..               // guidelines   官方指南
│   ├── api.cn.md                   // api     api介绍
│   ├── plugins.cn.md               // plugins    插件说明
│   ├── source-maps.cn.md           // source-maps   
│   ├── syntax.cn.md                // syntax    
│   └── writing-a-plugin.cn.md      // writing-a-plugin  
├── Plugins/                        // 插件  导航页入口
│   ├── Readme.cn.md                // readmes    指add a plugin的github的readme文档，添加插件 
├── Setup/                    
│   ├── index.md                    //  官网首页文字部分
├── ...                       
│   └── ...
```


### 翻译流程 - Forking工作流
1. fork 本仓库到自己的账号下，克隆 fork 的仓库到本地
2. 从 [Projects](https://github.com/guoyueting/POSTCSS-CN/tree/postcss-md-dev-1.0.0) 中所有由 [`待翻译`](https://github.com/guoyueting/POSTCSS-CN/issues) 标记的文章中，选择一篇自己感兴趣的进行翻译，并在评论中留下**你翻译预计完成的时间**
3. 翻译完毕，提交到自己的分支。<br>
	整个git操作步骤如下:
	* 克隆仓库到本地 git clone https://github.com/guoyueting/POSTCSS-CN.git
	* 创建并切换到自己的分支 git checkout -b 'dev-1.1.0-guoyueting' （命名时请参照dev-1.1.0-翻译人员姓名）
	* git add .
	* git commit -m'翻译的文档路径及文件名称'
	* git push [remoteName] [localBranchName]，若远程仓不存在，则采用git push origin [localBranchName] 

	详细的git操作请参考[Git官方文档](https://git-scm.com/book/zh/v2)
4. 记得修改issue标签为待校对<br>

