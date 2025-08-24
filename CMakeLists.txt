add_subdirectory(build/cmake)

foreach(t glew glew_s)
  target_include_directories(${t} PUBLIC "include/")
endforeach()
