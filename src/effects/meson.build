subdir('imagefilters')

source_file = [
	'Sk1DPathEffect.cpp',
	'Sk2DPathEffect.cpp',
	'SkColorMatrix.cpp',
	'SkColorMatrixFilter.cpp',
	'SkCornerPathEffect.cpp',
	'SkDashPathEffect.cpp',
	'SkDiscretePathEffect.cpp',
	'SkEmbossMask.cpp',
	'SkEmbossMaskFilter.cpp',
	'SkHighContrastFilter.cpp',
	'SkLayerDrawLooper.cpp',
	'SkLumaColorFilter.cpp',
	'SkOpPathEffect.cpp',
	'SkOverdrawColorFilter.cpp',
	'SkPackBits.cpp',
	'SkShaderMaskFilter.cpp',
	'SkTableColorFilter.cpp',
	'SkTableMaskFilter.cpp',
	'SkTrimPathEffect.cpp',
	]

skeffects_dep = declare_dependency(
                                    include_directories : include_directories('.'),
                                    sources : source_file,
                                    dependencies : skeffects_imagefilters_dep,
                                 )