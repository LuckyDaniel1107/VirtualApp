### VirtualApp
专注用 Xposed 实现游戏、电商等应用 xposed 插件
1、Xposed VA  VirtualApp

韩国游戏过盾
# 1、永恒之塔2 
    a、永恒2 默认带有dex 保护、逆向前请优先移除dex 保护
    b、游戏启动的时候开启Guard 保护、我们启动的时候移除Guard 即可
# 2、尤弥尔
    a、这个游戏比较特殊，他很多字符都放到了底层去做加密解密 所以我们需要对GuardEngine 进行hook
    b、由于hook 了GuardEngine 后破坏了游戏的正常启动逻辑所以需要手动去扫描启动部分组件 com.google.firebase.components.ComponentDiscovery.discover

Telegram:https://t.me/lucky_daniel1107
Email   :lucky.daniel1107@gmail.com
