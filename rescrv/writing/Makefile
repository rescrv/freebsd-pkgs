PORTNAME=      rescrv-writing
PORTVERSION=   20161023
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       writing meta package

NO_BUILD=      yes
NO_WRKSUBDIR=  yes

RUN_DEPENDS+=	rescrv-minimal>0:${PORTSDIR}/rescrv/minimal
RUN_DEPENDS+=	gnuplot>0:${PORTSDIR}/math/gnuplot
RUN_DEPENDS+=	py-pelican>0:${PORTSDIR}/www/py-pelican
RUN_DEPENDS+=	tidy4>0:${PORTSDIR}/www/tidy

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
