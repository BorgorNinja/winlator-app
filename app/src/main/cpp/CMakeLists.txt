cmake_minimum_required(VERSION 3.22.1)

# Ensure 16 KB page size alignment for Android 15+ kernels
add_link_options("-Wl,-z,max-page-size=16384")

add_subdirectory(winlator)
add_subdirectory(vortekrenderer)
add_subdirectory(virglrenderer)
add_subdirectory(midihandler)
add_subdirectory(libadrenotools)
add_subdirectory(gladiorenderer)