# 这是一个上传项目到github的教程

给那些像我一样走了很多弯路的朋友，网上的SSh Http教程，终端操作云云简直搞得人一个头两个大

* 上传项目到github真的很简单很简单

1. git账号 请自行注册自行申请
2. 下载github mac版，请自行度娘安装
3. 登录git mac端， 输入账号、密码然后一直continue 直到界面出现

    第一次进入git客户端 界面应该是这样的
    ![界面应该是全空 或者只有几句英文提示](https://github.com/2232787525/uploading-projects-in-GitHub/blob/master/img/屏幕快照%202017-11-21%20下午5.45.44.png)

4. 建立自己的仓库
    点击左上角“+”， 选择Create， 输入仓库名，第二个输入框会自动填写，点击create repository就建好了本地仓库，左侧列表会出现自己的仓库
    
    ![建立自己的仓库](https://github.com/2232787525/uploading-projects-in-GitHub/blob/master/img/屏幕快照%202017-11-21%20下午5.47.45.png)
    
5. 找到上一步中的 Local Path 本地地址， 或者左侧列表右击 Open in Finder。在这个文件夹中就可以开始修改新建操作
    下面我在里面建了一个文件夹“img”，然后拖动图片进去。回到客户端可以看到有好几个change
       ![拖动图片进去](https://github.com/2232787525/uploading-projects-in-GitHub/blob/master/img/建文件夹拖入img.png)
        ![好几个change](https://github.com/2232787525/uploading-projects-in-GitHub/blob/master/img/change.png)
        
6. summary Description两个输入框输入后，就可以点击 Commit to master 提交修改内容
        很多小伙伴这时候就会兴高采烈的跑去网页看，结果发现自己被骗了，刚刚提交的根本什么都没有嘛
        ![提交后](https://github.com/2232787525/uploading-projects-in-GitHub/blob/master/img/提交后.png)
        其实我们是少了一步。 仔细看这个图。除了后面两个圈圈，其他都是点点。 点点代表已和git同步，倒数第二个圈就是我们刚刚提交的，左下角change那里 还会有一个undo的按钮，标识取消提交此次修改。 这么不人性化的设计我也是醉了。接下来点击圈圈上面的按钮，首次提交应该显示Publish， 第二次后显示Sync
         ![圈圈](https://github.com/2232787525/uploading-projects-in-GitHub/blob/master/img/圈圈、.png)
         
     7. 点击Publish或Sync后 可以填写 git 上面的仓库信息了，感觉离成功越来越近哈哈。
         ![git上的仓库信息填写](https://github.com/2232787525/uploading-projects-in-GitHub/blob/master/img/git上的仓库信息填写.png)
         
     8. 正在pushing
         ![正在pushing](https://github.com/2232787525/uploading-projects-in-GitHub/blob/master/img/正在push.png)
         push完成 去git看看吧
         ![push完成 去git看看吧](https://github.com/2232787525/uploading-projects-in-GitHub/blob/master/img/在网页查看.png)
         网页效果
         ![push完成 去git看看吧](https://github.com/2232787525/uploading-projects-in-GitHub/blob/master/img/网页效果.png)
        
