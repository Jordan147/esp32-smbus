# For IDF v4.x:
#idf_component_register(SRCS "smbus.c" INCLUDE_DIRS include)

set(COMPONENT_ADD_INCLUDEDIRS include ${IDF_PATH}/components/driver/i2c/include ${IDF_PATH}/components/driver/gpio/include)
set(COMPONENT_SRCS "smbus.c")
register_component()
