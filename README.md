# bf_record_search
基于[HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot)的战地1战绩查询插件，以图片形式呈现

主要功能为查询总体战绩和详细战绩，目前仅可查询战地1战绩

命令1：`xxx战绩`  xxx为有效的玩家origin id

命令2：`xxx 武器or载具or模式or职业数据` 查询更加详细的数据，注意空格

# 后续更新计划

- [ ] 战地5的战绩查询
- [ ] 对武器载具等名称的汉化
- [ ] 增加绑定id功能，不用每次查询时都输入origin id


# 在部署前需要注意
- 本项目需要用到的字体文件，不会在项目文件中提供，需自行提供。本项目默认使用的是微软雅黑细体，可在原生windows的C:\Windows\Fonts目录下找到，并将对应文件复制到和本项目文件同目录下。
- 如果你不喜欢本项目自带的背景图，也可以自定义背景，自定义背景需要`1920*1080`分辨率或者等于此比例的图片。自定义的背景在更换完后可重启bot重新生成也可通过命令生成。（考虑到大多数bot是部署在云服，我将插件所需的两个背景设置成事先生成好，这样可以节省对服务器内存的占用，提高bot的响应速度）
- 插件的注释中写了更多详细内容以及使用方法，可自行阅读

# 部署
下载本项目，并在HoshinoBot\hoshino\modules目录下新建一个bf_record_search文件夹，将项目文件扔进去，然后在HoshinoBot/hoshino/config/\_\_bot\_\_ .py中的MODULES_ON中添加'bf_record_search'

HoshinoBot的部署方法详见[HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot)
