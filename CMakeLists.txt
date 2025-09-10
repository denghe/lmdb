add_library(lmdb
    ${CMAKE_CURRENT_SOURCE_DIR}/libraries/liblmdb/lmdb.h
    ${CMAKE_CURRENT_SOURCE_DIR}/libraries/liblmdb/mdb.c
    ${CMAKE_CURRENT_SOURCE_DIR}/libraries/liblmdb/midl.h
    ${CMAKE_CURRENT_SOURCE_DIR}/libraries/liblmdb/midl.c)

target_include_directories(lmdb PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/libraries/liblmdb)
