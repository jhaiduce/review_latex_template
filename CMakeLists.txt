cmake_minimum_required(VERSION 3.17.1)

project(2024JA033606_0_review LANGUAGES)

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${PROJECT_SOURCE_DIR}/UseLatexMk")

include(UseLatexMk)

add_latex_document(SOURCE review.tex)
