
## coursera-dl
1. $ pip3 install coursera-dl
2. go to the working dir and put [coursera-dl.conf](https://github.com/us-upal/download/blob/main/coursera-dl.conf)
3. at working dir $ coursera-dl course_name
Example:
```commandline
$ coursera-dl linear-algebra-machine-learning
```
:::::::>https://www.coursera.org/learn/linear-algebra-machine-learning

                               

## youtube-dl
1. add  [get cookies.txt](https://chrome.google.com/webstore/detail/get-cookiestxt/bgaddhkoddajcdgocldbbfleckgcbcid?hl=en) in the chrome browser extension
2. download youtube-dl.exe || ```$ pip3 install youtube-dl``` ====> official documentation [youtube-dl](https://github.com/ytdl-org/youtube-dl/blob/master/README.md#readme)
3. go to working dir
4. cookies.txt to the workingDir
5. run CMD as admisistrator or in zsh:
```commandline
youtube-dl --download-archive archive.txt --cookies cookies.txt -o "(playlist_index)s - %(title)s.%(ext)s" https:www.YourCourseURL.com --playlist-start 1 --all-subs -f "best[height=720]"
```

Example:
```commandline
youtube-dl --download-archive archive.txt --cookies cookies.txt -o "%(playlist_index)s - %(title)s.%(ext)s" https://www.lynda.com/Android-tutorials/Android-App-Development-Data-Persistence-Libraries/540500-2.html --playlist-start 1 --all-subs -f "best[height=720]"
```


