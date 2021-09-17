PORTNAME=      rescrv-mail-server
PORTVERSION=   20190505
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       mail-server meta package

NO_MTREE=      yes
NO_BUILD=      yes
NO_WRKSUBDIR=  yes

USES=          metaport

RUN_DEPENDS+=	rescrv-minimal>0:${PORTSDIR}/rescrv/minimal
RUN_DEPENDS+=	dovecot>0:${PORTSDIR}/mail/dovecot
RUN_DEPENDS+=	opendkim>0:${PORTSDIR}/mail/opendkim
RUN_DEPENDS+=	postfix>0:${PORTSDIR}/mail/postfix
RUN_DEPENDS+=	postgrey>0:${PORTSDIR}/mail/postgrey

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
