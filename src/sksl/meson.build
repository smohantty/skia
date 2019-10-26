subdir('ir')
subdir('lex')
source_file = [
	'SkSLASTNode.cpp',
	'SkSLByteCode.cpp',
	'SkSLByteCodeGenerator.cpp',
	'SkSLCFGGenerator.cpp',
	'SkSLCPPCodeGenerator.cpp',
	'SkSLCPPUniformCTypes.cpp',
	'SkSLCompiler.cpp',
	'SkSLGLSLCodeGenerator.cpp',
	'SkSLHCodeGenerator.cpp',
	'SkSLIRGenerator.cpp',
	'SkSLLexer.cpp',
	'SkSLMain.cpp',
	'SkSLMetalCodeGenerator.cpp',
	'SkSLOutputStream.cpp',
	'SkSLParser.cpp',
	'SkSLPipelineStageCodeGenerator.cpp',
	'SkSLSPIRVCodeGenerator.cpp',
	'SkSLSectionAndParameterHelper.cpp',
	'SkSLString.cpp',
	'SkSLUtil.cpp',
	]

sksksl_dep = declare_dependency(
                                    include_directories : include_directories('.'),
                                    sources : source_file,
                                    dependencies : [ sksksl_ir_dep, sksksl_lex_dep],
                                 )