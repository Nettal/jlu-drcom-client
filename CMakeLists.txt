cmake_minimum_required(VERSION 3.30)
project(jlu_drcom_client C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(jlu_drcom_client
        client.c
        client.h
        config.h
        debug_utils.c
        debug_utils.h
        encryption.c
        encryption.h
        logger.c
        logger.h
        main.c
        md5.c
        md5.h
        resend.c
        resend.h)
