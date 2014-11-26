node.js_CLI
===========

需要使用這樣的功能
````
hello
````
傳出一個 hello world 做法:

1.目錄下需要 package.json:
````javascript
{	
	"name": "plus",
  	"version": "0.0.1",
  	"preferGlobal": "true",
  	"description": "Quick Build",
	"bin": {
    	"plus": "./bin/plus" //bin目錄
  	}
}
````
2.bin 的plus檔案需要寫入:
````javascript
#!/usr/bin/env node
````
3.npm link 就能使用了
