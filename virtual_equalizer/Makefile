PROG=		virtual_equalizer
MAN=		${PROG}.8
PREFIX?=	/usr/local
LOCALBASE?=	/usr/local
BINDIR=		${PREFIX}/sbin
MANDIR=		${PREFIX}/share/man/man
LIBDIR=		${PREFIX}/lib

SRCS=		equalizer.c

CFLAGS+= 	-I${LOCALBASE}/include -I../virtual_oss \
		-Wcast-align -Wthread-safety-analysis -Wunused

LDFLAGS+= 	-L${LIBDIR} -lm -lfftw3

.include <bsd.prog.mk>
