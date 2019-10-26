subdir('generated')

source_file = [
	'GrGradientBitmapCache.cpp',
	'GrGradientShader.cpp',
	]

skgpu_gradients_dep = declare_dependency(
                                    include_directories : include_directories('.'),
                                    sources : source_file,
                                    dependencies : skgpu_gradients_generated_dep,
                                 )