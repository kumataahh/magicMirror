# magicMirror
Make a MagicMirror from [![MagicMirror](https://github.com/MichMich/MagicMirror/blob/master/.github/header.png)](https://github.com/MichMich/MagicMirror)

# Finished demo
![finish_demo](https://github.com/kumataahh/magicMirror/.photo/demo.jpg)

# HW List

* Raspberry Pi(supports the Raspberry Pi 2, 3 & 4)

* 液晶屏&驱动板 (随意挑选废弃显示器，Serve for Pi)

* 单向透视镜/原子镜(手工定制)

* 镜框(手工定制)


# SW ENV

#### Pi os install

[Raspberry Pi Desktop](https://www.raspberrypi.org/downloads/)

#### Pi os config
* SSH远程访问

* 无线网络（使用即插即用的 USB 无线网卡则无需配置）

* 更换软件源（国内源工具Download更快）

* 配置系统时间

* 设置屏幕纵向显示（在 /boot/config.txt 文件中添加 display_rotate=1）

* 设置 HDMI 热插拔（在 /boot/config.txt 文件中取消 hdmi_force_hotplug=1 的注释）



# SW Deplory

1. Down and install Node.js

```
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -

sudo apt install -y nodejs
```

2. Project install

```
// Clone the repository
git clone https://github.com/kumataahh/magicMirror

// Enter the repository
cd magicMirror

// Delete the original node_modules
rm -rf node_modules/

// Install the application
npm install
```

3. Add config infos in config.js
    `config/config.js`  申请相应网站的KEY并加入config.js


4. Start the application
```
npm run start
```













