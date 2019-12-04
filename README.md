# raspberrylive
A tool which can play videos on Live site by raspberry

一个树莓派用的直播工具


首先安装ffmpeg（FFmpeg可以运行音频和视频多种格式的录影、转换、流功能[1]，包含了libavcodec——这是一个用于多个项目中音频和视频的解码器库，以及libavformat——一个音频与视频格式转换库）
sudo apt install ffmpeg

安装qt（Qt是一个跨平台的C++应用程序开发框架。）
sudo apt install qt5-default qtcreator

下载源代码
git clone https://github.com/suntaobuaa/raspberrylive

cd /raspberrylive

qmake

make
即可

或者用qtcreator打开.pro.user 文件  编译运行

电视剧模式，自动顺序播放文件夹下所有视频文件，不支持字幕功能，如需字幕，必须视频自带硬字幕



目前源码中电影模式添加了在线下载字幕功能，参见https://github.com/qzane/SPlayerSubDownloader

注意须将getsrt.py文件拷到可执行文件目录。









