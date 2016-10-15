PORTNAME=		rescrv-poudriere
PORTVERSION=	20161015
CATEGORIES=		rescrv
MASTER_SITES=	# none
DISTFILES=		# none
EXTRACT_ONLY=	# none

MAINTAINER=	robert@rescrv.net
COMMENT=	Meta port for poudriere builder

NO_BUILD=		yes
NO_WRKSUBDIR=	yes

RUN_DEPENDS+=	rescrv-minimal>0:${PORTSDIR}/rescrv/minimal
RUN_DEPENDS+=	portmaster>0:${PORTSDIR}/ports-mgmt/portmaster
RUN_DEPENDS+=	portshaker>0:${PORTSDIR}/ports-mgmt/portshaker
RUN_DEPENDS+=	poudriere>0:${PORTSDIR}/ports-mgmt/poudriere

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
