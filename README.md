Development——AX6_AX3600_AX9000开发版
lean已删除AX9000相关！所以AX9000开发板将只是插件的更新！

基于OPenwrt官方源：https://github.com/yaya131/RedMi-AX6-NSS  AX6-nss加速！无线没有！
2023-01-05：蓝奏云网盘更新基准以测试使用15天无问题才会更新，由于群与TG随缘看，仅交流。暂无添加插件的计划。蓝奏云网盘随缘更新！所有更新以Github为主！     无NSS的5.10.100的AX6及AX3600相关编译移至全能版块！具体看介绍！

新增5.10内核主线的更新：特色，NSS，最新内核，最新插件，日更！

AX6-AX3600-AX9000测试项目地址：https://github.com/yaya131/LEDE-XiaoMi-Test

源编译的固件特别说明：

源码切换至5.10.143最后一版稳定版！

管理地址：192.168.10.1

登陆密码：password

无线密码：1234567890

激进，快速，稳定.层次逻辑更清晰

20210927精简了部分特小众的插件
# 添加红米ax6 编译选项
    - name: Redmi ax6  ax3600 support
      run: |
        cat $GITHUB_WORKSPACE/generic.mk >> openwrt/target/linux/ipq807x/image/generic.mk



        
包含：

纯净ap=====精简插件SCJ======全插件DCJ

集成的插件：
#IPv6
#简单组网
#科学ssp（全组件）

#小猫咪
#smartdns
#去广告plus
#云音乐
#流控

#ttyd
#zerotier
#Turbo ACC
#访客网络

#全能推送
#openclash
#jd签到
#多拨&负载均衡

等等

##如有不想要的插件，需要自定义
请移至我的这个 https://github.com/jingleijack/AX6-AX3600_Almighty-Edition_Config
在.config文件里找到相应的插件名称删除即可##
节约资源从我做起！
直接下载我的最新版本即可。
刷机尽可能不保留配置刷入
