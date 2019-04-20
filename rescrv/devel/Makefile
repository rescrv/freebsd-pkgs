PORTNAME=      rescrv-devel
PORTVERSION=   20190420
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
RUN_DEPENDS+=	bazel>0:${PORTSDIR}/devel/bazel
RUN_DEPENDS+=	bison>0:${PORTSDIR}/devel/bison
RUN_DEPENDS+=	git>0:${PORTSDIR}/devel/git
RUN_DEPENDS+=	libtool>0:${PORTSDIR}/devel/libtool
RUN_DEPENDS+=	llvm40>0:${PORTSDIR}/devel/llvm40
RUN_DEPENDS+=	llvm50>0:${PORTSDIR}/devel/llvm50
RUN_DEPENDS+=	llvm60>0:${PORTSDIR}/devel/llvm60
RUN_DEPENDS+=	llvm70>0:${PORTSDIR}/devel/llvm70
RUN_DEPENDS+=	pkgconf>0:${PORTSDIR}/devel/pkgconf
RUN_DEPENDS+=	valgrind>0:${PORTSDIR}/devel/valgrind
RUN_DEPENDS+=	py36-cython>0:${PORTSDIR}/lang/cython
RUN_DEPENDS+=	gcc48>0:${PORTSDIR}/lang/gcc48
RUN_DEPENDS+=	gcc49>0:${PORTSDIR}/lang/gcc49
RUN_DEPENDS+=	gcc5>0:${PORTSDIR}/lang/gcc5
RUN_DEPENDS+=	gcc6>0:${PORTSDIR}/lang/gcc6
RUN_DEPENDS+=	gcc7>0:${PORTSDIR}/lang/gcc7
RUN_DEPENDS+=	gcc8-devel>0:${PORTSDIR}/lang/gcc8-devel
RUN_DEPENDS+=	gcc9-devel>0:${PORTSDIR}/lang/gcc9-devel
RUN_DEPENDS+=	go>0:${PORTSDIR}/lang/go
RUN_DEPENDS+=	rust>0:${PORTSDIR}/lang/rust
RUN_DEPENDS+=	help2man>0:${PORTSDIR}/misc/help2man

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
