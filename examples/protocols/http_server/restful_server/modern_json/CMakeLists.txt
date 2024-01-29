# idf_component_register(SRCS "cJSON/cJSON.c"
# "cJSON/cJSON_Utils.c"
# INCLUDE_DIRS cJSON)

add_library(modern_json STATIC cJSON/cJSON.c cJSON/cJSON_Utils.c)

target_include_directories(modern_json PUBLIC cJSON)
