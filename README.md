# gallery-by-react
## 感想

这是一个完全按照慕课网上课程一步一步敲出来的一个小画廊。

由于版本的不同，所以在过程中简直痛不欲生，但又不舍得放弃，尤其最后上传到github pages这一个地方被卡了好久.

但看了其他的代码，看了一些评论，对比自己的项目，做了好多改动，最终才能够顺畅的运行在https://linban.github.io/gallery-by-react

大家如果有兴趣可以看一下

## 总结

这个项目总共做了两次，所以教程也看了好几次，才最终把一些地方一点点修改好，现在就其中需要注意的几个地方提一下

几个指令需要注意（括号里是旧版）：
grunt build(npm run dist), grunt serve:dist(npm run serve:dist), grunt serve(npm run start或者node server.js)
git这些命令没有改变，和原来的一样

最后打包上传到gh-pages需要修改的几个地方：
dist目录中的index.html文件最后src引用的地方"/assets/app.js"改成"assets/app.js"，也就是去掉前面的斜杠
cfg目录中的base.js中的两处publicPath中defaultSettings.publicpath都要修改成'assets/'

其他的没有碰到什么大问题，都是比较容易解决的。
