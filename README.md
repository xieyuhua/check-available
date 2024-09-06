# tvbox 直播源 m3u8 批量检测程序(目前仅支持.txt格式)

## 将待检测的直播源文件放置到playlists/文件夹下：

支持在线直链（如raw.githubusercontent.com，gitee.com/*/raw/等，可添加多个），自动下载至playlists/文件夹，文件名相同则直接覆盖（类似自动更新）
```
支持检测多个在线.txt文件
# py main.py http://a.txt https://b.txt http://c.txt
会保存到/playlists目录中，文件名自动截取为url中最后一个'/'后的所有字符，覆盖同名文件
```


## 使用方法

本项目基于 **python3.7** 进行开发 

- 模块安装 Requirements
```
pip3 install pandas
pip3 install requests
pip3 install DingtalkChatbot -i https://pypi.tuna.tsinghua.edu.cn/simple
pip3 install openpyxl
pip3 install pyinstaller -i https://pypi.tuna.tsinghua.edu.cn/simple

pyinstaller --onefile main.py
```

## todo 


