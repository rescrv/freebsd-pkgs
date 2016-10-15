PORTNAME=		rescrv-minimal
PORTVERSION=	20161015
CATEGORIES=		rescrv
MASTER_SITES=	# none
DISTFILES=		# none
EXTRACT_ONLY=	# none

MAINTAINER=	robert@rescrv.net
COMMENT=	Meta port for minimal FreeBSD installation

NO_BUILD=		yes
NO_WRKSUBDIR=	yes

RUN_DEPENDS+=	bash:${PORTSDIR}/shells/bash
RUN_DEPENDS+=	keychain:${PORTSDIR}/security/keychain
RUN_DEPENDS+=	rsync:${PORTSDIR}/net/rsync
RUN_DEPENDS+=	tmux:${PORTSDIR}/sysutils/tmux
RUN_DEPENDS+=	vim-lite:${PORTSDIR}/editors/vim-lite
RUN_DEPENDS+=	w3m:${PORTSDIR}/www/w3m
RUN_DEPENDS+=	wget:${PORTSDIR}/ftp/wget
RUN_DEPENDS+=	zsh:${PORTSDIR}/shells/zsh

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
