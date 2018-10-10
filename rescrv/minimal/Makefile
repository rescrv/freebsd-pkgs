PORTNAME=      rescrv-minimal
PORTVERSION=   20181010
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       minimal meta package

NO_BUILD=      yes
NO_WRKSUBDIR=  yes

RUN_DEPENDS+=	redupe>0:${PORTSDIR}/archivers/redupe
RUN_DEPENDS+=	bind-tools>0:${PORTSDIR}/dns/bind-tools
RUN_DEPENDS+=	vim-console>0:${PORTSDIR}/editors/vim-console
RUN_DEPENDS+=	wget>0:${PORTSDIR}/ftp/wget
RUN_DEPENDS+=	python2>0:${PORTSDIR}/lang/python2
RUN_DEPENDS+=	python3>0:${PORTSDIR}/lang/python3
RUN_DEPENDS+=	rsync>0:${PORTSDIR}/net/rsync
RUN_DEPENDS+=	signify-port>0:${PORTSDIR}/rescrv/signify
RUN_DEPENDS+=	encryptify>0:${PORTSDIR}/security/encryptify
RUN_DEPENDS+=	keychain>0:${PORTSDIR}/security/keychain
RUN_DEPENDS+=	bash>0:${PORTSDIR}/shells/bash
RUN_DEPENDS+=	zsh>0:${PORTSDIR}/shells/zsh
RUN_DEPENDS+=	puppet5>0:${PORTSDIR}/sysutils/puppet5
RUN_DEPENDS+=	shuf>0:${PORTSDIR}/sysutils/shuf
RUN_DEPENDS+=	stow>0:${PORTSDIR}/sysutils/stow
RUN_DEPENDS+=	tmux>0:${PORTSDIR}/sysutils/tmux
RUN_DEPENDS+=	w3m>0:${PORTSDIR}/www/w3m

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
