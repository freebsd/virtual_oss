LIB= voss_oss
LIBDIR?= /usr/local/lib
SHLIB_MAJOR= 0

SRCS=	oss.c

CFLAGS += -I${.CURDIR} -I/usr/local/include \
	-Wcast-align -Wthread-safety-analysis -Wunused

.include <bsd.lib.mk>
