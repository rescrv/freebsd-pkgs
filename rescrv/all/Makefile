PORTNAME=      rescrv-all
PORTVERSION=   20230901
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

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
