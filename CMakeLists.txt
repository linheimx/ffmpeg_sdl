cmake_minimum_required(VERSION 3.14)
project(ffmpeg_sdl C)

find_package(PkgConfig)
pkg_check_modules(NEED libavformat libavcodec libswscale sdl)
message(---)
message(include dir:${NEED_INCLUDE_DIRS})
include_directories(${NEED_INCLUDE_DIRS})
message(lib dir:${NEED_LIBRARY_DIRS})
link_directories(${NEED_LIBRARY_DIRS})
message("lib:${NEED_LIBRARIES}")

add_executable(ffmpeg_sdl tutor5.c)
target_link_libraries(ffmpeg_sdl ${NEED_LIBRARIES})
