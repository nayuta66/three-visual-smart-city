# 说明
    声音是有温度和色彩的
    主要功能：
        音制作：
            1、ai音频训练生成：通过拖拽上传source音频轨道，model参照物音频轨道，生成你想要的专属target音频轨道
            2、ai图片生成：根据target音频轨道，生成音频的专属图片作为封面
            3、也可以仅上传音频和封面
            4、制作完成之后，会发短信/邮件通知用户
            例如：你可以把喜欢的人或事物的音频作为model参照物音频，自己录制一段音频（想说什么都可以）作为source音频，然后这段音频的内容就
            会模仿参照物的声音，用参照物的声音说出你所说的内容。比如ai许嵩，ai本兮，也可以是你喜欢的那个人ai恋人。
        音展区：
            1、按照热度，最新，
            2、展示用户用ai生成或者自己上传的专属音乐/声音（例如白噪音、asmr助眠、自然音等），附带用户编辑的数字藏品链接，具备价值的音频，
            可作为数字藏品展出，目前仅支持私下联系
            3、作品点赞、评论、收藏
        其他功能待定...
# 技术选型
    create-react-app、react18、ts；采用craco覆盖cra的webpack的配置
    less、antd5、styled-componets、react-spring动画库
    threejs、blender建模
    ai音频（训练模型待定）、ai图片（训练模型待定）

# 安装依赖
    npm install

# 执行程序
    npm start

# 打包程序
    npm run build