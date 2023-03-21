add_library(PDFObjects OBJECT PDFObject.cpp)
target_include_directories(PDFObjects PUBLIC ${CMAKE_SOURCE_DIR}/include/PDFObjects)