project('skia',
        'cpp',
        default_options : ['warning_level=0', 'werror=false', 'cpp_std=c++14', 'optimization=s'],
        version : '0.0.1',
        license : 'BSD')

add_project_arguments('-DSK_USER_CONFIG_HEADER="config.h"', language : 'cpp')
compiler_flags = []
linker_flags = []

incdir = [include_directories('include')]
incdir += include_directories('.')
incdir += include_directories('include/third_party/skcms')

config_h = configuration_data()

config_h.set('SK_HAS_PNG_LIBRARY', false)
config_h.set('SK_HAS_HEIF_LIBRARY', false)
config_h.set('SK_HAS_WUFFS_LIBRARY', false)


configure_file(
  output: 'config.h',
  configuration: config_h
)

subdir('src/core')
subdir('src/utils')
subdir('src/ports')
subdir('src/gpu')
subdir('src/image')
subdir('src/images')
subdir('src/shaders')
subdir('src/pathops')
subdir('src/lazy')
subdir('src/effects')
subdir('src/opts')
subdir('src/codec')
subdir('src/sksl')


#todo fix
subdir('third_party/gif')
subdir('third_party/skcms')



skia_lib_dep  = [
                 skcore_dep, 
                 skutils_dep, 
                 skports_dep, 
                 skgpu_dep, 
                 skimage_dep, 
                 skimages_dep,
                 skshaders_dep,
                 skpathops_dep,
                 sklazy_dep,
                 skeffects_dep,
                 skopts_dep, 
                 skcodec_dep,
                 skgif_dep,
                 skskcms_dep, 
                 sksksl_dep
                 ]

skia_lib = library('skia',
                      include_directories   : incdir,
                      version               : meson.project_version(),
                      dependencies          : skia_lib_dep,
                      install               : false,
                      cpp_args              : compiler_flags,
                      link_args             : linker_flags,
                      gnu_symbol_visibility : 'hidden',
                     )




