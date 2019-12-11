incdir = include_directories('.')

zip_lib = static_library('zip',
  'miniz.h',
  'zip.c',
  'zip.h',
  include_directories : incdir,
)

libzip_dep = declare_dependency(include_directories : incdir,
  link_with : zip_lib)
