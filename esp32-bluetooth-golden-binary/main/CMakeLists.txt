idf_component_register(SRCS "controller_hci_uart_demo.c"
                    PRIV_REQUIRES bt nvs_flash esp_driver_uart esp_coex esp_phy esp_rom
                    INCLUDE_DIRS ".")
