PORTNAME=      rescrv-mail
PORTVERSION=   20161004
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       mail meta package

NO_BUILD=      yes
NO_WRKSUBDIR=  yes

RUN_DEPENDS+=	rescrv-minimal>0:${PORTSDIR}/rescrv/minimal
RUN_DEPENDS+=	msmtp>0:${PORTSDIR}/mail/msmtp
RUN_DEPENDS+=	mutt>0:${PORTSDIR}/mail/mutt
RUN_DEPENDS+=	notmuch>0:${PORTSDIR}/mail/notmuch
RUN_DEPENDS+=	offlineimap>0:${PORTSDIR}/mail/offlineimap

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
