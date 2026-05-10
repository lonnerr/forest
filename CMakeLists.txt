cmake_minimum_required(VERSION 3.13)

project(Forest)

find_package(SFML COMPONENTS window graphics REQUIRED)

add_executable(Forest
    main.cpp
    Sundew.cpp
    Sparrow.cpp
    Plant.cpp
    Penguin.cpp
    Mushroom.cpp
    Lion.cpp
    Herbivore.cpp
    Forest.cpp
    Flower.cpp
    Fish.cpp
    Creature.cpp
    Cow.cpp
    Cat.cpp
    Carnivore.cpp
    Animal.cpp
)

target_link_libraries(Forest PRIVATE sfml-window sfml-graphics)

install(TARGETS Forest)
