file( GLOB SRC *.cpp )
file( GLOB HDR *.h )
#
add_executable( app ${SRC} ${HDR} )
#