# MP3-Player

1-开虚拟环境
.\.venv\Scripts\Activate

2-安装ffmpeg

3-ffmpeg path丢给他
this is my example
$env:Path = "C:\Users\User\AppData\Local\Microsoft\WinGet\Packages\Gyan.FFmpeg_Microsoft.Winget.Source_8wekyb3d8bbwe\ffmpeg-7.1-full_build\bin;" + $env:Path

检查
ffmpeg -version

4-开启
python youtube_to_mp3.py
