PORTNAME=      rescrv-all
PORTVERSION=   20230909
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
RUN_DEPENDS+=	rescrv-devel>0:${PORTSDIR}/rescrv/devel
RUN_DEPENDS+=	rescrv-multimedia>0:${PORTSDIR}/rescrv/multimedia
RUN_DEPENDS+=	rescrv-misc>0:${PORTSDIR}/rescrv/misc

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
