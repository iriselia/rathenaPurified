cmake_minimum_required( VERSION 2.8 )

# Preprocessor Definitions
SET( MACROS
LIBCONFIG_STATIC
)
SET( INCLUDE
zlib
)
SET( LINK
zlib
)

create_project(STATIC "${MACROS}" "${INCLUDE}" "${LINK}")
