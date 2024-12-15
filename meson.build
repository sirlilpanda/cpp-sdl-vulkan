project('sdldemo', 'cpp',
        default_options: 'default_library=static')


deps = [
    # dependency('vulkan'),
    dependency('sdl2'),
    dependency('sdl2main'),
    dependency('imgui', static: true),
]


executable('sdlprog', 'src/main.cpp',
           win_subsystem: 'windows',
           dependencies: deps)
