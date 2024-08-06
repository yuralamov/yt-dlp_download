Качалка yt-dlp

Собственно

https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp.exe

Загрузчик

https://github.com/aria2/aria2/releases/tag/release-1.37.0

ffmpeg

https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-full.7z

Скачиваем, распаковываем

В каталоге с yt-dlp создаем yt-dlp.conf

Или в командной строке

D:\Apps\yt-dlp\yt-dlp.exe  --ffmpeg-location D:\Apps\ffmpeg-full_build\bin\ffmpeg.exe --downloader D:\Apps\aria2-64bit\aria2c.exe --merge-output-format mp4 --paths D:\Desktop https://урла_ролика_или_плейлиста
