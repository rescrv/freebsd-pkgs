PORTNAME=      rescrv-writing
PORTVERSION=   20230407
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       writing meta package

NO_MTREE=      yes
NO_BUILD=      yes
NO_WRKSUBDIR=  yes

USES=          metaport

RUN_DEPENDS+=	rescrv-minimal>0:${PORTSDIR}/rescrv/minimal
RUN_DEPENDS+=	gnuplot-lite>0:${PORTSDIR}/math/gnuplot-lite
RUN_DEPENDS+=	hs-pandoc>0:${PORTSDIR}/textproc/hs-pandoc
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}markdown>0:${PORTSDIR}/textproc/py-markdown
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}pygments>0:${PORTSDIR}/textproc/py-pygments
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}pelican>0:${PORTSDIR}/www/py-pelican
RUN_DEPENDS+=	tidy4>0:${PORTSDIR}/www/tidy
USES= python

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
