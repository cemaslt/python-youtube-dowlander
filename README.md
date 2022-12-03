# Python YouTube Video Dowlander
    - Basic YouTube Video Dowlander.


# Kurulum

- Python indirildikten sonra , komut sistemini açıp [ pip install pytube ] pytubeyi indiriyoruz.



# Kodlama

```py
from pytube import YouTube
link = input("Link: ")

yt = YouTube(link)
ys = yt.streams.get_highest_resolution()

print("Video İndiriliyor.")
ys.dowland()
print("Video İndirildi.")

```

> Kolayca youtube videolarını indirebilirsiniz.
