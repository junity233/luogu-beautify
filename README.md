# luogu-beautify
美化洛谷

## Features
 - 全页面背景图片
 - 透明度刚刚好的半透明卡片
 - 圆角

## 使用方法
先下个可以添加自制css的插件，比如 [User JavaScript and CSS](https://chrome.google.com/webstore/detail/nbhcbdghjpllgmfilhnhkllmkecfmpld)
然后把 [luogu.css](luogu.css) 应用上去就可以了

## 备注
若出现加载css后无效果，可尝试在luogu.css的每个声明后添加``!important``。

或者开启 ```User JavaScript and CSS``` 的 ```Highest CSS priority``` 选项
e.g.
```css
#app > div.main-container > main{
	background-color: rgba(239, 239, 239,0);
}
```
=>
```css
#app > div.main-container > main{
	background-color: rgba(239, 239, 239,0)!important;
}
```


## 屏幕截图
![](Screenshot_2.png)
![](Screenshot_4.png)
![](Screenshot_5.png)
