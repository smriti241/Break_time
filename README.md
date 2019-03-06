# Break_time
Giving a break after some time and playing a video(Python)
import webbrowser
import time
print("This program started at:"+time.ctime())
i=0
while(i<3):
    time.sleep(10)
    webbrowser.open("https://www.youtube.com/watch?v=zmr2I8caF0c")
    i=i+1
