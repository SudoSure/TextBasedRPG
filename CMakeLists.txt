CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
SET(CMAKE_CXX_STANDARD 11)

ADD_EXECUTABLE(rpg
    main.cpp
    GameHandler.cpp
    CurrentState.cpp
    Player.cpp
    PlayerClass.cpp
    )
