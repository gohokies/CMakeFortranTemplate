set(SRCS HelloWorldSample.f90)

set(TGT FortranHelloWorldSample)
add_executable(${TGT} ${SRCS})

target_link_libraries(${TGT} HelloWorldFortran)