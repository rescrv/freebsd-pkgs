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

RUN_DEPENDS+=	bash:shells/bash
RUN_DEPENDS+=	keychain:security/keychain
RUN_DEPENDS+=	rsync:net/rsync
RUN_DEPENDS+=	tmux:sysutils/tmux
RUN_DEPENDS+=	vim-lite:editors/vim-lite
RUN_DEPENDS+=	w3m:www/w3m
RUN_DEPENDS+=	wget:ftp/wget
RUN_DEPENDS+=	zsh:shells/zsh

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
