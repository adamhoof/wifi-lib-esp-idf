idf_component_register(SRCS "wifi-lib.c"
                    INCLUDE_DIRS "include"
                    REQUIRES esp_wifi nvs_flash freertos lwip)
