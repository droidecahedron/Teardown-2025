cmake_minimum_required(VERSION 3.20.0)
find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})

project(Teardown-2025)

target_sources(app PRIVATE src/main.c)
