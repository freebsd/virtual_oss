PROG=		virtual_oss_cmd
MAN=		${PROG}.8
PREFIX?=	/usr/local
LOCALBASE?=	/usr/local
BINDIR=		${PREFIX}/sbin
MANDIR=		${PREFIX}/share/man/man
LIBDIR=		${PREFIX}/lib

SRCS=		command.c

CFLAGS+= 	-I${LOCALBASE}/include -I../virtual_oss \
		-Wcast-align -Wthread-safety-analysis -Wunused
LDFLAGS+= 	-L${LIBDIR}

.include <bsd.prog.mk>
