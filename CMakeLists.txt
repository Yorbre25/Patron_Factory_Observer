cmake_minimum_required(VERSION 3.17)
project(Tarea2_DatosII)

set(CMAKE_CXX_STANDARD 14)

include_directories(Factory)
include_directories(Factory/Golosinas)

add_executable(Tarea2_DatosII
        Factory/Golosinas/Almendras.cpp
        Factory/Golosinas/Bombon.cpp
        Factory/Golosinas/Botoneta.cpp
        Factory/Golosinas/Golosina.cpp
        Factory/Golosinas/Golosina.h
        Factory/Golosinas/ManiSalado.cpp
        Factory/Factory.h
        Factory/FactoryDulce.cpp
        Factory/FactoryDulce.h
        Factory/FactorySalada.cpp
        Factory/FactorySalada.h
		Observer/Periodico.cpp Observer/Classes.h main.cpp Observer/Suscriptor.cpp)

