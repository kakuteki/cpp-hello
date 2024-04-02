cmake_minimum_required(VERSION 3.0)
project(HelloWorld)

# C++の標準バージョンを設定します。例えば、C++11, C++14, C++17等
set(CMAKE_CXX_STANDARD 11)

# 実行ファイルを生成するためのソースファイルを指定します。
add_executable(HelloWorld main.cpp)
