PORTNAME=      rescrv-desktop
PORTVERSION=   20180220
CATEGORIES=    rescrv
MASTER_SITES=  # none
DISTFILES=     # none
EXTRACT_ONLY=  # none

MAINTAINER=    robert@rescrv.net
COMMENT=       desktop meta package

NO_BUILD=      yes
NO_WRKSUBDIR=  yes

RUN_DEPENDS+=	rescrv-minimal>0:${PORTSDIR}/rescrv/minimal
RUN_DEPENDS+=	zip>0:${PORTSDIR}/archivers/zip
RUN_DEPENDS+=	dmenu>0:${PORTSDIR}/x11/dmenu
RUN_DEPENDS+=	parcellite>0:${PORTSDIR}/deskutils/parcellite
RUN_DEPENDS+=	gpicview>0:${PORTSDIR}/graphics/gpicview
RUN_DEPENDS+=	sudo>0:${PORTSDIR}/security/sudo
RUN_DEPENDS+=	nitrogen>0:${PORTSDIR}/sysutils/nitrogen
RUN_DEPENDS+=	mplayer>0:${PORTSDIR}/multimedia/mplayer
RUN_DEPENDS+=	chromium>0:${PORTSDIR}/www/chromium
RUN_DEPENDS+=	firefox>0:${PORTSDIR}/www/firefox
RUN_DEPENDS+=	conky>0:${PORTSDIR}/sysutils/conky
RUN_DEPENDS+=	dmenu>0:${PORTSDIR}/x11/dmenu
RUN_DEPENDS+=	ledger>0:${PORTSDIR}/finance/ledger
RUN_DEPENDS+=	xf86-input-synaptics>0:${PORTSDIR}/x11-drivers/xf86-input-synaptics
RUN_DEPENDS+=	xf86-video-ati>0:${PORTSDIR}/x11-drivers/xf86-video-ati
RUN_DEPENDS+=	xf86-video-intel>0:${PORTSDIR}/x11-drivers/xf86-video-intel
RUN_DEPENDS+=	bitstream-vera>0:${PORTSDIR}/x11-fonts/bitstream-vera
RUN_DEPENDS+=	noto>0:${PORTSDIR}/x11-fonts/noto
RUN_DEPENDS+=	terminus-font>0:${PORTSDIR}/x11-fonts/terminus-font
RUN_DEPENDS+=	terminus-ttf>0:${PORTSDIR}/x11-fonts/terminus-ttf
RUN_DEPENDS+=	xfontsel>0:${PORTSDIR}/x11-fonts/xfontsel
RUN_DEPENDS+=	hs-xmobar>0:${PORTSDIR}/x11/hs-xmobar
RUN_DEPENDS+=	rxvt-unicode>0:${PORTSDIR}/x11/rxvt-unicode
RUN_DEPENDS+=	setxkbmap>0:${PORTSDIR}/x11/setxkbmap
RUN_DEPENDS+=	scrot>0:${PORTSDIR}/graphics/scrot
RUN_DEPENDS+=	slim>0:${PORTSDIR}/x11/slim
RUN_DEPENDS+=	gtk-murrine-engine>0:${PORTSDIR}/x11-themes/gtk-murrine-engine
RUN_DEPENDS+=	hs-xmonad>0:${PORTSDIR}/x11-wm/hs-xmonad
RUN_DEPENDS+=	hs-xmonad-contrib>0:${PORTSDIR}/x11-wm/hs-xmonad-contrib
RUN_DEPENDS+=	xmodmap>0:${PORTSDIR}/x11/xmodmap
RUN_DEPENDS+=	xorg-minimal>0:${PORTSDIR}/x11/xorg-minimal
RUN_DEPENDS+=	xrandr>0:${PORTSDIR}/x11/xrandr
RUN_DEPENDS+=	xrdb>0:${PORTSDIR}/x11/xrdb
RUN_DEPENDS+=	xscreensaver>0:${PORTSDIR}/x11/xscreensaver
RUN_DEPENDS+=	xset>0:${PORTSDIR}/x11/xset
RUN_DEPENDS+=	xsetroot>0:${PORTSDIR}/x11/xsetroot
RUN_DEPENDS+=	xauth>0:${PORTSDIR}/x11/xauth
RUN_DEPENDS+=	xbacklight>0:${PORTSDIR}/x11/xbacklight
RUN_DEPENDS+=	awscli>0:${PORTSDIR}/devel/awscli

do-install: build
		@${DO_NADA}

.include <bsd.port.mk>
