PORTNAME=      rescrv-builder
PORTVERSION=   20200423
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       builder meta package

NO_MTREE=      yes
NO_BUILD=      yes
NO_WRKSUBDIR=  yes

USES=          metaport

RUN_DEPENDS+=	rescrv-minimal>0:${PORTSDIR}/rescrv/minimal
RUN_DEPENDS+=	git-lite>0:${PORTSDIR}/devel/git@lite
RUN_DEPENDS+=	portlint>0:${PORTSDIR}/ports-mgmt/portlint
RUN_DEPENDS+=	portshaker>0:${PORTSDIR}/ports-mgmt/portshaker
RUN_DEPENDS+=	poudriere>0:${PORTSDIR}/ports-mgmt/poudriere

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
