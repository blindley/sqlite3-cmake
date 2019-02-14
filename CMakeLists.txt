cmake_minimum_required(VERSION 3.0)
project(sqlite3)

add_library(sqlite3 sqlite3.c)

install(TARGETS sqlite3 ARCHIVE DESTINATION lib)
install(FILES sqlite3.h DESTINATION "include/sqlite3")
