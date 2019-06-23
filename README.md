# ffmpeg_sdl
## tutor1
compile 
```
clang -g -o tutor1 tutor1.c `pkg-config --cflags --libs libavformat libavcodec libswscale`
```
run 
```
./tutor1 video.mp4
```

## tutor2
compile 
```
clang -g -o tutor2 tutor2.c `pkg-config --cflags --libs libavformat libavcodec libavutil libswscale sdl`
```
run 
```
./tutor2 video.mp4
```

## tutor3
compile 
```
clang -g -o tutor3 tutor3.c `pkg-config --cflags --libs libavformat libavcodec libswscale sdl`
```
run 
```
./tutor3 video.mp4
```





