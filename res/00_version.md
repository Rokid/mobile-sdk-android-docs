#  版本更新信息

* v1.10.1

    [新增] 基础模块 - 支持通过 maven 直接引入 SDK
    
* v1.10.0

     [新增] 账户模块 - 增加用户信息获取和更新接口<br>
     
     [修改] 账户模块 - 注册接口取消 `accessKey` 入参
     
     [修改] 基础模块 - 日志优化
     
* v1.9.0

     [修改] 媒体模块 - `RokidMobileSDK.media.requestListIntent`接口增加`linkUrl`参数<br>
     [新增] `SDK`初始化增加对`appKey`、`appSecret`、`accessKey`对校验逻辑<br>
     [新增] 媒体模块 - 增加酷狗登录H5支持<br>
     
* v1.8.1

     [修复] BUG修复
     
* v1.8.0

     [新增] 媒体模块 - 三方账号授权增加酷狗音乐登录支持<br>
     [新增] 账号模块 - 增加新的获取验证码接口以支持传入国际区号<br>
     [新增] 账号模块 - 验证码长度由4位更新为6位<br>

* v1.7.0

     [修复] BUG修复

* v1.6.5

     [新增] 设备模块 - SDKDevice增加ssid（当前设备连接wifi）<br>
     [新增] 设备模块 - 增加获取YodaOS系统设备在线状态接口<br>
     [修复] 设备模块 - 获取设备地理位置信息无数据返回修复<br>

* v1.6.3

     [修复] 取消 D8 编译，兼容旧版本gradle<br>

* v1.6.1

    [新增] Skill模块 - 云闹钟 列表获取、新增、删除、更新。<br>
    [新增] Skill模块 - 云提醒 列表获取、删除<br>

* v1.6.0

    [新增] 设备模块 - 设备音量设置、获取<br>
    [新增] 媒体模块 - 授权媒体 Skill 列表<br>
    [新增] 媒体模块 - 获取媒体 首页、列表、详情页信息<br>
    [新增] 媒体模块 - 媒体内容点播、暂停、继续播放、上一首、下一首<br>
    [新增] 媒体模块 - 三方账号授权API<br>
    [新增] 账号模块 - 新增重置密码接口。<br>
    [删除] 设备模块 - 设备基本信息(base_info) 调整到 SDKDevice 中 <br>
    [删除] protobuf 依赖库<br>
    [修复] 设备模块-恢复出厂设置 消息<br>
 
* v1.3.1

    [新增] 账号模块 - 若琪自有账号体系 注册相关接口。<br>
    [修改] 账号模块 - 开发者自有账号体系 登录接口。

* v1.3.0

    [新增] 绑定模块 - 蓝牙 2.0 配网协议，配网过程中 设备状态的判断

* v1.2.1
    
    [修复] 断网后，长连接没有正常连接问题。
    [新增] SDKChannelMessage 长连接全部消息。<br>
    [新增] 设备自定义信息存储、获取

* v1.2.0
    
    [优化] SDK 长连接 稳定性

* v1.0.11

    [新增] SDKMediaEvent 内容播放消息

* v1.0.9

    [新增] Vui sendMessage接口

* v1.0.8

    [新增] Bridge goBack 接口 <br>
    [优化] Bridge 加载速度，SDKWebClient 改为 SDKWebChromeClient <br>
    [修复] Skill 闹钟 ext 字段丢失 <br>
    [修改] Account token login
    [新增] Skill-闹钟\提醒 获取列表 回调 <br>
    [优化] Skill-闹钟\提醒 重复模式 解释
    
* v1.0.7 
    
    [新增] Web Bridge 接入说明

* v1.0.6
    
    [新增] 闹钟、提醒 skill 接口

* v1.0.5
    
    [新增] DeviceTypeId、Token、Debug

* v1.0.4

    [新增] 用户单独登录、系统更新 Event

* v1.0.3

    [删除] 刷新 Token 接口<br>
    [新增] Device 一些接口的返回值

* v1.0.2 
    
    [新增] Token 登录<br>
    [新增] 刷新 Token 接口

* v1.0.1 

    [新增] Card 协议解释

* v1.0.0 
    
    [新增] Rokid Mobile SDK 初版



