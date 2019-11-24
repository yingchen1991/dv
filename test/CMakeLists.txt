set( SAMPLE_NAME test1 )
add_executable( ${SAMPLE_NAME} test.cpp glew.c)
target_link_libraries( ${SAMPLE_NAME} ${BINARY_FILES} )
add_dependencies( ${SAMPLE_NAME} glfw ${COPY_BINARY} )