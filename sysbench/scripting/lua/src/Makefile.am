# Copyright (C) 2006 MySQL AB
# Copyright (C) 2006 Alexey Kopytov <akopytov@gmail.com>
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
# 
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
# 
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA

noinst_LIBRARIES = liblua.a

liblua_a_SOURCES = lapi.c lcode.c ldebug.c ldo.c ldump.c lfunc.c lgc.c llex.c lmem.c \
        lobject.c lopcodes.c lparser.c lstate.c lstring.c ltable.c ltm.c  \
        lundump.c lvm.c lzio.c \
        lauxlib.c lbaselib.c ldblib.c liolib.c lmathlib.c loslib.c ltablib.c \
        lstrlib.c loadlib.c linit.c \
        lapi.h lcode.h ldo.h lgc.h llimits.h lobject.h lparser.h lstring.h ltm.h \
        luaconf.h lundump.h lzio.h lauxlib.h ldebug.h lfunc.h llex.h lmem.h lopcodes.h \
        lstate.h ltable.h lua.h lualib.h lvm.h

AM_CFLAGS += -Wno-bad-function-cast
