cmake_minimum_required(VERSION 3.5)
project(stb)

add_library(stb STATIC 
include/stb/stb_image.h 
include/stb/stb_rect_pack.h 
include/stb/stb_rect_pack.h 
include/stb/stb_truetype.h 

src/stb_image.c
src/stb_rect_pack.c
src/stb_rect_pack.c
src/stb_truetype.c
)

target_include_directories(stb PUBLIC include)
