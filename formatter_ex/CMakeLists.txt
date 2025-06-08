add_library(formatter_ex STATIC
    formatter_ex.cpp
    formatter_ex.h
)

target_link_libraries(formatter_ex PRIVATE formatter)
