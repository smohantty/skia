
subdir('gradients')

source_file = [
	'SkBitmapProcShader.cpp',
	'SkColorFilterShader.cpp',
	'SkColorShader.cpp',
	'SkComposeShader.cpp',
	'SkImageShader.cpp',
	'SkLightingShader.cpp',
	'SkLights.cpp',
	'SkLocalMatrixShader.cpp',
	'SkPerlinNoiseShader.cpp',
	'SkPictureShader.cpp',
	'SkRTShader.cpp',
	'SkShader.cpp',
	]

skshaders_dep = declare_dependency(
                                    include_directories : include_directories('.'),
                                    sources : source_file,
                                    dependencies : skshader_gradient_dep,
                                 )