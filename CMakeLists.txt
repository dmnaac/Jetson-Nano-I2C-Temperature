cmake_minimum_required(VERSION 2.8)

project(jetson_i2c_temperature)

add_executable(jetson_i2c_temperature i2c_temperature.cpp i2c.c)
