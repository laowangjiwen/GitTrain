project(GITTRAIN)

add_library(L myLib.c)

set(F main.c hello.c)

add_executable(test ${F})

target_link_libraries(test L)
