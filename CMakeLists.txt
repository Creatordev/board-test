# Project Properties
####################
CMAKE_MINIMUM_REQUIRED (VERSION 2.6.2)

PROJECT(board_test)
SET(board_test_VERSION_MAJOR 1)
SET(board_test_VERSION_MINOR 0)
SET(board_test_VERSION_PATCH 0)
SET(board_test_VERSION
    ${board_test_VERSION_MAJOR}.${board_test_VERSION_MINOR}.${board_test_VERSION_PATCH})

ADD_SUBDIRECTORY(src)
