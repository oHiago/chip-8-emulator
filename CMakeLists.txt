cmake_minimum_required(VERSION 3.31.11)
project(Emu LANGUAGES CXX)
add_executable(emu
    main.cpp
    src/emu.cpp
)
target_include_directories(emu PRIVATE src)
target_compile_features(emu PRIVATE cxx_std_17)