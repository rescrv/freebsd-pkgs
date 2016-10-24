PORTNAME=      rescrv-minimal
PORTVERSION=   20161017
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       minimal meta package

NO_BUILD=      yes
NO_WRKSUBDIR=  yes

RUN_DEPENDS+=	vim-lite>0:${PORTSDIR}/editors/vim-lite
RUN_DEPENDS+=	wget>0:${PORTSDIR}/ftp/wget
RUN_DEPENDS+=	rsync>0:${PORTSDIR}/net/rsync
RUN_DEPENDS+=	keychain>0:${PORTSDIR}/security/keychain
RUN_DEPENDS+=	bash>0:${PORTSDIR}/shells/bash
RUN_DEPENDS+=	zsh>0:${PORTSDIR}/shells/zsh
RUN_DEPENDS+=	tmux>0:${PORTSDIR}/sysutils/tmux
RUN_DEPENDS+=	w3m>0:${PORTSDIR}/www/w3m

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
