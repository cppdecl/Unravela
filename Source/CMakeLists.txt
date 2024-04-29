cmake_minimum_required(VERSION 3.15)

add_executable(
    ${PROJECT_NAME} 
    SHARED 
    
    Main.cc
)


target_link_libraries(${PROJECT_NAME} PUBLIC 
    ${CMAKE_THREAD_LIBS_INIT}
)

target_include_directories(${PROJECT_NAME} PUBLIC .)