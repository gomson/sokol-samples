fips_begin_lib(flextgl)
    fips_vs_warning_level(3)
    fips_src(flextgl)
fips_end_lib()

fips_begin_app(clear-glfw cmdline)
    fips_vs_warning_level(3)
    fips_files(clear-glfw.c)
    fips_deps(glfw3 flextgl)
fips_end_app()

fips_begin_app(triangle-glfw cmdline)
    fips_vs_warning_level(3)
    fips_files(triangle-glfw.c)
    fips_deps(glfw3 flextgl)
fips_end_app()
