cmake_minimum_required(VERSION 3.15)

project(mctrd
  VERSION
    1.0
  DESCRIPTION
    "Command line tool for add/extract files from .scl and .trd images"
  LANGUAGES
    C)

add_executable(mctrd main.c)
