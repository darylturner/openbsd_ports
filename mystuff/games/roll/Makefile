# $OpenBSD: Makefile.template,v 1.78 2018/07/09 15:00:06 jca Exp $
#
V =	2.4.0

COMMENT =		roll dice specified in a simple and intutive way
DISTNAME =		roll-${V}
REVISION =		1
CATEGORIES =	games

HOMEPAGE =		https://matteocorti.github.io/roll/
MAINTAINER =	Daryl Turner <daryl@layer-eight.uk>

# GPLv2+
PERMIT_PACKAGE_CDROM =	Yes

# uses pledge()

WANTLIB +=	c m

MASTER_SITES =		https://github.com/matteocorti/roll/releases/download/v${V}/

SEPARATE_BUILD =	Yes

CONFIGURE_STYLE =	gnu

.include <bsd.port.mk>
