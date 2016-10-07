# koa-handluploadfile
处理文件上传

###makeup
```
npm install koa-handluploadfile
```

###USE
```
import body from 'koa-better-body'

app.use(convert(new body()))

app.use(handleffile("/public/file/upload/image"))//会将koa－better-body上传的文件，存储到这个文件夹下面，暂时还不能使用（如果要用，直接将这个index弄成你的模块就可以使用了。。。主要是koa2还不支持这样写中间件的语法）
```

