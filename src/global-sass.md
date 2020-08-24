### 全局引入scss文件配置



在 **vue.config.js** 中添加配置

``` javascript
module.exports = {
    
    css: {
        loaderOptions: {
            scss: {
                prependData: `
					@import "scss文件路径";
				`
            }
        }
    }
    
}
```

