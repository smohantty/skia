subdir('generated')

source_file = [
	'GrBezierEffect.cpp',
	'GrBicubicEffect.cpp',
	'GrBitmapTextGeoProc.cpp',
	'GrConvexPolyEffect.cpp',
	'GrCoverageSetOpXP.cpp',
	'GrCustomXfermode.cpp',
	'GrDisableColorXP.cpp',
	'GrDistanceFieldGeoProc.cpp',
	'GrGaussianConvolutionFragmentProcessor.cpp',
	'GrMatrixConvolutionEffect.cpp',
	'GrOvalEffect.cpp',
	'GrPorterDuffXferProcessor.cpp',
	'GrRRectEffect.cpp',
	'GrSRGBEffect.cpp',
	'GrShadowGeoProc.cpp',
	'GrSkSLFP.cpp',
	'GrTextureDomain.cpp',
	'GrXfermodeFragmentProcessor.cpp',
	'GrYUVtoRGBEffect.cpp',
	]

skgpu_effects_dep = declare_dependency(
	                                    include_directories : include_directories('.'),
	                                    sources : source_file,
	                                    dependencies : skgpu_effects_generated_dep
                                      )