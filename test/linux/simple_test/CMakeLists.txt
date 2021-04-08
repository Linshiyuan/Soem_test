
set(SOURCES simple_test.c)
add_executable(simple_test ${SOURCES})
target_link_libraries(simple_test soem)
install(TARGETS simple_test DESTINATION bin)

add_executable(r1 r1.c)
target_link_libraries(r1 soem m)

add_executable(r2 r2.c)
target_link_libraries(r2 soem m)