PORTNAME=      rescrv-mail
PORTVERSION=   20161006
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
RUN_DEPENDS+=	p5-Mail-Box>0:${PORTSDIR}/mail/p5-Mail-Box
RUN_DEPENDS+=	p5-Mail-Tools>0:${PORTSDIR}/mail/p5-Mail-Tools
RUN_DEPENDS+=	p5-File-Which>0:${PORTSDIR}/sysutils/p5-File-Which
RUN_DEPENDS+=	p5-String-ShellQuote>0:${PORTSDIR}/textproc/p5-String-ShellQuote

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
