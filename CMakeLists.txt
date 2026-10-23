cmake_minimum_required(VERSION 3.11)

add_subdirectory(EASTL)

export(TARGETS EABase EASTL NAMESPACE EASTL::)