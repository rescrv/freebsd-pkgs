PORTNAME=      rescrv-executive
PORTVERSION=   20190928
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       executive meta package

NO_MTREE=      yes
NO_BUILD=      yes
NO_WRKSUBDIR=  yes

USES=          metaport

RUN_DEPENDS+=	taskwarrior>0:${PORTSDIR}/deskutils/taskwarrior
RUN_DEPENDS+=	taskd>0:${PORTSDIR}/deskutils/taskd
RUN_DEPENDS+=	vit>0:${PORTSDIR}/deskutils/vit

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
