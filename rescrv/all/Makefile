PORTNAME=      rescrv-all
PORTVERSION=   20180416
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       all meta package

NO_BUILD=      yes
NO_WRKSUBDIR=  yes

RUN_DEPENDS+=	rescrv-minimal>0:${PORTSDIR}/rescrv/minimal
RUN_DEPENDS+=	rescrv-builder>0:${PORTSDIR}/rescrv/builder
RUN_DEPENDS+=	rescrv-mail>0:${PORTSDIR}/rescrv/mail
RUN_DEPENDS+=	rescrv-devel>0:${PORTSDIR}/rescrv/devel
RUN_DEPENDS+=	rescrv-consus-devel>0:${PORTSDIR}/rescrv/consus-devel
RUN_DEPENDS+=	rescrv-writing>0:${PORTSDIR}/rescrv/writing
RUN_DEPENDS+=	rescrv-desktop>0:${PORTSDIR}/rescrv/desktop
RUN_DEPENDS+=	rescrv-workstation>0:${PORTSDIR}/rescrv/workstation

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
