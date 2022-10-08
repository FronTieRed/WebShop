cmake_minimum_required(VERSION 3.23)
project(WebShop)

set(CMAKE_CXX_STANDARD 14)

include_directories(WebShop/src/backend/Basket)

add_executable(WebShop
        WebShop/src/backend/Basket/basket.cpp
        WebShop/src/backend/Basket/basket.h)
