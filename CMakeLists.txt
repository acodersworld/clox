cmake_minimum_required (VERSION 3.26)

project(clox)

set(CMAKE_BUILD_TYPE Debug)

add_executable (clox
	src/main.c
	src/chunk.c
	src/memory.c
	src/debug.c
	src/value.c
	src/vm.c
	src/scanner.c
	src/compiler.c
	src/object.c
)
