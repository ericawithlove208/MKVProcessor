
add_executable(MKVProcessor main.cpp)


# Dependencies of this library
target_link_libraries(MKVProcessor PRIVATE 
    k4a
    k4abt
    k4arecord
    pthread
    )


