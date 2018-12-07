

## 个人信息

 - **姓名**：沈林平/男/1992
 - **手机**：15986943076
 - **Email**：shenmu.mail@gmail.com
 - **微信号**：lin-sleeping
 - **学校专业**：本科/肇庆学院电子信息科学与技术（2011.09-2015.06）
 - **工作年限**：4年
 - **期望职位**：iOS工程师
 - **期望城市**：广州
 - **github**：https://github.com/kabicode
 - **英语水平**：CTE-4
 
&nbsp;&nbsp;
## 技能清单
- C / Objective-C / Swift / OC-Swift混编。
- 掌握runtime的原理和实际应用。
- 掌握MVC、MVVM等设计架构，熟练使用SingleTon、Delegate、Block等设计模式。 
- 熟悉TCP、HTTP/HTTPS、Socket等通信协议。 
- 熟练使用UIKit和可视化编程（Xib、StroyBoard）进行App的UI搭建。 
- 熟练使用NSThread、NSOperation、GCD等多线程编程。 
- 熟练使用CoreAnimation、CoreGraphics、CoreText等底层框架。 
- 熟练使用AVFoundation 等音视频框架。 
- 性能调优，熟练使用Xcode自带的调试工具，定位app的性能瓶颈并进行优化。 
- 调试工具：熟练使用Postman，Charles，Reveal等工具提高工作效率。 
- 能独立开发项目，自主解决问题能力强，能根据项目需求选择适合的技术方案。 
- 具备阅读Apple官方文档，和阅读主流第三方框架源码的能力。


&nbsp;&nbsp;
## 工作经历

### 团贷网 （ 2017年06月 ~ 至今 ）
iOS开发工程师

#### 网贷记账通 
网贷记账通是专为P2P网贷投资人打造的理财记账软件。
在此项目主要负责了：    
一、独自负责P2P平台自动同步框架。              
 1）自动爬取P2P平台数据，通过移动端模拟ajax请求、解析html标签的方式爬取数据。    
 2）使用NSOperationQueue进行多线程异步爬取，用NSCondition实现线程间数据同步。    
 3）封装爬取框架，方便其他业务模块调用。    
 4）制定JS-OC的爬取交互文档, 供JS与原生交互。   
 5）对需要注入的JS文本进行压缩、加密处理，防止第三方攻击。    
二、H5页面资源缓存框架。   
 1）自动拦截H5页面资源文件（如图片、js、css等），保存到沙盒路径下。加载时优先读取本地资源文件。当用户二次加载时，可提高页面加载速度，在弱网情况下效果更加明显。   
 2）建立更新机制，当请求资源更新时，本地资源同步更新。   
三、编写Fir自动打包上传脚本，简化测试打包流程。   

&nbsp;
### 荔枝微课 （ 2016年11月 ~ 2017年05月 ）   
iOS开发工程师

#### 荔枝微课    
荔枝微课是一款在线培训直播平台，更是线上教育平台，分享知识平台，支持十万人同时在线。    
**纯Swift项目**。该项目使用**Storyboard＋Swift3** 实现。     
在此项目主要负责了：    
一、 将项目代码从Swift2.2迁移到Swift3 上。   
二、直播间模块和课程模块的功能编写。    
1）直播间通讯模块基于webSocket实现，自定义通讯协议，支持PC、微信、移动端三端同步。   
2）直播间支持语音消息、文本、签到、图片、视频、音乐等等消息类型，支持撤回功能。    
3）支持PPT授课模式，支持语音绑定PPT功能，增加授课信息维度。   
4）课程模块课程介绍支持原生图文混排，支持课程试听。    
5）支持后台/锁屏状态下听课。（类型网易云音乐）    
三、集成IAP支付，提出iOS端建立荔枝币系统。    
1）在12月的时候苹果审核被拒，根据苹果审核文档，在App内消费虚拟物品需要通过IAP支付。遂集成苹果IAP支付，且同时参考了市场上的直播软件，建议建立代币系统，并命名为荔枝币。   
四、因App初期有部分海外用户，所以App全面支持本地化，支持中、英双文。   

&nbsp;
### 广东数库互联网金融信息服务有限公司   （ 2015年08月 ~ 2016年10月 ） 
iOS工程师

#### 数库金服    
数库金服是一款面向OTC市场的股权投资App，集直播路演，金融资讯，公司信息，选股器，智投圈为一体。    
在此项目主要负责了：    
一、直播与视频模块。底层采用ijkplayer进行实时推流解析，可支持HLS和RTMP推流。    
二、自定义类Execl表格控件，可展示上市公司各项数据指标，可自适应单元格大小，根据项目需求自定义freeze的行列数，在性能上做了优化。     
三、IM模块。 实时聊天部分采用MQTT协议实现消息队列，并对聊天消息做持久化保存。    
四、游客模式。   
五、本地HTML热更新功能。    
六、App集成第三方统计、崩溃收集、推送等功能。    

#### 陪你看电影
以电影社交为切入点的社交软件。   
在此项目主要负责了：    
一、实时聊天部分采用MQTT协议实现消息队列。     
二、使用WebViewJavascriptBridge,实现与UIWebView的JS交互。    
三、app性能优化, 通过Instrument定位瓶颈, 优化tableView性能。     

&nbsp;&nbsp;
## 个人作品
####  FrameCamera(https://github.com/ShenLinPing/FrameCamera）   
**一款个人作品，采用纯swift编程，用户可以拍摄照片并生成定格视频，具有可编辑性。**   
主要支持功能有：        
一、绿幕功能。   
使用OpenGL实现，用户可以替换绿幕为自定义背景图片。    
二、贴图功能。   
可以给图片添加自定义贴图、文字和涂鸦等，可自由放大、旋转、翻转。可随时改变贴图层级和去除贴图。     
三、背景音乐功能。    
可以给定格视频添加自定义音频，也可以给定格视频实时录音。    
四、可以调整每张照片在定格视频中的持续时间，可以试看编辑后的视频，生成的视频可保存到本地相册。   

      
&nbsp;&nbsp;
## 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。

