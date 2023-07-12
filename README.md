# Vision Hub 使用手册

主页地址： https://applevisionhub.net \
PC移动端服务站点地址：https://visionhub.top （目前使用）\
安卓App（部分功能存在异常，如无法换头像）： <a href="https://github.com/k1287988804/visionhubdocs/releases/download/v1.0.0/VisionHub_1.0.0_release.apk" target="_blank" >VisionHub</a> \
VisionTool：https://github.com/k1287988804/VisionTool

@author：K启源 B站/爱发电同名

#### 现有功能：

##### 全局设置面板 
支持设置自己头像、设置聊天主题色、语言、字体 \
支持切换聊天频道、支持使用自定义claude工作区 \
支持配置全局模板：Jailbreak Prompt、Main Prompt、NSFW Prompt 示例DEMO（可sese）：<a href="https://github.com/k1287988804/visionhubdocs/blob/main/18template.md" target="_black">DEMO</a> \
支持配置stable diffusion远程地址，可使用秋叶整合包搭建Colab版本无缝衔接 （默认备选地址较慢，白嫖的接口） \
支持配置vits语音地址，兼容vits-simple-api项目 （默认备选地址较慢，白嫖的接口）

##### 角色对话面板
支持设置角色预设对话、支持设置角色头像、设置角色名称、设置自己名字 \
支持对接sd面板 \
支持对接vits套用角色语音 

##### 幻象大厅
支持自定义角色幻象（对话、头像、形象、声音）、支持导入导出幻象

##### 使用本地SD绘图的方法：
地址填入：http://localhost:7860   支持秋叶启动器
###### sd的启动命令要加--api和--cors-allow-origins '*' 
如：\
--medvram --autolaunch --xformers --theme dark --no-half-vae --api --cors-allow-origins '*' --listen --port 7860





