PORTNAME=      rescrv-writing
PORTVERSION=   20161025
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
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}markdown>0:${PORTSDIR}/textproc/py-markdown
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}pygments>0:${PORTSDIR}/textproc/py-pygments
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}pelican>0:${PORTSDIR}/www/py-pelican
RUN_DEPENDS+=	tidy4>0:${PORTSDIR}/www/tidy
USES= python

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
