PORTNAME=      rescrv-devel
PORTVERSION=   20161004
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       devel meta package

NO_BUILD=      yes
NO_WRKSUBDIR=  yes

RUN_DEPENDS+=	rescrv-minimal>0:${PORTSDIR}/rescrv/minimal
RUN_DEPENDS+=	autoconf>0:${PORTSDIR}/devel/autoconf
RUN_DEPENDS+=	autoconf-archive>0:${PORTSDIR}/devel/autoconf-archive
RUN_DEPENDS+=	automake>0:${PORTSDIR}/devel/automake
RUN_DEPENDS+=	bison>0:${PORTSDIR}/devel/bison
RUN_DEPENDS+=	git>0:${PORTSDIR}/devel/git
RUN_DEPENDS+=	libtool>0:${PORTSDIR}/devel/libtool
RUN_DEPENDS+=	pkgconf>0:${PORTSDIR}/devel/pkgconf
RUN_DEPENDS+=	valgrind>0:${PORTSDIR}/devel/valgrind
RUN_DEPENDS+=	cython>0:${PORTSDIR}/lang/cython
RUN_DEPENDS+=	help2man>0:${PORTSDIR}/misc/help2man

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
