#
# Linux makefile
#

CFLAGS+=`sdl-config --cflags`
PREFIX=../linux/
SUFFIX=
LIBS+=`sdl-config --libs`

# MIDI input uses CoreMIDI on macOS
ifeq ($(shell uname -s),Darwin)
LIBS+=-framework CoreMIDI -framework CoreFoundation
endif

include makefile.common
