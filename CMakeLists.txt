cmake_minimum_required(VERSION 3.0.0)
project(VulkanTutorial)

FILE(GLOB_RECURSE sources src/*)
add_executable(executable ${sources})

target_link_libraries(executable PRIVATE glfw vulkan)
