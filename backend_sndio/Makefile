LIB= voss_sndio	
LIBDIR?= /usr/local/lib
SHLIB_MAJOR= 0

SRCS=	sndio.c

CFLAGS+= -I${.CURDIR} -I/usr/local/include \
	-Wcast-align -Wthread-safety-analysis -Wunused

LDFLAGS+= -L/usr/local/lib -lsndio

.include <bsd.lib.mk>
