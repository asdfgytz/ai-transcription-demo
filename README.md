# ai-transcription-demo

上字幕(不包含翻譯)

使用 openAI API


## Introduction
所有code都存在 test.ipynb裡面

全長影片來源是存取: 
https://miru.v.anime1.me/1361/24.mp4

1分鐘片段是擷取: 3:51 to 4:48


## Detail

note: client = OpenAI(api_key='your_key')


1-min_segment.txt: 1-min.mp3的日文字幕


25MB_up.txt: 完整影片的日文字幕(還需要優化)

這個目的是測試 openAI API 無法接收 > 25MB file
而的確也不行(test.ipynb裡面可以看到error code)

## Note

client = OpenAI(api_key='your_key')

這個需要自己create a key from openAI


