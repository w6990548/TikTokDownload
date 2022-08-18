<div align="center">
<img width="450px" src="https://tva1.sinaimg.cn/large/006908GAly1gqg5fvxuutj30dw0dwt99.jpg"/>
</div>

<h1 align="center">TikTokDownload</h1>

<p align="center">✨ 抖音去水印视频下载 ✨</p>

<p align="center">
<a href="https://github.com/Johnserf-Seed/TikTokDownload/blob/main/LICENSE">
<img src="https://img.shields.io/github/license/johnserf-seed/tiktokdownload">
</a>
<a href="https://github.com/Johnserf-Seed/TikTokDownload">
<img src="https://img.shields.io/badge/python-v3.8.5-green">
</a>
<a href="https://github.com/Johnserf-Seed/TikTokDownload">
<img src="https://img.shields.io/github/stars/johnserf-seed/tiktokdownload?style=social">
</a>
<a href="https://github.com/Johnserf-Seed/TikTokDownload">
<img src="https://img.shields.io/github/forks/johnserf-seed/tiktokdownload?style=social">
</a>
<a target="_blank" href="http://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&email=PFZTVFJPWU5aEU9ZWVh8WlNEUV1VUBJfU1E" style="text-decoration:none;">
<img src="http://rescdn.qqmail.com/zh_CN/htmledition/images/function/qm_open/ico_mailme_11.png"/>
</a>
</p>

[English](README-EN.md)   [简体中文](README.md)

## 使用教程

1. 运行软件前先打开目录下 conf.ini 文件按照要求进行配置

  批量下载可直接修改配置文件，单一视频下载推荐<a href="https://github.com/Johnserf-Seed/TikTokWeb">TikTokWeb</a>项目在线解析

<table>
    <tr>
        <td><center><img src="https://tva2.sinaimg.cn/large/006908GAly1h5be5mhf5wj30am0bcabz.jpg"></center></td>
        <td><center><img src="https://tvax3.sinaimg.cn/large/006908GAly1h5be2em4ovj30ad0ba77s.jpg"></center></td>
    </tr>
    <tr>
    	<td>新版配置文件conf.ini</td>
    	<td>旧版配置文件conf.conf</td>
    </tr>
</table>

2. ~~本项目制作了pip包，可以输入 ``` pip install TikTokDownload==1.2.3 ```安装~~
（1.2.3没有及时更新到1.3.0，请勿安装）

<img src="https://tvax3.sinaimg.cn/large/006908GAly1gqg4j7ppuij30w60nnmxz.jpg" alt="image" width="800" data-width="808" data-height="224">

<img src="https://tvax3.sinaimg.cn/large/006908GAly1gqg4jfswmxj30ul08xmy8.jpg" alt="image" width="800" data-width="808" data-height="224">

   **包使用方法：**

   ```python
   #example.py
   import TikTokDownload as TK
   import TikTokMulti as MTK
   # 删除注释使用对应文件
   
   # 用户主页批量下载
   # MTK.TikTok()
   
   # 单视频下载
   # TK.video_download(*TK.main())
   ```

   ***example.py需确保TikTokMulti.py与TikTokDownload.py两个文件都在相同目录中***

3. 如何编译

   运行根目录下```build.bat```文件按控制台提示即可，生成的```exe```在```./dist```目录中

4. 批量保存

	- 下载录制
	<img src="https://tva3.sinaimg.cn/large/006908GAly1h5bel0gf8ng319r0g3qvc.gif" alt="image" width="800" data-width="808" data-height="224">
   
	- 跳过已下载
	<img src="https://tva3.sinaimg.cn/large/006908GAly1h5beq5uq0qg313m0ktdl5.gif" alt="image" width="800" data-width="808" data-height="224">
	
	- 图文下载
	<img src="https://tva4.sinaimg.cn/large/006908GAly1h5bevy693qg313m0kt41g.gif" alt="image" width="800" data-width="808" data-height="224">
   
	- 全部下载
	<img src="https://tva3.sinaimg.cn/large/006908GAly1gqg4dk7fiyj31cw0mo4qp.jpg" alt="image" width="800" data-width="808" data-height="224">

	- 资源文件夹
	<img src="https://tva2.sinaimg.cn/large/006908GAly1gn1dim1oojj30q30ertaz.jpg" alt="image" width="800" data-width="808" data-height="224">
   
5. issues反馈
    如有您有任何bug或者意见反馈请在 https://github.com/Johnserf-Seed/TikTokDownload/issues 发起

<img src="https://tva3.sinaimg.cn/large/006908GAly1gqg4f0b9kgj31hc0qwmz6.jpg" alt="image" width="800" data-width="808" data-height="224">

