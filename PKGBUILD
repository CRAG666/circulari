pkgname=circulari
pkgver=1
pkgrel=1
arch=('any')
pkgdesc="A circular icons pack"
url="https://github.com/CRAG666/circulari"
makedepends=('git')
source=("git+https://github.com/CRAG666/circulari.git")
license=('GPL')
sha256sums=('SKIP')

package() {
  mkdir -p $pkgdir/usr/share/icons/
  cp -a "$srcdir/circulari/circular_icons" "$pkgdir/usr/share/icons/circulari"
  rm -rf "$pkgdir/usr/share/icons/circulari/.git"
}
