reflexincludedir        = $(includedir)/reflex
reflexinclude_HEADERS   = $(top_srcdir)/include/reflex/abslexer.h $(top_srcdir)/include/reflex/absmatcher.h $(top_srcdir)/include/reflex/bits.h $(top_srcdir)/include/reflex/boostmatcher.h $(top_srcdir)/include/reflex/convert.h $(top_srcdir)/include/reflex/debug.h $(top_srcdir)/include/reflex/error.h $(top_srcdir)/include/reflex/flexlexer.h $(top_srcdir)/include/reflex/input.h $(top_srcdir)/include/reflex/matcher.h $(top_srcdir)/include/reflex/pattern.h $(top_srcdir)/include/reflex/posix.h $(top_srcdir)/include/reflex/ranges.h $(top_srcdir)/include/reflex/setop.h $(top_srcdir)/include/reflex/stdmatcher.h $(top_srcdir)/include/reflex/timer.h $(top_srcdir)/include/reflex/traits.h $(top_srcdir)/include/reflex/unicode.h $(top_srcdir)/include/reflex/utf8.h

lib_LIBRARIES           = libreflex.a

libreflex_a_CPPFLAGS    = -I$(top_srcdir)/include -DPLATFORM=\"$(PLATFORM)\" -Wall -Wunused -Wextra
libreflex_a_SOURCES     = convert.cpp debug.cpp error.cpp input.cpp matcher.cpp pattern.cpp posix.cpp unicode.cpp utf8.cpp $(top_srcdir)/unicode/block_scripts.cpp $(top_srcdir)/unicode/language_scripts.cpp $(top_srcdir)/unicode/letter_scripts.cpp

# lib_LTLIBRARIES       = libreflex.la
# libreflex_la_CPPFLAGS = -I$(top_srcdir)/include
# libreflex_la_SOURCES  = convert.cpp debug.cpp error.cpp input.cpp matcher.cpp pattern.cpp posix.cpp unicode.cpp utf8.cpp $(top_srcdir)/unicode/block_scripts.cpp $(top_srcdir)/unicode/language_scripts.cpp $(top_srcdir)/unicode/letter_scripts.cpp
