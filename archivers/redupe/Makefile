# $FreeBSD$

PORTNAME=	redupe
PORTVERSION=	0.1.0
CATEGORIES=	archivers
MASTER_SITES=	http://rescrv.net/src/

MAINTAINER=	robert@rescrv.net
COMMENT=	Forward error correction tools for backup and long term storage

LICENSE=	BSD3CLAUSE
LICENSE_FILE=	${WRKSRC}/LICENSE

LIB_DEPENDS=	libpopt.so:devel/popt

GNU_CONFIGURE=	yes

CPPFLAGS+=	-I${LOCALBASE}/include
LDFLAGS+=	-L${LOCALBASE}/lib

.include <bsd.port.mk>
