# Codemirror-for-TinyMCE5-plugin
Codemirror for TinyMCE5 plugin
```
tinymce.init({
     selector: '#Body',      
     plugins: 'acecode'

  });
```
配置plugin.js
找到：
```
   title: 'Source Code',
       url: '/plugins/tinymce5/plugins/acecode/source.html',
       buttons: [
       ......
```
url修改成自己的项目的真实路径.

效果如下：
![界面截图](https://github.com/doubletong/Codemirror-for-TinyMCE-plugin/blob/master/images/ui.png?raw=true)
