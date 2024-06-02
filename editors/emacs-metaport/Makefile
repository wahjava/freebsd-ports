PORTNAME=	emacs-metaport
DISTVERSION=	1.0.0
CATEGORIES=	editors
MASTER_SITES=	# empty
DISTFILES=	# empty

MAINTAINER=	emacs@FreeBSD.org
COMMENT=	Emacs meta-port
WWW=		https://freebsd.org/

LICENSE=        NA
LICENSE_COMB=   single
LICENSE_NAME=   Non applicable
LICENSE_TEXT=   No licenses are applicable to metaports
LICENSE_PERMS=  dist-mirror dist-sell pkg-mirror pkg-sell auto-accept

PLIST_FILES=	bin/install-emacs

NO_BUILD=	true
NO_CONFIGURE=	true
SUB_FILES=	pkg-install

do-install:
	${MKDIR} ${STAGEDIR}${PREFIX}/bin
	${INSTALL_SCRIPT} ${FILESDIR}/install-emacs ${STAGEDIR}${PREFIX}/bin

.include <bsd.port.mk>
