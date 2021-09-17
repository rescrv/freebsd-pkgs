PORTNAME=      rescrv-devel
PORTVERSION=   20200423
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       devel meta package

NO_MTREE=      yes
NO_BUILD=      yes
NO_WRKSUBDIR=  yes

USES=          metaport

RUN_DEPENDS+=	rescrv-minimal>0:${PORTSDIR}/rescrv/minimal
RUN_DEPENDS+=	git-lite>0:${PORTSDIR}/devel/git@lite
RUN_DEPENDS+=	rust>0:${PORTSDIR}/lang/rust

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
