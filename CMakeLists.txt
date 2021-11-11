cmake_minimum_required (VERSION 3.8)
project (regex_project)

include_directories(
	${CMAKE_CURRENT_SOURCE_DIR}
)

add_executable (vs_project "src/utf8-CR.cc")
