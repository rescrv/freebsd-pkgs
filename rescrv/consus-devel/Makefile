PORTNAME=      rescrv-consus-devel
PORTVERSION=   20161003
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       consus-devel meta package

NO_BUILD=      yes
NO_WRKSUBDIR=  yes

RUN_DEPENDS+=	glog>0:${PORTSDIR}/devel/glog
RUN_DEPENDS+=	sparsehash>0:${PORTSDIR}/devel/sparsehash
RUN_DEPENDS+=	leveldb>0:${PORTSDIR}/databases/leveldb

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
