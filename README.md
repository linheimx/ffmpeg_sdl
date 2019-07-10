# ffmpeg_sdl
>可简单配置CMakeLists.txt，来对项目快速的编译。以下提供单个文件的编译命令

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

## tutor4
compile
```
clang -g -o tutor4 tutor4.c `pkg-config --cflags --libs libavformat libavcodec libswscale sdl`
```
run
```
./tutor4 video.mp4
```



