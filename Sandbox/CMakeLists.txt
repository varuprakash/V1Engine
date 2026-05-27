add_executable(Sandbox Main.cpp)

target_link_libraries(Sandbox PRIVATE Engine)

target_include_directories(Sandbox PRIVATE
    ../Engine/Include
)