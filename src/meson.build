src = 'utils.cpp'
src_w_main = files([src]) + files(['main.cpp'])

mesonunitlib = shared_library('mesonunit',
                        src,
                        include_directories : inc,
                        dependencies : [],
                        install : true)

executable(
    meson.project_name(),
    sources: src_w_main,
    include_directories : inc,
    dependencies: [],
    install: true
)
