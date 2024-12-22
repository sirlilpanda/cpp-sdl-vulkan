project('sdldemo', 'cpp',
        default_options: ['default_library=static'])


deps = [
    dependency('sdl2'),
    dependency('sdl2main'),
    dependency('imgui', static: true),
    dependency('glm'),
]

# includeds = include_directories(
#     'src/*.hpp'
# )

srcs = [
    'src/main.cpp',
]


executable(
'app', 
    srcs,
            # win_subsystem: 'windows',
            dependencies: deps
)
# meson compile -C builddir && builddir\app.exe