# PicGo + Github效果图

<img src="https://cdn.jsdelivr.net/gh/soeos/111@master/img/202308160447293.png" alt="效果图">


## 配置Github

1. 创建一个新仓库，用于存放图片。
   填写仓库名称和描述，且仓库必须是public的，否则存储的图片不能正常访问。
    <img src="https://cdn.jsdelivr.net/gh/soeos/111@master/img/202308160455206.png" alt="">
2. 生成一个token，用于picGo访问github  
   选择左侧菜单的Developer settings
   

3. 选择左侧Personal access tokens，再点击Generate new token
   <img src="https://cdn.jsdelivr.net/gh/soeos/111@master/img/202308160458196.png" alt="">
   

5. 填写 Notes 信息，选择 token 过期时间，为了安全，GitHub 会强烈建议不要设置成永久。这个大家根据自己实际情况选择，到期之后重新生成即可。复选框的话，repo 一定要全选，其他的无所谓。
   <img src="https://cdn.jsdelivr.net/gh/soeos/111@master/img/202308160500272.png" alt="">



7. 确定之后，就生成我们需要的 token 了。
   <img src="https://cdn.jsdelivr.net/gh/soeos/111@master/img/202308160507608.png" alt="">

==注意== :生成的token只会在这里显示一次，所以记得单独保存下来哦。

至此，Github的配置完成。

## PicGo配置

设定仓库名：上文在 GitHub 创建的仓库。
设定分支名：main。
设定 Token：上文生成的 token。
指定存储路径：为空的话会上传到跟目录，也可以指定路径。
设定自定义域名：可以为空，这里为了使用 CDN 加快图片的访问速度，按这样格式填写：
https://cdn.jsdelivr.net/gh/用户名/仓库@分支

<img src="https://cdn.jsdelivr.net/gh/soeos/111@master/img/202308160501029.png" alt="">

直接拖拽，或者点击上传都可以。

<img src="https://cdn.jsdelivr.net/gh/soeos/111@master/img/202308160503032.png" alt="">

上传成功之后，在 GitHub 的仓库就可以看到了。

<img src="https://cdn.jsdelivr.net/gh/soeos/111@master/img/202308160447293.png" alt="">

最后，在相册里复制外链，粘贴到我们的 markdown 文档中，就可以看到图片了。
