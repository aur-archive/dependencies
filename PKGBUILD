# Maintainer: megadriver <megadriver at gmx dot com>

pkgname=dependencies
pkgver=3
pkgrel=2
pkgdesc="Visualize dependencies of Linux binaries and libraries"
arch=(any)
url="http://domseichter.blogspot.be/2008/02/visualize-dependencies-of-binaries-and.html"
license=('unknown')
depends=('bash' 'graphviz')
source=(http://krename.sf.net/data/scripts/dependencies.sh)
md5sums=('cf9f43e1dd7aaa3d07a0d6e98ddac20c')

package() {
  install -Dm755 $srcdir/$pkgname.sh $pkgdir/usr/bin/$pkgname
}
