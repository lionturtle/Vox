set(INI_SRCS
    "${CMAKE_CURRENT_SOURCE_DIR}/ini.h"
	"${CMAKE_CURRENT_SOURCE_DIR}/ini.c"
    "${CMAKE_CURRENT_SOURCE_DIR}/INIReader.h"
	"${CMAKE_CURRENT_SOURCE_DIR}/INIReader.cpp"
	PARENT_SCOPE)

source_group("ini" FILES ${INI_SRCS})