6. 单一下载模式 TikTokDownload,批量下载模式TikTokMulti,图文下载 TikTokPic,测试版图形界面 TikTokMultiGUI

**注意（常见错误）：**

1. 单个视频链接与用户主页链接要分清，软件闪退可以通过终端运行查看报错信息（一般是链接弄错的问题）

   如：

    - <img src="https://tvax4.sinaimg.cn/large/006908GAly1gn1dofvcc7j309800k3y9.jpg" alt="image" width="800" data-width="808" data-height="224">

    - <img src="https://tvax2.sinaimg.cn/large/006908GAly1gn1dpoiqhzj306d0193ya.jpg" alt="image" width="800" data-width="808" data-height="224">

   ***链接一定要输入仔细哦~***

2. 配置文件一定要注意编码格式（推荐Notepad++）

   **正确：**

<img src="https://tva1.sinaimg.cn/large/006908GAly1gn1dl6jv3hj30ib09tq3k.jpg" alt="image" width="700" data-width="808" data-height="224">

   **错误：**

<img src="https://tva1.sinaimg.cn/large/006908GAly1gn1dmakebqj30qh03lmx8.jpg" alt="image" width="700" data-width="808" data-height="224">

   挺抽风的，另存为的UTF-8居然不可以会闪退，玄学

3. 如果出现长时间的api抓取可能是姿势不对（抖音api比较奇怪）
4. 现在新增了日志功能，可以在logs中找到所有的日志文件，汇报issue的时候可以附上
<img src="https://tva2.sinaimg.cn/large/006908GAly1h5beyv1f13j30gk07pgqg.jpg" width="700">
<img src="https://tvax4.sinaimg.cn/large/006908GAly1h5bf16rylfj310q0ijb29.jpg">

## New

**05/01 更新了无水印图集下载功能 ->TikTokPic.py**

<img src="https://tvax2.sinaimg.cn/large/006908GAly1h1s8uky10aj30us0gh0ym.jpg" alt="image" width="800" data-width="1108" data-height="593">

<img src="https://tva4.sinaimg.cn/large/006908GAly1h1s8pryq7rj30mg068tdn.jpg" alt="image" width="800" data-width="808" data-height="224">

**04/23 后的新版支持解析1080p分辨率视频（*注，虽然下载的是1080p，但是原视频不满足1080p的情况下，即使下载到本地也还是原本的分辨率***）

**720p对比1080p**

<img src="https://tva4.sinaimg.cn/large/006908GAly1h1iwtyrqyij30id073q52.jpg" alt="image" width="800" data-width="808" data-height="224">

**GUI版即将发布**

<img src="https://tva3.sinaimg.cn/large/006908GAly1h5bf3snbfij30sm0gzwhc.jpg" alt="image" width="800" data-width="808" data-height="224">

***可自行在GUI文件夹内编译ui -> pyuic5 -o Main.py Main.ui***

**V1.3.0控制台界面版本**

<img src="https://tvax1.sinaimg.cn/large/006908GAly1h5bf5oylooj30ui0m20zn.jpg" alt="image" width="800" data-width="808" data-height="224">

**uTools插件同步开发中...**

<img src="https://tva4.sinaimg.cn/large/006908GAgy1gtbtg4t2n3j30ma02y40d.jpg" alt="image" width="800" data-width="808" data-height="224">

<img src="https://tvax1.sinaimg.cn/large/006908GAgy1gtbtgut1njj30ma02ygmk.jpg" alt="image" width="800" data-width="808" data-height="224">

<img src="https://tva2.sinaimg.cn/large/006908GAly1h5bf4dvde0j30m00gnwij.jpg" alt="image" width="800" data-width="808" data-height="224">

## ToDo
- [x] 无水印图集下载功能
- [x] 可视化界面
- [ ] 支持多平台视频解析
- [ ] 记录作品详细信息到本地数据库
- [ ] 本地服务检测抖音关注用户作品的更新情况***(并推送)***
- [ ] 所有已关注用户主页的视频批量下载的可选功能
- [ ] 直播推流保存
- [ ] 制作本地接口解析服务


## Web版项目

[Johnserf-Seed/TikTokWeb](https://github.com/Johnserf-Seed/TikTokWeb)

<img src="https://tvax3.sinaimg.cn/large/006908GAly1h1e6e0mjmbj30m217a168.jpg" alt="image" width="800" data-width="808" data-height="224">

<img src="https://tvax4.sinaimg.cn/large/006908GAly1gn1dxspeqeg302s02sdgf.gif" alt="image" width="100" data-width="808" data-height="224">
