PORTNAME=      rescrv-multimedia
PORTVERSION=   20230904
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       multimedia meta package

NO_MTREE=      yes
NO_BUILD=      yes
NO_WRKSUBDIR=  yes

USES=          metaport

RUN_DEPENDS+=	ffmpeg>0:${PORTSDIR}/multimedia/ffmpeg
RUN_DEPENDS+=	x264>0:${PORTSDIR}/multimedia/x264

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
