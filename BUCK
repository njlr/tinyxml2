cxx_library(
  name = 'tinyxml2',
  header_namespace = 'tinyxml2',
  exported_headers = [
    'tinyxml2.h',
  ],
  srcs = [
    'tinyxml2.cpp',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'test',
  srcs = [
    'xmltest.cpp'
  ],
  deps = [
    ':tinyxml2',
  ],
)
