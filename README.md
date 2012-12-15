1. ```rails new my_food```
2. ```rails generate scaffold food name:string description:string recipe:string```
   ```rake db:migrate```
3. 编辑```config/routes.rb```找到```# root :to => 'welcome#index'```去掉注释，```'welcome#index => foods#index```，按照提示删除```/public/index.html```
4. 浏览[devise](https://github.com/plataformatec/devise)主页的getting start节，按顺序操作安装用户模块，可以看samples来学习用法
5. 浏览[bootstrap-sass](https://github.com/thomas-mcdonald/bootstrap-sass)使用bootstrap美化界面，布局参考[Bootstrap官方指南](http://twitter.github.com/bootstrap/getting-started.html#examples)的源码和章节。

======
[官方Getting start中文过期](http://guides.ruby.tw/rails3/getting_started.html)
[官方指南，英文](http://guides.rubyonrails.org/getting_started.html)