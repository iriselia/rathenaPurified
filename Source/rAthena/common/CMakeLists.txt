cmake_minimum_required( VERSION 2.8 )

# Preprocessor Definitions
SET( MACROS
MINICORE
)
SET( INCLUDE
libconfig
msinttypes
mt19937ar
mysql
pcre
zlib
)
SET( LINK
libconfig
msinttypes
mt19937ar
mysql
pcre
zlib
)

create_project(STATIC "${MACROS}" "${INCLUDE}" "${LINK}")
