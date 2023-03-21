add_subdirectory(PDFObjects)
add_library(OasymPDF STATIC PDFFile.cpp)
target_link_libraries(OasymPDF PUBLIC PDFObjects)
target_include_directories(OasymPDF PUBLIC ${CMAKE_SOURCE_DIR}/include)