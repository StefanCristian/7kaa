noinst_LIBRARIES = libaudio_openal.a
libaudio_openal_a_SOURCES = openal_audio.cpp wav_stream.cpp

AM_CPPFLAGS = \
	-I$(top_srcdir)/include
AM_CXXFLAGS = $(GLOBAL_CFLAGS)
AM_CXXFLAGS += $(OPENAL_CFLAGS)
