PORTNAME=		rescrv-devel
PORTVERSION=	20161001
CATEGORIES=		rescrv
MASTER_SITES=	# none
DISTFILES=		# none
EXTRACT_ONLY=	# none

MAINTAINER=	robert@rescrv.net
COMMENT=	Meta port for development

NO_BUILD=		yes
NO_WRKSUBDIR=	yes

RUN_DEPENDS+=	rescrv-minimal>0:${PORTSDIR}/rescrv/minimal
RUN_DEPENDS+=	autoconf>0:${PORTSDIR}/devel/autoconf
RUN_DEPENDS+=	autoconf-archive>0:${PORTSDIR}/devel/autoconf-archive
RUN_DEPENDS+=	automake>0:${PORTSDIR}/devel/automake
RUN_DEPENDS+=	bison>0:${PORTSDIR}/devel/bison
RUN_DEPENDS+=	flex>0:${PORTSDIR}/devel/flex
RUN_DEPENDS+=	help2man>0:${PORTSDIR}/misc/help2man
RUN_DEPENDS+=	hs-pandoc>0:${PORTSDIR}/textproc/hs-pandoc
RUN_DEPENDS+=	git>0:${PORTSDIR}/devel/git

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
