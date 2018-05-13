# $FreeBSD$

PORTNAME=	encryptify
PORTVERSION=	0.1.1
CATEGORIES=	security
MASTER_SITES=	http://rescrv.net/src/

MAINTAINER=	robert@rescrv.net
COMMENT=	Encryption tool for asymmetric streams of encrypted data.

LICENSE=	BSD3CLAUSE
#TODO: update this when a new release hits
#LICENSE_FILE=	${WRKSRC}/LICENSE

USES=		libtool
GNU_CONFIGURE=	yes

CPPFLAGS+=	-I${LOCALBASE}/include
LDFLAGS+=	-L${LOCALBASE}/lib

.include <bsd.port.mk>
