# SPDX-License-Identifier: Apache-2.0

cmake_minimum_required(VERSION 3.21)
# Subdirectories
add_subdirectory(drivers)

# Include headers
zephyr_include_directories(drivers)