PORTNAME=      rescrv-mail-server
PORTVERSION=   20170302
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       mail-server meta package

NO_BUILD=      yes
NO_WRKSUBDIR=  yes

RUN_DEPENDS+=	rescrv-minimal>0:${PORTSDIR}/rescrv/minimal
RUN_DEPENDS+=	dovecot2>0:${PORTSDIR}/mail/dovecot2
RUN_DEPENDS+=	postfix>0:${PORTSDIR}/mail/postfix
RUN_DEPENDS+=	postgrey>0:${PORTSDIR}/mail/postgrey

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
