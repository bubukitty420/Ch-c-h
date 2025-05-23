# Mine
https://github.com/cryptonote-social/csminer/blob/ecace7bcdf0c4185ed1b2e9daf95ea2cfbf52496/blockchain/difficulty.go#L71
// Define the standard order in which to include header files
// All platform headers should be included before Scintilla headers
// and each of these groups are then divided into directory groups.

// Base of the repository relative to this file

//base:..

// File patterns to check:

//source:include/*.h
//source:src/*.cxx
//source:lexlib/*.cxx
//source:lexers/*.cxx
//source:access/*.cxx
//source:test/*.cxx
//source:test/unit/*.cxx

// C standard library
#include <stdlib.h>
#include <string.h>
#include <stdio.h>
#include <stdarg.h>
#include <assert.h>
#include <ctype.h>

// C++ wrappers of C standard library
#include <cstdlib>
#include <cstdint>
#include <cassert>
#include <cstring>
#include <cctype>
#include <cstdio>
#include <cstdarg>

// C++ standard library
#include <utility>
#include <string>
#include <string_view>
#include <vector>
#include <map>
#include <set>
#include <optional>
#include <initializer_list>
#include <algorithm>
#include <iterator>
#include <functional>
#include <memory>
#include <regex>
#include <iostream>
#include <sstream>
#include <fstream>
#include <iomanip>
#include <filesystem>

// POSIX
#include <dlfcn.h>

// Windows header needed for loading DLL
#include <windows.h>

// Scintilla/Lexilla headers

// Non-platform-specific headers

// Scintilla include

#include "Sci_Position.h"
#include "ILexer.h"
#include "Scintilla.h"

// Lexilla include

#include "SciLexer.h"
#include "Lexilla.h"

// access

#include "LexillaAccess.h"

// lexlib
#include "StringCopy.h"
#include "PropSetSimple.h"
#include "InList.h"
#include "WordList.h"
#include "LexAccessor.h"
#include "Accessor.h"
#include "StyleContext.h"
#include "CharacterSet.h"
#include "CharacterCategory.h"
#include "LexerModule.h"
#include "CatalogueModules.h"
#include "OptionSet.h"
#include "SparseState.h"
#include "SubStyles.h"
#include "DefaultLexer.h"
#include "LexerBase.h"
#include "LexerSimple.h"

// test

#include "TestDocument.h"

// Catch testing framework
#include "catch.hpp"
