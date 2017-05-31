# Build all SeetaFace libraries to lib directory

cmake_minimum_required(VERSION 2.8.4)

project(seeta_face_engine)

set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_CURRENT_BINARY_DIR}/lib)

add_subdirectory(FaceDetection)
add_subdirectory(FaceAlignment)
add_subdirectory(FaceIdentification)