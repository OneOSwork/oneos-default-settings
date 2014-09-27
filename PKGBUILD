# Maintainer: Giulio Leone <giulio97.leone@gmail.com>
pkgname=oneos-default-settings
pkgver=20140908
pkgrel=1
pkgdesc="This provides to Infinity OS's UI."
arch=('i686' 'x86_64')
url="http://infinityos.org/repo/oneosui"
license=('LGPLv2+')
depends=('gnome-shell')
makedepends=('bzr')
replaces=("gnome-shell-common","gnome-shell")
_realver=0.3.1
provides=("oneosui")
_fileurl=http://infinityos.org/repo/oneosui.tar.gz
source=bzr+lp:~infinityosproject/infinityosdevelop/oneos-default-settings
md5sums=('SKIP')

package() {
    cd "${srcdir}/${pkgname}"

    mkdir -p "${pkgdir}"/usr/share/glib-2.0
    cp -R glib-2.0 "${pkgdir}"/usr/share/

    mkdir -p "${pkgdir}"/usr/share/backgrounds
    cp -R backgrounds "${pkgdir}"/usr/share/

}
