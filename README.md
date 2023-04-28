用Pake打包一个桌面应用👉```https://www.perplexity.ai/``` 


#### 打包前期工作
* [官方帮助文档](https://github.com/tw93/Pake/blob/master/bin/README.md)
	* node>=16 
	* rust >= 1.2

#### mac打包命令

```
// M1&Intel芯片打包
pake https://www.perplexity.ai  --name PerplexityAi --icon ./logo.icns --show-menu --multi-arch

//单芯片(本机环境)打包
pake https://www.perplexity.ai  --name PerplexityAi --icon ./logo.icns --show-menu

```

* [Mac客户端(M1&Intel)](https://github.com/ghyghoo8/pake-perplexity.ai/raw/main/PerplexityAi.dmg)
