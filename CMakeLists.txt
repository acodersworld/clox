cmake_minimum_required (VERSION 3.26)

project(clox)

add_executable (clox
	src/main.c
	src/chunk.c
	src/memory.c
	src/debug.c
	src/value.c
	src/vm.c
)
