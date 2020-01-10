# 博物馆AR导览PRD文档
## 智能APP名称：博览
### 价值主张写作
一句话版本：博览使用AR技术为用户设计观展路线，增加展览的互动感，实现最佳观展体验。

一分钟版本: 将场景感知、人脸人体特效的AR交互能力融入展区环境，提供兼具娱乐性与交互性的AR互动方案，例如为观众提供试衣体验。或者结合人像抠图功能，把人脸抠到穿古装的人身上，结合展区导览等AI功能，持续提升用户在展区的一体化体验。

### 1. 加值宣言
- AR导览能够为参观者提供沉浸式的观展体验，增加展览的交互性与参与感
- AR为博物馆赋能，提升展览与博物馆的吸引力，吸引更多年轻的参观者，更好地实现博物馆的科教与娱乐目的。
- 展馆数字化利于多平台多渠道展示与展品信息的数字化保存。通过网络覆盖更多样化的群体提升知名度与受众

### 2. 核心价值宣言
该产品使用场景为博物馆，主要针对了三种目标用户：休闲旅客、知识获取型旅客、专家型旅客。当他们不了解博物馆内路线或在游览时不了解文物背后的故事而感到枯燥时，他们即可使用该产品来分别实现展区内AR步行导航{通过AR实时导航让游客去到自己想去的地点游览}、线上导览（即提前了解展区主题与展品速览）、线下互动（通过AR交互提供给用户兼具游戏与沉浸式交互的游览体验）

### 3. 用户痛点
- 在博物馆中经常迷路，不知道怎样参观比较精彩
- 展品介绍看不懂，展品的展现方式比较枯燥，无法引起游客兴趣
- 互动感不足，游客无法和展览和展品产生联系

### 4. 目标用户
以用户需求分类：
- 休闲观光型游客---此类游客一般为了消遣游乐，没有明确目的，也抱着打卡到此一游的心态，故对于博物馆结构与内部路线并不熟悉。
- 增长见识型游客---此类游客抱着学习新知识的心态游览，对展品相关信息及相关知识科普的需求较高。
- 专家型游客---此类游客对博物馆的构造及馆藏文物有较深入的了解，出于更加深入研究目的进行观览。

### 5. 用户需求列表
***
用户案例 | 对应标题 |  重要程度
-|-|-
用户刚到博物馆时，可以用这个APP找到一条帮他置顶好几个浏览地点的路线。| 路线规划、地理编码、图像识别 | 重要 |
用户来到文物前，通过扫描文物获取更多文物相关信息。对文物了解程度不同的用户都可从中获得自己想要的信息。| 图像识别| 次重要|
参观者想与博物馆展品产生一定的联系——与历史人物进行人脸融合| 人脸融合 | 次重要 |


### 6. 效益成本分析
#### 成本分析：
（1）技术成本：
开发与维护成本：
开发各系统移动端（IOS、安卓）可用的APP与小程序的费用
对博物馆内的展品进行数字化与数据化（用于图像识别的机器学习）的费用
对于程序的迭代和服务升级所需要的持续研发与维护费用

该成本包括对该程序的设计、开发、雇用技术咨询人员安装和运行软件的成本。

（2）运营成本
在博物馆各处设置AR提示牌与AR识别区
租用云端服务器或是调用API后必须发生的各种支持服务费用。

（3）风险成本：APP被黑客攻击导致数据泄露


### 7. 功能介绍

1. 线上导览——用户拿起手机点开广东省博物馆APP，点击“扫一扫”功能，调用手机的摄像功能，对准不同场馆的门口标识区后，结合2D图像跟踪——通过扫描识别图调起AR，会自动在屏幕上显示该展区的展览主题与展品速览，以AR全景图片、视频形式将展区场景体验前置，带领用户身临其境领略不同展区的文化风采。当用户进入展区内浏览时，使用手机摄像头对准展品，通过扫描识别展品调起AR，会自动播放有关展品的音频资料以及显示展品相关的图像文字，详细地介绍展品的前世今生所经历的风风雨雨，能更好的为用户进行展品科普教育。

2. 场地AR步导——将视觉定位与增强服务（VPAS）融入百度地图场景化解决方案，为用户提供展区内的场景实时步行导航，使用户能够实现拿着手机就能自助游览不迷路，清晰了解自己所处的位置不茫然。并且还能为用户规划不同导览路线的功能，丰富用户在展区的体验感。结合展区导览等AI功能，持续提升用户在展区的一体化体验。

3. 线下互动——将场景感知、人脸人体特效的AR交互能力融入展区环境，提供兼具娱乐性与交互性的AR游戏互动方案，例如为观众提供试衣体验。或者结合人像抠图功能，把人脸抠到穿古装的人身上，增强用户对衣服配饰类展品的了解度以及体验感。
（所需要的API：2D图像跟踪；AR物体识别；AR动画ARAnimationController；AR多媒体ARMediaController；AR-UserInteraction；人像抠图）


### 8. 功能总览流程图
![功能总览流程图](https://gitee.com/NFUNM171036008/API_img/blob/master/%E5%8A%9F%E8%83%BD%E6%B5%81%E7%A8%8B.png)

### 9. APP原型和功能展示
![原型](https://gitee.com/NFUNM171036008/API_img/blob/master/%E5%8E%9F%E5%9E%8B.png)

