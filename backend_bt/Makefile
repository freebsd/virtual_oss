.PATH: ../virtual_oss/bt

LIB= voss_bt
LIBDIR?= /usr/local/lib
SHLIB_MAJOR= 0

SRCS=	bt.c

CFLAGS += -I${.CURDIR} -I../virtual_oss/bt -I/usr/local/include \
	-Wcast-align -Wthread-safety-analysis -Wunused
LDFLAGS+= -lbluetooth -lsdp

.if defined(HAVE_FFMPEG)
CFLAGS+=	-DHAVE_FFMPEG
LDFLAGS+= 	-lavdevice -lavutil -lavcodec -lavresample -lavformat
.endif

.include <bsd.lib.mk>
