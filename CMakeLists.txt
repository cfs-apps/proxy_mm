project(CFE_MM C)
# This file is from https://github.com/cfs-apps/proxy_mm

include_directories(fsw/inc)
include_directories(fsw/src)

aux_source_directory(fsw/src APP_SRC_FILES)

# Create the app module
add_cfe_app(mm ${APP_SRC_FILES})

