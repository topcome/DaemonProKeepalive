# DaemonProKeepAlive   请下载最新安装包
2023持续全网最新！！！ Android平台进程保活技术DaemonProcess  保活，APP保活，app保活，Android保活，安卓进程保活，Android进程保活      
1：支持国内android7-12，国外7-13版本进程保活  
2：支持厂商，google原生系统，三星，OPPO,vivo,小米，华为，pixel  
3：支持无权限后台打开activity即后台弹窗  
4：支持图标隐藏功能  
5：支持厂商系统级APP拉活功能    
6：支持无权限自启动，安装立即启动无需手动打开（需一定时机条件），支持设备重启拉活，及重启不受影响，部分品牌重启需要一定时间才会自启动，不会立即自己启动  
7：联系微信：nickme521  
8：最新体验下载链接，（体验包支持到2023-06-15 11:00:21 过期无效！！！！！！！！！):https://dameonprokeepalive.oss-cn-hangzhou.aliyuncs.com/test/DaemonKeepalivePro40_c.apk           
   
   
 测试注意：  
   ★一定要联网，一定要联网，一定要联网（否则会一直崩溃）,海外设备请打开VPN代理连上国际网络（功能需要用到GMS服务，因此需要联网）！！！！！！！！！！！！  ，程序定时触发后台打开activity事件    
   ★ 1： adb shell  2： ps -A|grep com.pdd.sandroiddsa.actsp    (使用命令行查看进程是否存在)   
   ★部分机型功能需要单独打包，此包只展示强杀进程模式，对于重启设备拉活进程需要单独打包 ,国外设备不受限制     
   ★海外设备在android13中杀死进程后会在大约30s-1分钟左右重启进程   
   ★反馈问题：请描述设备机型，版本等参数    
   ★不支持虚拟机（没有编译x86架构）  
     
      
 2023/4/22 更新记录：修复了一些无关紧要的bug         
 2023/4/6 更新记录：新增一种进程保活机制，此机制由系统处理，无法主动控制，在海外设备测试中效果不错   
 2023/3/7 更新记录：1：新增一种针对海外android13系统的体外弹窗功能，无需申请任何权限即可通过API后台打开Activity（目前海外市场暂时没看到能做到，也许是我没看到）,几乎适配所有海外13版本设备（测试注意：海外版本保活机制采用拉活，表现为在强行杀死进程后，在一分钟以内进程即可自动恢复）   
 2023/3/2 更新记录：1：针对google13版本新增一种体外弹窗功能（需要给通知权限），同时可以为13以下版本版本的体外弹窗有更强的稳定性 2：增强以函数粒度的混淆程度包含java层，native层   
 2023/2/15 更新记录：1：完善gooogle原生保活拉活机制，适配android13，2：大幅优化进程性能消耗（java写的部分核心业务也由c++实现，也提升了不少性能损耗）3：重构了部分SDK源码，保持代码整洁    
 2022/12/30更新记录：完善google机型部分卡顿问题  
 2022/12/20更新记录：修复findclass异常提示报错问题  
 2022/12/10更新记录：增强进程保活能力  
 2022/10/7更新记录：增加系统app拉活能力，当进程死亡时打开任意系统app即可重新拉起目标应用    
 2022/9/28更新记录：so层增加ollvm混淆   
 2022/9/21更新记录：实现oppo开机自启动   
 ....
