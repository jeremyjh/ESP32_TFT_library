FILE(GLOB SOURCES *.c)
idf_component_register(SRCS ${SOURCES} INCLUDE_DIRS "."
                       REQUIRES vfs spi_flash)
