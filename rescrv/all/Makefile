PORTNAME=      rescrv-all
PORTVERSION=   20210917
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       all meta package

NO_MTREE=      yes
NO_BUILD=      yes
NO_WRKSUBDIR=  yes

USES=          metaport

RUN_DEPENDS+=	rescrv-minimal>0:${PORTSDIR}/rescrv/minimal
RUN_DEPENDS+=	rescrv-builder>0:${PORTSDIR}/rescrv/builder
RUN_DEPENDS+=	rescrv-mail>0:${PORTSDIR}/rescrv/mail
RUN_DEPENDS+=	rescrv-devel>0:${PORTSDIR}/rescrv/devel
RUN_DEPENDS+=	rescrv-executive>0:${PORTSDIR}/rescrv/executive
RUN_DEPENDS+=	rescrv-writing>0:${PORTSDIR}/rescrv/writing
RUN_DEPENDS+=	rescrv-photography>0:${PORTSDIR}/rescrv/photography
RUN_DEPENDS+=	rescrv-mail-server>0:${PORTSDIR}/rescrv/mail-server

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
