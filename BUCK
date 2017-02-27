prebuilt_cxx_library(
  name = 'eigen',
  header_only = True,
  header_namespace = 'Eigen', 
  exported_headers = subdir_glob([
    ('Eigen', '*'),
    ('Eigen', 'src/**/*.h'),
  ]), 
  visibility = [
    'PUBLIC',
  ],
)
