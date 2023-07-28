idf_component_register(
    SRCS "template.c"         # list the source files of this component
    INCLUDE_DIRS "./include"        # optional, add here public include directories
    REQUIRES driver  esp_adc       # optional, list the public requirements (component names)
)
