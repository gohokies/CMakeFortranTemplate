set(TGT HelloWorldFortran)

set(SOURCES
    HelloWorld.f90
    )

add_library(${TGT} SHARED ${SOURCES})

set_property(TARGET ${TGT} PROPERTY POSITION_INDEPENDENT_CODE ON)
