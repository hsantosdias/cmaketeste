cmake_minimum_required(VERSION 3.10)

# Nome do projeto
project(MeuProjeto)

# Defina o padrão do C++ (opcional, mas recomendado)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Adicione o executável
add_executable(MeuProjeto src/main.cpp)
