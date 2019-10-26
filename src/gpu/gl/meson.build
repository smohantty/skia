subdir('builders')

source_file = [
	'GrGLAssembleGLESInterfaceAutogen.cpp',
	'GrGLAssembleGLInterfaceAutogen.cpp',
	'GrGLAssembleHelpers.cpp',
	'GrGLAssembleInterface.cpp',
	'GrGLAssembleWebGLInterfaceAutogen.cpp',
	'GrGLBuffer.cpp',
	'GrGLCaps.cpp',
	'GrGLContext.cpp',
	'GrGLExtensions.cpp',
	'GrGLGLSL.cpp',
	'GrGLGpu.cpp',
	'GrGLGpuProgramCache.cpp',
	'GrGLInterfaceAutogen.cpp',
	'GrGLMakeNativeInterface_none.cpp',
	'GrGLOpsRenderPass.cpp',
	'GrGLPath.cpp',
	'GrGLPathRendering.cpp',
	'GrGLProgram.cpp',
	'GrGLProgramDataManager.cpp',
	'GrGLRenderTarget.cpp',
	'GrGLSemaphore.cpp',
	'GrGLStencilAttachment.cpp',
	'GrGLTexture.cpp',
	'GrGLTextureRenderTarget.cpp',
	'GrGLTypesPriv.cpp',
	'GrGLUniformHandler.cpp',
	'GrGLUtil.cpp',
	'GrGLVaryingHandler.cpp',
	'GrGLVertexArray.cpp',
	]

skgpu_gl_dep = declare_dependency(
                                    include_directories : include_directories('.'),
                                    sources : source_file,
                                    dependencies : [ skgpu_gl_builder_dep],
                                 )