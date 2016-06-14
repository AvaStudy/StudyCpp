###############################################################################
#helloworld
set(PROJECT_NAME "helloworld")
set(PROJECT_SOURCES
    main.cpp
    )

include_directories(${CMAKE_CURRENT_SOURCE_DIR})

add_executable(${PROJECT_NAME}
  ${PROJECT_SOURCES}
  )
