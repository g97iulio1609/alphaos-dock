# Maintainer: Giulio Leone <giulio97.leone@gmail.com>
pkgname=alphaos-dock
pkgver=20140908
pkgrel=1
pkgdesc="This provides to Alpha OS dock."
arch=('i686' 'x86_64')
url="https://github.com/g97iulio1609/alphaos-dock"
license=('LGPLv2+')
depends=('gnome-shell')
makedepends=('git')
replaces=('gnome-shell')
_repanthalver=0.3.1
provides=('alphaos-dock')
source=("git+https://github.com/g97iulio1609/alphaos-dock.git")
md5sums=('SKIP')

package() {
    cd "${srcdir}/${pkgname}"

    mkdir -p "${pkgdir}"/usr/share/gnome-shell
    cp -R usr/share/gnome-shell "${pkgdir}"/usr/share/


}
