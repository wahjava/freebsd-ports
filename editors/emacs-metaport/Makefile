PORTNAME=	emacs-metaport
PORTREVISION=	1
DISTVERSION=	1.0.0
CATEGORIES=	editors

MAINTAINER=	emacs@FreeBSD.org
COMMENT=	Emacs meta-port
WWW=		https://freebsd.org/

USES=		metaport

OPTIONS_RADIO=	EMACS
OPTIONS_RADIO_EMACS=	DEFAULT_FULL DEFAULT_NOX DEFAULT_CANNA DEFAULT_WAYLAND \
			DEVEL_FULL DEVEL_NOX
OPTIONS_DEFAULT=	DEFAULT_FULL

DEFAULT_FULL_DESC=	29.x (full flavor)
DEFAULT_NOX_DESC=	29.x (nox flavor)
DEFAULT_CANNA_DESC=	29.x (canna flavor)
DEFAULT_WAYLAND_DESC=	29.x (wayland flavor)
DEVEL_FULL_DESC=	-devel (full flavor)
DEVEL_NOX_DESC=		-devel (nox flavor)

DEFAULT_FULL_RUN_DEPENDS=	emacs:editors/emacs@full
DEFAULT_NOX_RUN_DEPENDS=	emacs:editors/emacs@nox
DEFAULT_CANNA_RUN_DEPENDS=	emacs:editors/emacs@canna
DEFAULT_WAYLAND_RUN_DEPENDS=	emacs:editors/emacs@wayland
DEVEL_FULL_RUN_DEPENDS=		emacs:editors/emacs-devel@full
DEVEL_NOX_RUN_DEPENDS=		emacs:editors/emacs-devel@nox

.include <bsd.port.mk>
