cmake_minimum_required(3.1)

set(CMAKE_CONFIGURATION_TYPES Debug)

project(ogl2dr)

set(CMAKE_CXX_STANDARD 11)

FetchContent_Declare(
    glfw
    GIT_REPOSITORY https://github.com/glfw/glfw.git
    GIT_TAG 3.3.7
)
FetchContent_MakeAvailable(glfw)