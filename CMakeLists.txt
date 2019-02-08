cmake_minimum_required(VERSION 3.5)
project(base64)

add_library(
	${PROJECT_NAME}
	STATIC

	include/export/tools/base64.hpp
	src/base64.cpp
)

target_include_directories(
	${PROJECT_NAME}
	PUBLIC
		include/export
)
