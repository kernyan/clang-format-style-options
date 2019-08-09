# clang-format style-options listing by version

## Documentation
[Clang 9](https://clang.llvm.org/docs/ClangFormatStyleOptions.html)\
[Clang 8](https://releases.llvm.org/8.0.0/tools/clang/docs/ClangFormatStyleOptions.html)\
[Clang 7](https://releases.llvm.org/7.0.0/tools/clang/docs/ClangFormatStyleOptions.html)\
[Clang 6](https://releases.llvm.org/6.0.0/tools/clang/docs/ClangFormatStyleOptions.html)\
[Clang 5](https://releases.llvm.org/5.0.0/tools/clang/docs/ClangFormatStyleOptions.html)\
[Clang 4](https://releases.llvm.org/4.0.0/tools/clang/docs/ClangFormatStyleOptions.html)

## ClangFormat new style-options added
| Clang 9 | Clang 8 | Clang 7 | Clang 6 | Clang 5 |
|:---     |:---     |:---     |:---     |:---     |
| AlignConsecutiveMacros (bool)      | JavaImportGroups (std::vector<std::string>) | ObjCBinPackProtocolList (BinPackStyle)     | IncludeBlocks (IncludeBlocksStyle) | BreakBeforeInheritanceComma (bool) |
| AllowAllArgumentsOnNextLine (bool) | StatementMacros (std::vector<std::string>)  | PenaltyBreakTemplateDeclaration (unsigned) | IndentPPDirectives (PPDirectiveIndentStyle) | CompactNamespaces (bool)  |
| AllowAllConstructorInitializersOnNextLine (bool) |                               | SpaceBeforeCpp11BracedList (bool)          | RawStringFormats (std::vector<RawStringFormat>) | FixNamespaceComments (bool) |
| AllowShortLambdasOnASingleLine (ShortLambdaStyle) |                              | SpaceBeforeCtorInitializerColon (bool)     |                                          | JavaScriptWrapImports (bool) |
| TypenameMacros (std::vector<std::string>)        |                               | SpaceBeforeInheritanceColon (bool)         |                                       | PenaltyBreakAssignment (unsigned) |
| NamespaceMacros (std::vector<std::string>) |                                     | SpaceBeforeRangeBasedForLoopColon (bool)   |                                       | SortUsingDeclarations (bool) |
| SpaceAfterLogicalNot (bool) |                                                    |                                            |                                       |                              |
 
## ClangFormat style-options interface changes
| Clang 9 | Clang 8 | Clang 7 | Clang 6 | Clang 5 | Clang 4 |
|:---     |:---     |:---     |:---     |:---     |:---     |
| AllowShortIfStatementsOnASingleLine (ShortIfStyle) | AllowShortIfStatementsOnASingleLine (bool)      |       |       |         |         |
|         |         | AlwaysBreakTemplateDeclarations (BreakTemplateDeclarationsStyle) | AlwaysBreakTemplateDeclarations (bool)   |         |            |
|         |         | BreakInheritanceList (BreakInheritanceListStyle)                 | BreakBeforeInheritanceComma (bool)       |         |            |
|         |         |         |         | AlignEscapedNewlines (EscapedNewlineAlignmentStyle) |  AlignEscapedNewlinesLeft (bool) |
|         |         |         |         | BreakConstructorInitializers (BreakConstructorInitializersStyle) |  BreakConstructorInitializersBeforeComma (bool) |

## ClangFormat complete style-options by version

| Clang 9 | Clang 8 | Clang 7 | Clang 6 | Clang 5 | Clang 4 |
|:---     |:---     |:---     |:---     |:---     |:---     |
|	AccessModifierOffset (int)	|	AccessModifierOffset (int)	|	AccessModifierOffset (int)	|	AccessModifierOffset (int)	|	AccessModifierOffset (int)	|	AccessModifierOffset (int)
|	AlignAfterOpenBracket (BracketAlignmentStyle)	|	AlignAfterOpenBracket (BracketAlignmentStyle)	|	AlignAfterOpenBracket (BracketAlignmentStyle)	|	AlignAfterOpenBracket (BracketAlignmentStyle)	|	AlignAfterOpenBracket (BracketAlignmentStyle)	|	AlignAfterOpenBracket (BracketAlignmentStyle)
|	AlignConsecutiveMacros (bool)	|		|		|		|		|	
|	AlignConsecutiveAssignments (bool)	|	AlignConsecutiveAssignments (bool)	|	AlignConsecutiveAssignments (bool)	|	AlignConsecutiveAssignments (bool)	|	AlignConsecutiveAssignments (bool)	|	AlignConsecutiveAssignments (bool)
|	AlignConsecutiveDeclarations (bool)	|	AlignConsecutiveDeclarations (bool)	|	AlignConsecutiveDeclarations (bool)	|	AlignConsecutiveDeclarations (bool)	|	AlignConsecutiveDeclarations (bool)	|	AlignConsecutiveDeclarations (bool)
|	AlignEscapedNewlines (EscapedNewlineAlignmentStyle)	|	AlignEscapedNewlines (EscapedNewlineAlignmentStyle)	|	AlignEscapedNewlines (EscapedNewlineAlignmentStyle)	|	AlignEscapedNewlines (EscapedNewlineAlignmentStyle)	|	AlignEscapedNewlines (EscapedNewlineAlignmentStyle)	|	AlignEscapedNewlinesLeft (bool)
|	AlignOperands (bool)	|	AlignOperands (bool)	|	AlignOperands (bool)	|	AlignOperands (bool)	|	AlignOperands (bool)	|	AlignOperands (bool)
|	AlignTrailingComments (bool)	|	AlignTrailingComments (bool)	|	AlignTrailingComments (bool)	|	AlignTrailingComments (bool)	|	AlignTrailingComments (bool)	|	AlignTrailingComments (bool)
|	AllowAllArgumentsOnNextLine (bool)	|		|		|		|		|	
|	AllowAllConstructorInitializersOnNextLine (bool)	|		|		|		|		|	
|	AllowAllParametersOfDeclarationOnNextLine (bool)	|	AllowAllParametersOfDeclarationOnNextLine (bool)	|	AllowAllParametersOfDeclarationOnNextLine (bool)	|	AllowAllParametersOfDeclarationOnNextLine (bool)	|	AllowAllParametersOfDeclarationOnNextLine (bool)	|	AllowAllParametersOfDeclarationOnNextLine (bool)
|	AllowShortBlocksOnASingleLine (bool)	|	AllowShortBlocksOnASingleLine (bool)	|	AllowShortBlocksOnASingleLine (bool)	|	AllowShortBlocksOnASingleLine (bool)	|	AllowShortBlocksOnASingleLine (bool)	|	AllowShortBlocksOnASingleLine (bool)
|	AllowShortCaseLabelsOnASingleLine (bool)	|	AllowShortCaseLabelsOnASingleLine (bool)	|	AllowShortCaseLabelsOnASingleLine (bool)	|	AllowShortCaseLabelsOnASingleLine (bool)	|	AllowShortCaseLabelsOnASingleLine (bool)	|	AllowShortCaseLabelsOnASingleLine (bool)
|	AllowShortFunctionsOnASingleLine (ShortFunctionStyle)	|	AllowShortFunctionsOnASingleLine (ShortFunctionStyle)	|	AllowShortFunctionsOnASingleLine (ShortFunctionStyle)	|	AllowShortFunctionsOnASingleLine (ShortFunctionStyle)	|	AllowShortFunctionsOnASingleLine (ShortFunctionStyle)	|	AllowShortFunctionsOnASingleLine (ShortFunctionStyle)
|	AllowShortIfStatementsOnASingleLine (ShortIfStyle)	|	AllowShortIfStatementsOnASingleLine (bool)	|	AllowShortIfStatementsOnASingleLine (bool)	|	AllowShortIfStatementsOnASingleLine (bool)	|	AllowShortIfStatementsOnASingleLine (bool)	|	AllowShortIfStatementsOnASingleLine (bool)
|	AllowShortLambdasOnASingleLine (ShortLambdaStyle)	|		|		|		|		|	
|	AllowShortLoopsOnASingleLine (bool)	|	AllowShortLoopsOnASingleLine (bool)	|	AllowShortLoopsOnASingleLine (bool)	|	AllowShortLoopsOnASingleLine (bool)	|	AllowShortLoopsOnASingleLine (bool)	|	AllowShortLoopsOnASingleLine (bool)
|	AlwaysBreakAfterDefinitionReturnType (DefinitionReturnTypeBreakingStyle)	|	AlwaysBreakAfterDefinitionReturnType (DefinitionReturnTypeBreakingStyle)	|	AlwaysBreakAfterDefinitionReturnType (DefinitionReturnTypeBreakingStyle)	|	AlwaysBreakAfterDefinitionReturnType (DefinitionReturnTypeBreakingStyle)	|	AlwaysBreakAfterDefinitionReturnType (DefinitionReturnTypeBreakingStyle)	|	AlwaysBreakAfterDefinitionReturnType (DefinitionReturnTypeBreakingStyle)
|	AlwaysBreakAfterReturnType (ReturnTypeBreakingStyle)	|	AlwaysBreakAfterReturnType (ReturnTypeBreakingStyle)	|	AlwaysBreakAfterReturnType (ReturnTypeBreakingStyle)	|	AlwaysBreakAfterReturnType (ReturnTypeBreakingStyle)	|	AlwaysBreakAfterReturnType (ReturnTypeBreakingStyle)	|	AlwaysBreakAfterReturnType (ReturnTypeBreakingStyle)
|	AlwaysBreakBeforeMultilineStrings (bool)	|	AlwaysBreakBeforeMultilineStrings (bool)	|	AlwaysBreakBeforeMultilineStrings (bool)	|	AlwaysBreakBeforeMultilineStrings (bool)	|	AlwaysBreakBeforeMultilineStrings (bool)	|	AlwaysBreakBeforeMultilineStrings (bool)
|	AlwaysBreakTemplateDeclarations (BreakTemplateDeclarationsStyle)	|	AlwaysBreakTemplateDeclarations (BreakTemplateDeclarationsStyle)	|	AlwaysBreakTemplateDeclarations (BreakTemplateDeclarationsStyle)	|	AlwaysBreakTemplateDeclarations (bool)	|	AlwaysBreakTemplateDeclarations (bool)	|	AlwaysBreakTemplateDeclarations (bool)
|	BinPackArguments (bool)	|	BinPackArguments (bool)	|	BinPackArguments (bool)	|	BinPackArguments (bool)	|	BinPackArguments (bool)	|	BinPackArguments (bool)
|	BinPackParameters (bool)	|	BinPackParameters (bool)	|	BinPackParameters (bool)	|	BinPackParameters (bool)	|	BinPackParameters (bool)	|	BinPackParameters (bool)
|	BraceWrapping (BraceWrappingFlags)	|	BraceWrapping (BraceWrappingFlags)	|	BraceWrapping (BraceWrappingFlags)	|	BraceWrapping (BraceWrappingFlags)	|	BraceWrapping (BraceWrappingFlags)	|	BraceWrapping (BraceWrappingFlags)
|	BreakAfterJavaFieldAnnotations (bool)	|	BreakAfterJavaFieldAnnotations (bool)	|	BreakAfterJavaFieldAnnotations (bool)	|	BreakAfterJavaFieldAnnotations (bool)	|	BreakAfterJavaFieldAnnotations (bool)	|	BreakAfterJavaFieldAnnotations (bool)
|	BreakBeforeBinaryOperators (BinaryOperatorStyle)	|	BreakBeforeBinaryOperators (BinaryOperatorStyle)	|	BreakBeforeBinaryOperators (BinaryOperatorStyle)	|	BreakBeforeBinaryOperators (BinaryOperatorStyle)	|	BreakBeforeBinaryOperators (BinaryOperatorStyle)	|	BreakBeforeBinaryOperators (BinaryOperatorStyle)
|	BreakBeforeBraces (BraceBreakingStyle)	|	BreakBeforeBraces (BraceBreakingStyle)	|	BreakBeforeBraces (BraceBreakingStyle)	|	BreakBeforeBraces (BraceBreakingStyle)	|	BreakBeforeBraces (BraceBreakingStyle)	|	BreakBeforeBraces (BraceBreakingStyle)
|	BreakBeforeTernaryOperators (bool)	|	BreakBeforeTernaryOperators (bool)	|	BreakBeforeTernaryOperators (bool)	|	BreakBeforeTernaryOperators (bool)	|	BreakBeforeTernaryOperators (bool)	|	BreakBeforeTernaryOperators (bool) 	|
|	BreakConstructorInitializers (BreakConstructorInitializersStyle)	|	BreakConstructorInitializers (BreakConstructorInitializersStyle)	|	BreakConstructorInitializers (BreakConstructorInitializersStyle)	|	BreakConstructorInitializers (BreakConstructorInitializersStyle)	|	BreakConstructorInitializers (BreakConstructorInitializersStyle)	|	BreakConstructorInitializersBeforeComma (bool)
|	BreakInheritanceList (BreakInheritanceListStyle)	|	BreakInheritanceList (BreakInheritanceListStyle)	|	BreakInheritanceList (BreakInheritanceListStyle)	|	BreakBeforeInheritanceComma (bool)	|	BreakBeforeInheritanceComma (bool)	|	
|	BreakStringLiterals (bool)	|	BreakStringLiterals (bool)	|	BreakStringLiterals (bool)	|	BreakStringLiterals (bool)	|	BreakStringLiterals (bool)	|	BreakStringLiterals (bool)
|	ColumnLimit (unsigned)	|	ColumnLimit (unsigned)	|	ColumnLimit (unsigned)	|	ColumnLimit (unsigned)	|	ColumnLimit (unsigned)	|	ColumnLimit (unsigned)
|	CommentPragmas (std::string)	|	CommentPragmas (std::string)	|	CommentPragmas (std::string)	|	CommentPragmas (std::string)	|	CommentPragmas (std::string)	|	CommentPragmas (std::string)
|	CompactNamespaces (bool)	|	CompactNamespaces (bool)	|	CompactNamespaces (bool)	|	CompactNamespaces (bool)	|	CompactNamespaces (bool)	|	
|	ConstructorInitializerAllOnOneLineOrOnePerLine (bool)	|	ConstructorInitializerAllOnOneLineOrOnePerLine (bool)	|	ConstructorInitializerAllOnOneLineOrOnePerLine (bool)	|	ConstructorInitializerAllOnOneLineOrOnePerLine (bool)	|	ConstructorInitializerAllOnOneLineOrOnePerLine (bool)	|	ConstructorInitializerAllOnOneLineOrOnePerLine (bool)
|	ConstructorInitializerIndentWidth (unsigned)	|	ConstructorInitializerIndentWidth (unsigned)	|	ConstructorInitializerIndentWidth (unsigned)	|	ConstructorInitializerIndentWidth (unsigned)	|	ConstructorInitializerIndentWidth (unsigned)	|	ConstructorInitializerIndentWidth (unsigned)
|	ContinuationIndentWidth (unsigned)	|	ContinuationIndentWidth (unsigned)	|	ContinuationIndentWidth (unsigned)	|	ContinuationIndentWidth (unsigned)	|	ContinuationIndentWidth (unsigned)	|	ContinuationIndentWidth (unsigned)
|	Cpp11BracedListStyle (bool)	|	Cpp11BracedListStyle (bool)	|	Cpp11BracedListStyle (bool)	|	Cpp11BracedListStyle (bool)	|	Cpp11BracedListStyle (bool)	|	Cpp11BracedListStyle (bool)
|	DerivePointerAlignment (bool)	|	DerivePointerAlignment (bool)	|	DerivePointerAlignment (bool)	|	DerivePointerAlignment (bool)	|	DerivePointerAlignment (bool)	|	DerivePointerAlignment (bool)
|	DisableFormat (bool)	|	DisableFormat (bool)	|	DisableFormat (bool)	|	DisableFormat (bool)	|	DisableFormat (bool)	|	DisableFormat (bool)
|	ExperimentalAutoDetectBinPacking (bool)	|	ExperimentalAutoDetectBinPacking (bool)	|	ExperimentalAutoDetectBinPacking (bool)	|	ExperimentalAutoDetectBinPacking (bool)	|	ExperimentalAutoDetectBinPacking (bool)	|	ExperimentalAutoDetectBinPacking (bool)
|	FixNamespaceComments (bool)	|	FixNamespaceComments (bool)	|	FixNamespaceComments (bool)	|	FixNamespaceComments (bool)	|	FixNamespaceComments (bool)	|	
|	ForEachMacros (std::vector<std::string>)	|	ForEachMacros (std::vector<std::string>)	|	ForEachMacros (std::vector<std::string>)	|	ForEachMacros (std::vector<std::string>)	|	ForEachMacros (std::vector<std::string>)	|	ForEachMacros (std::vector<std::string>)
|	TypenameMacros (std::vector<std::string>)	|		|		|		|		|	
|	IncludeBlocks (IncludeBlocksStyle)	|	IncludeBlocks (IncludeBlocksStyle)	|	IncludeBlocks (IncludeBlocksStyle)	|	IncludeBlocks (IncludeBlocksStyle)	|		|	
|	IncludeCategories (std::vector<IncludeCategory>)	|	IncludeCategories (std::vector<IncludeCategory>)	|	IncludeCategories (std::vector<IncludeCategory>)	|	IncludeCategories (std::vector<IncludeCategory>)	|	IncludeCategories (std::vector<IncludeCategory>)	|	IncludeCategories (std::vector<IncludeCategory>)
|	IncludeIsMainRegex (std::string)	|	IncludeIsMainRegex (std::string)	|	IncludeIsMainRegex (std::string)	|	IncludeIsMainRegex (std::string)	|	IncludeIsMainRegex (std::string)	|	IncludeIsMainRegex (std::string)
|	IndentCaseLabels (bool)	|	IndentCaseLabels (bool)	|	IndentCaseLabels (bool)	|	IndentCaseLabels (bool)	|	IndentCaseLabels (bool)	|	IndentCaseLabels (bool)
|	IndentPPDirectives (PPDirectiveIndentStyle)	|	IndentPPDirectives (PPDirectiveIndentStyle)	|	IndentPPDirectives (PPDirectiveIndentStyle)	|	IndentPPDirectives (PPDirectiveIndentStyle)	|		|	
|	IndentWidth (unsigned)	|	IndentWidth (unsigned)	|	IndentWidth (unsigned)	|	IndentWidth (unsigned)	|	IndentWidth (unsigned)	|	IndentWidth (unsigned)
|	IndentWrappedFunctionNames (bool)	|	IndentWrappedFunctionNames (bool)	|	IndentWrappedFunctionNames (bool)	|	IndentWrappedFunctionNames (bool)	|	IndentWrappedFunctionNames (bool)	|	IndentWrappedFunctionNames (bool)
|	JavaImportGroups (std::vector<std::string>)	|	JavaImportGroups (std::vector<std::string>)	|		|		|		|	
|	JavaScriptQuotes (JavaScriptQuoteStyle)	|	JavaScriptQuotes (JavaScriptQuoteStyle)	|	JavaScriptQuotes (JavaScriptQuoteStyle)	|	JavaScriptQuotes (JavaScriptQuoteStyle)	|	JavaScriptQuotes (JavaScriptQuoteStyle)	|	JavaScriptQuotes (JavaScriptQuoteStyle)
|	JavaScriptWrapImports (bool)	|	JavaScriptWrapImports (bool)	|	JavaScriptWrapImports (bool)	|	JavaScriptWrapImports (bool)	|	JavaScriptWrapImports (bool)	|	
|	KeepEmptyLinesAtTheStartOfBlocks (bool)	|	KeepEmptyLinesAtTheStartOfBlocks (bool)	|	KeepEmptyLinesAtTheStartOfBlocks (bool)	|	KeepEmptyLinesAtTheStartOfBlocks (bool)	|	KeepEmptyLinesAtTheStartOfBlocks (bool)	|	KeepEmptyLinesAtTheStartOfBlocks (bool)
|	Language (LanguageKind)	|	Language (LanguageKind)	|	Language (LanguageKind)	|	Language (LanguageKind)	|	Language (LanguageKind)	|	Language (LanguageKind)
|	MacroBlockBegin (std::string)	|	MacroBlockBegin (std::string)	|	MacroBlockBegin (std::string)	|	MacroBlockBegin (std::string)	|	MacroBlockBegin (std::string)	|	MacroBlockBegin (std::string)
|	MacroBlockEnd (std::string)	|	MacroBlockEnd (std::string)	|	MacroBlockEnd (std::string)	|	MacroBlockEnd (std::string)	|	MacroBlockEnd (std::string)	|	MacroBlockEnd (std::string)
|	MaxEmptyLinesToKeep (unsigned)	|	MaxEmptyLinesToKeep (unsigned)	|	MaxEmptyLinesToKeep (unsigned)	|	MaxEmptyLinesToKeep (unsigned)	|	MaxEmptyLinesToKeep (unsigned)	|	MaxEmptyLinesToKeep (unsigned)
|	NamespaceIndentation (NamespaceIndentationKind)	|	NamespaceIndentation (NamespaceIndentationKind)	|	NamespaceIndentation (NamespaceIndentationKind)	|	NamespaceIndentation (NamespaceIndentationKind)	|	NamespaceIndentation (NamespaceIndentationKind)	|	NamespaceIndentation (NamespaceIndentationKind)
|	NamespaceMacros (std::vector<std::string>)	|		|		|		|		|	
|	ObjCBinPackProtocolList (BinPackStyle)	|	ObjCBinPackProtocolList (BinPackStyle)	|	ObjCBinPackProtocolList (BinPackStyle)	|		|		|	
|	ObjCBlockIndentWidth (unsigned)	|	ObjCBlockIndentWidth (unsigned)	|	ObjCBlockIndentWidth (unsigned)	|	ObjCBlockIndentWidth (unsigned)	|	ObjCBlockIndentWidth (unsigned)	|	ObjCBlockIndentWidth (unsigned)
|	ObjCSpaceAfterProperty (bool)	|	ObjCSpaceAfterProperty (bool)	|	ObjCSpaceAfterProperty (bool)	|	ObjCSpaceAfterProperty (bool)	|	ObjCSpaceAfterProperty (bool)	|	ObjCSpaceAfterProperty (bool)
|	ObjCSpaceBeforeProtocolList (bool)	|	ObjCSpaceBeforeProtocolList (bool)	|	ObjCSpaceBeforeProtocolList (bool)	|	ObjCSpaceBeforeProtocolList (bool)	|	ObjCSpaceBeforeProtocolList (bool)	|	ObjCSpaceBeforeProtocolList (bool)
|	PenaltyBreakAssignment (unsigned)	|	PenaltyBreakAssignment (unsigned)	|	PenaltyBreakAssignment (unsigned)	|	PenaltyBreakAssignment (unsigned)	|	PenaltyBreakAssignment (unsigned)	|	
|	PenaltyBreakBeforeFirstCallParameter (unsigned)	|	PenaltyBreakBeforeFirstCallParameter (unsigned)	|	PenaltyBreakBeforeFirstCallParameter (unsigned)	|	PenaltyBreakBeforeFirstCallParameter (unsigned)	|	PenaltyBreakBeforeFirstCallParameter (unsigned)	|	PenaltyBreakBeforeFirstCallParameter (unsigned)
|	PenaltyBreakComment (unsigned)	|	PenaltyBreakComment (unsigned)	|	PenaltyBreakComment (unsigned)	|	PenaltyBreakComment (unsigned)	|	PenaltyBreakComment (unsigned)	|	PenaltyBreakComment (unsigned)
|	PenaltyBreakFirstLessLess (unsigned)	|	PenaltyBreakFirstLessLess (unsigned)	|	PenaltyBreakFirstLessLess (unsigned)	|	PenaltyBreakFirstLessLess (unsigned)	|	PenaltyBreakFirstLessLess (unsigned)	|	PenaltyBreakFirstLessLess (unsigned)
|	PenaltyBreakString (unsigned)	|	PenaltyBreakString (unsigned)	|	PenaltyBreakString (unsigned)	|	PenaltyBreakString (unsigned)	|	PenaltyBreakString (unsigned)	|	PenaltyBreakString (unsigned)
|	PenaltyBreakTemplateDeclaration (unsigned)	|	PenaltyBreakTemplateDeclaration (unsigned)	|	PenaltyBreakTemplateDeclaration (unsigned)	|		|		|	
|	PenaltyExcessCharacter (unsigned)	|	PenaltyExcessCharacter (unsigned)	|	PenaltyExcessCharacter (unsigned)	|	PenaltyExcessCharacter (unsigned)	|	PenaltyExcessCharacter (unsigned)	|	PenaltyExcessCharacter (unsigned)
|	PenaltyReturnTypeOnItsOwnLine (unsigned)	|	PenaltyReturnTypeOnItsOwnLine (unsigned)	|	PenaltyReturnTypeOnItsOwnLine (unsigned)	|	PenaltyReturnTypeOnItsOwnLine (unsigned)	|	PenaltyReturnTypeOnItsOwnLine (unsigned)	|	PenaltyReturnTypeOnItsOwnLine (unsigned)
|	PointerAlignment (PointerAlignmentStyle)	|	PointerAlignment (PointerAlignmentStyle)	|	PointerAlignment (PointerAlignmentStyle)	|	PointerAlignment (PointerAlignmentStyle)	|	PointerAlignment (PointerAlignmentStyle)	|	PointerAlignment (PointerAlignmentStyle)
|	RawStringFormats (std::vector<RawStringFormat>)	|	RawStringFormats (std::vector<RawStringFormat>)	|	RawStringFormats (std::vector<RawStringFormat>)	|	RawStringFormats (std::vector<RawStringFormat>)	|		|	
|	ReflowComments (bool)	|	ReflowComments (bool)	|	ReflowComments (bool)	|	ReflowComments (bool)	|	ReflowComments (bool)	|	ReflowComments (bool)
|	SortIncludes (bool)	|	SortIncludes (bool)	|	SortIncludes (bool)	|	SortIncludes (bool)	|	SortIncludes (bool)	|	SortIncludes (bool)
|	SortUsingDeclarations (bool)	|	SortUsingDeclarations (bool)	|	SortUsingDeclarations (bool)	|	SortUsingDeclarations (bool)	|	SortUsingDeclarations (bool)	|	
|	SpaceAfterCStyleCast (bool)	|	SpaceAfterCStyleCast (bool)	|	SpaceAfterCStyleCast (bool)	|	SpaceAfterCStyleCast (bool)	|	SpaceAfterCStyleCast (bool)	|	SpaceAfterCStyleCast (bool)
|	SpaceAfterLogicalNot (bool)	|		|		|		|		|	
|	SpaceAfterTemplateKeyword (bool)	|	SpaceAfterTemplateKeyword (bool)	|	SpaceAfterTemplateKeyword (bool)	|	SpaceAfterTemplateKeyword (bool)	|	SpaceAfterTemplateKeyword (bool)	|	SpaceAfterTemplateKeyword (bool)
|	SpaceBeforeAssignmentOperators (bool)	|	SpaceBeforeAssignmentOperators (bool)	|	SpaceBeforeAssignmentOperators (bool)	|	SpaceBeforeAssignmentOperators (bool)	|	SpaceBeforeAssignmentOperators (bool)	|	SpaceBeforeAssignmentOperators (bool)
|	SpaceBeforeCpp11BracedList (bool)	|	SpaceBeforeCpp11BracedList (bool)	|	SpaceBeforeCpp11BracedList (bool)	|		|		|	
|	SpaceBeforeCtorInitializerColon (bool)	|	SpaceBeforeCtorInitializerColon (bool)	|	SpaceBeforeCtorInitializerColon (bool)	|		|		|	
|	SpaceBeforeInheritanceColon (bool)	|	SpaceBeforeInheritanceColon (bool)	|	SpaceBeforeInheritanceColon (bool)	|		|		|	
|	SpaceBeforeParens (SpaceBeforeParensOptions)	|	SpaceBeforeParens (SpaceBeforeParensOptions)	|	SpaceBeforeParens (SpaceBeforeParensOptions)	|	SpaceBeforeParens (SpaceBeforeParensOptions)	|	SpaceBeforeParens (SpaceBeforeParensOptions)	|	SpaceBeforeParens (SpaceBeforeParensOptions)
|	SpaceBeforeRangeBasedForLoopColon (bool)	|	SpaceBeforeRangeBasedForLoopColon (bool)	|	SpaceBeforeRangeBasedForLoopColon (bool)	|		|		|	
|	SpaceInEmptyParentheses (bool)	|	SpaceInEmptyParentheses (bool)	|	SpaceInEmptyParentheses (bool)	|	SpaceInEmptyParentheses (bool)	|	SpaceInEmptyParentheses (bool)	|	SpaceInEmptyParentheses (bool)
|	SpacesBeforeTrailingComments (unsigned)	|	SpacesBeforeTrailingComments (unsigned)	|	SpacesBeforeTrailingComments (unsigned)	|	SpacesBeforeTrailingComments (unsigned)	|	SpacesBeforeTrailingComments (unsigned)	|	SpacesBeforeTrailingComments (unsigned)
|	SpacesInAngles (bool)	|	SpacesInAngles (bool)	|	SpacesInAngles (bool)	|	SpacesInAngles (bool)	|	SpacesInAngles (bool)	|	SpacesInAngles (bool)
|	SpacesInCStyleCastParentheses (bool)	|	SpacesInCStyleCastParentheses (bool)	|	SpacesInCStyleCastParentheses (bool)	|	SpacesInCStyleCastParentheses (bool)	|	SpacesInCStyleCastParentheses (bool)	|	SpacesInCStyleCastParentheses (bool)
|	SpacesInContainerLiterals (bool)	|	SpacesInContainerLiterals (bool)	|	SpacesInContainerLiterals (bool)	|	SpacesInContainerLiterals (bool)	|	SpacesInContainerLiterals (bool)	|	SpacesInContainerLiterals (bool)
|	SpacesInParentheses (bool)	|	SpacesInParentheses (bool)	|	SpacesInParentheses (bool)	|	SpacesInParentheses (bool)	|	SpacesInParentheses (bool)	|	SpacesInParentheses (bool)
|	SpacesInSquareBrackets (bool)	|	SpacesInSquareBrackets (bool)	|	SpacesInSquareBrackets (bool)	|	SpacesInSquareBrackets (bool)	|	SpacesInSquareBrackets (bool)	|	SpacesInSquareBrackets (bool)
|	Standard (LanguageStandard)	|	Standard (LanguageStandard)	|	Standard (LanguageStandard)	|	Standard (LanguageStandard)	|	Standard (LanguageStandard)	|	Standard (LanguageStandard)
|	StatementMacros (std::vector<std::string>)	|	StatementMacros (std::vector<std::string>)	|		|		|		|	
|	TabWidth (unsigned)	|	TabWidth (unsigned)	|	TabWidth (unsigned)	|	TabWidth (unsigned)	|	TabWidth (unsigned)	|	TabWidth (unsigned)
|	UseTab (UseTabStyle)	|	UseTab (UseTabStyle)	|	UseTab (UseTabStyle)	|	UseTab (UseTabStyle)	|	UseTab (UseTabStyle)	|	UseTab (UseTabStyle)
										
