PORTNAME=      rescrv-minimal
PORTVERSION=   20240302
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       minimal meta package

NO_MTREE=      yes
NO_BUILD=      yes
NO_WRKSUBDIR=  yes

USES=          metaport

RUN_DEPENDS+=	redupe>0:${PORTSDIR}/archivers/redupe
RUN_DEPENDS+=	vim>0:${PORTSDIR}/editors/vim@console
RUN_DEPENDS+=	python3>0:${PORTSDIR}/lang/python3
RUN_DEPENDS+=	rsync>0:${PORTSDIR}/net/rsync
RUN_DEPENDS+=	signify-port>0:${PORTSDIR}/rescrv/signify
RUN_DEPENDS+=	keychain>0:${PORTSDIR}/security/keychain
RUN_DEPENDS+=	encryptify>0:${PORTSDIR}/security/encryptify
RUN_DEPENDS+=	bash>0:${PORTSDIR}/shells/bash
RUN_DEPENDS+=	zsh>0:${PORTSDIR}/shells/zsh
RUN_DEPENDS+=	tmux>0:${PORTSDIR}/sysutils/tmux

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
