<h1 align="center">
  Douyin-Vue

## 在线访问

[//]: # (Gitee Pages: [https://zyronon.gitee.io/douyin/]&#40;https://zyronon.gitee.io/douyin/&#41;&#40;中国地区推荐访问这个地址&#41;   )
[//]: # (注意：Gitee Pages现在无法更新，代码不是最新的。如果你能翻墙推荐访问下面地址  )

Github Pages: [https://jinmohan.github.io/douyin/](https://jinmohan.github.io/douyin/)  

[//]: # (Gitee pages: [https://dy.ttentau.top/]&#40;https://dy.ttentau.top/&#41; &#40;中国地区推荐访问这个地址&#41;  )
[//]: # (Github pages: [https://zyronon.github.io/douyin/]&#40;https://zyronon.github.io/douyin/&#41;  )
[//]: # (Netlify: [https://douyins.netlify.app/]&#40;https://douyins.netlify.app/&#41;)
[//]: # (Vercel:  [https://douyins.vercel.app]&#40;https://douyins.vercel.app&#41;)
[//]: # (Android Apk: https://github.com/zyronon/douyin/releases)
[//]: # (**注意**：`PC` 必须将浏览器切到手机模式，先按 `F12` 调出控制台，再按 `Ctrl+Shift+M`才能正常预览)
[//]: # (**注意**：手机请用  [Via 浏览器]&#40;https://viayoo.com/zh-cn/&#41;  或 Chrome 浏览器预览。其它浏览器可能会强制将视频全屏，导致无法正常显示)

## 链接

【模仿抖音系列】一：[200行代码实现类似Swiper.js的轮播组件](https://juejin.cn/post/7360512664317018146)  
【模仿抖音系列】二：[实现抖音 “视频无限滑动“效果](https://juejin.cn/post/7361614921519054883)  
【模仿抖音系列】三：[Vue 路由使用介绍以及添加转场动画](https://juejin.cn/post/7362528152777130025)  
【模仿抖音系列】四：[Vue 有条件路由缓存，就像传统新闻网站一样](https://juejin.cn/post/7365334891473240101)  
【模仿抖音系列】五：[Github Actions 部署 Pages、同步到 Gitee、翻译 README 、 打包 docker 镜像](https://juejin.cn/post/7365757742381957161)  
【模仿抖音系列】六：[使用rem、动态vh自适应移动端](https://juejin.cn/post/7374452765273538595)

## 运行
注意：本项目仅适用于学习和研究，不得用于商业使用

### 快速部署至 Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/zyronon/douyin)

### 部署到 Docker
```bash
# pull Docker image
docker pull ghcr.io/zyronon/douyin-vue:latest

# start container, nginx reverse proxy custom port, for example: docker run -d -p 80:80 ghcr.io/zyronon/douyin-vue:latest
docker run -d -p 80:80 ghcr.io/zyronon/douyin-vue:latest
```
### 本地开发
**注意：必须 git 命令 clone 下来才能运行，下载 zip 包是无法运行的。如果 clone 速度太慢，推荐使用 gitee 地址**

```bash
git clone https://gitee.com/zyronon/douyin.git (中国使用)
          https://github.com/zyronon/douyin.git 
cd douyin
npm install
npm run dev
```

打开浏览器并访问: [http://127.0.0.1:3000](http://127.0.0.1:3000)

**注意：需要将浏览器切至手机模式，先按 `F12` 调出控制台，再按 `Ctrl+Shift+M` 才能正常预览**

## 数据来源

视频来源于以下抖音网红

- `我是香秀 🐂🍺`: [https://v.douyin.com/iYRAPA2L/](https://v.douyin.com/iYRAPA2L/)
- `杨老虎 🐯（磕穿下巴掉牙版）`: [https://v.douyin.com/iYRA56de/](https://v.douyin.com/iYRA56de/)
- `条子`: [https://v.douyin.com/iYRAaqjr/](https://v.douyin.com/iYRAaqjr/)
- `达莎 Digi`：[https://v.douyin.com/iYRA6rwT/](https://v.douyin.com/iYRA6rwT/)
- `小橙子`: [https://v.douyin.com/iYRAnudw/](https://v.douyin.com/iYRAnudw/)
- `南恬`: [https://v.douyin.com/iYRAbKm3/](https://v.douyin.com/iYRAbKm3/)
- `小霸宠牛排 🥩`：[https://v.douyin.com/iYRSosVB/](https://v.douyin.com/iYRSosVB/)
- `奶茶妹 ◕🌱`: [https://v.douyin.com/iYRACKhP/](https://v.douyin.com/iYRACKhP/)
- `我才是岚岚`: [https://v.douyin.com/iYRAQM1C/](https://v.douyin.com/iYRAQM1C/)
- `周憬艺 ziran`: [https://v.douyin.com/iYRAQs4h/](https://v.douyin.com/iYRAQs4h/)
- `刘思瑶 nice`: [https://v.douyin.com/iYRAaERn/](https://v.douyin.com/iYRAaERn/)
- `彭十六 elf`: [https://v.douyin.com/iYRAHrVG/](https://v.douyin.com/iYRAHrVG/)
- `李子柒`: [https://v.douyin.com/iYRA5B88/](https://v.douyin.com/iYRA5B88/)

图片来自于小红书公开笔记

以上内容均是互联网公开信息


## 功能与建议

目前项目处于开发初期，新功能正在持续添加中，如果你对软件有任何功能与建议，欢迎在 `Issues` 中提出
如果你也喜欢本软件的设计思想，欢迎提交 `PR`，非常感谢你对我们的支持！

## 联系我

您可以联系我的邮箱 <a href="mailto:zyronon@163.com">2093145185@qq.com</a>
> 分享我其他开源项目：
>
>_[**Typing Word
** - 可在网页上使用的背单词软件~](https://github.com/zyronon/typing-word) <img src="https://img.shields.io/github/stars/zyronon/typing-word.svg?style=flat-square&label=Star&color=4285dd&logo=github" height="16px" />_  
> _[**Web Scripts
** - 一些好用的油猴脚本~](https://github.com/zyronon/web-scripts) <img src="https://img.shields.io/github/stars/zyronon/web-scripts.svg?style=flat-square&label=Star&color=4285dd&logo=github" height="16px" />_

## 许可协议

[GPL](LICENSE)
