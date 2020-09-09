# DocStrapPs
DocStrapPs 基于 [DocStrap](https://github.com/docstrap/docstrap) 进行修改的 [Jsdoc](https://github.com/jsdoc/jsdoc) 文档模板 

### Install ###
```
npm install --save-dev docstrapps
```

### Use ###
修改 jsdoc 配置文件. 可参考 [about-configuring-jsdoc](https://jsdoc.app/about-configuring-jsdoc.html)  
```
{
	"opts": {
		"template": "./docstrap/template"
	}
}
```

### Configuring the template ###
```
{
	"opts": {},
	"template": {
		nameSpaceToNav: false,  // 是否将 @namespace 做为nav导航,
		theme: "flatlyPlus"  // 新增主题
	}
}
```
更多模板配置可参考 [docstrap template Configuring](https://github.com/docstrap/docstrap)
