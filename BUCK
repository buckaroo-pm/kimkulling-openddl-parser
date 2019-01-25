load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'openddlparser',
  header_namespace = 'openddlparser',
  exported_headers = subdir_glob([
    ('include/openddlparser', '**/*.h'),
  ]),
  srcs = glob([
    'code/**/*.cpp',
  ]),
  visibility = ['PUBLIC'],
)
