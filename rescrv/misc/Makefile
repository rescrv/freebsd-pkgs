PORTNAME=      rescrv-misc
PORTVERSION=   20230904
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       misc meta package

NO_MTREE=      yes
NO_BUILD=      yes
NO_WRKSUBDIR=  yes

USES=          metaport

RUN_DEPENDS+=	opensmtpd>0:${PORTSDIR}/mail/opensmtpd

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
