add_executable(TextEncodingConvert MainUnit.cpp)

target_link_libraries(TextEncodingConvert CMCore CMPlatform CMUtil)

set_property(TARGET TextEncodingConvert PROPERTY FOLDER "CM/Tools/Text")