cmake_minimum_required(VERSION 3.17)
project(curlEjemplo)

set(CMAKE_CXX_STANDARD 14)

add_executable(curlEjemplo main.cpp)

set(libcurl_INCLUDE_DIR "C:/Users/dell/CLionProjects/curlEjemplo/lib/curl-7.77.0-win64-mingw/include")
include_directories(${libcurl_INCLUDE_DIR})
target_link_libraries(curlEjemplo C:/Users/dell/CLionProjects/curlEjemplo/lib/curl-7.77.0-win64-mingw/lib/libcurl.dll.a)
