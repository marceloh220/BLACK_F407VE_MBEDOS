# Copyright (c) 2021 ARM Limited. All rights reserved.
# SPDX-License-Identifier: Apache-2.0

add_library(mbed-black-f4ve INTERFACE)

target_sources(mbed-black-f4ve
    INTERFACE
        PeripheralPins.c
)

target_include_directories(mbed-black-f4ve
    INTERFACE
        .
)

target_link_libraries(mbed-black-f4ve INTERFACE mbed-stm32f407xe)
