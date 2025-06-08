add_executable(solver
    main.cpp
)

target_link_libraries(solver PRIVATE formatter_ex solver_lib)
