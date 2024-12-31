testexe = executable('testexe',
    ['utils_test.cpp'],
    include_directories : inc,
    dependencies : catch2_dep,
    link_with : mesonunitlib)
test('meson_unit test', testexe)
