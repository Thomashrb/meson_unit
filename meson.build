project(
  'meson_unit',
  'cpp',
  version : '0.1')

catch2_dep = dependency('catch2-with-main', version: '>=3.7.1')

inc = include_directories('include')

subdir('src')
subdir('test')

pkg_mod = import('pkgconfig')
pkg_mod.generate(libraries : mesonunitlib,
                 version : '1.0',
                 name : 'libmesonunit',
                 filebase : 'mesonunit',
                 description : 'A very testy library')
