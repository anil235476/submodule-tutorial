cmake_minimum_required(VERSION 3.7)

add_executable(tutorial 
main.cpp
)

find_path(FUNCTION_CALLER_THREAD2 ...)
message("going to check condition")
if((NOT FUNCTION_CALLER_THREAD2) OR (NOT EXISTS ${FUNCTION_CALLER_THREAD2}))
message("Unable to find function caller")
endif()