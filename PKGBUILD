# Maintainer: James Bulmer <nekinie@gmail.com>

pkgname="python2-oslo-rootwtap"
pkgver=1.1.0
pkgrel=1
pkgdesc="Oslo rootwrap"
arch=("i686" "x86_64")
url="https://pypi.python.org/pypi/oslo.rootwrap/"
license=("Apache")

depends=(
  "python2"
  "python2-six"
)
source=("https://pypi.python.org/packages/source/o/oslo.rootwrap/oslo.rootwrap-${pkgver}.tar.gz")
md5sums=("eb5e7e7b089d3d4a30abcc284e2490a6")

package() {
  cd "${srcdir}/oslo.rootwrap-${pkgver}/"
  python2 setup.py install --root="${pkgdir}" --optimize=1
}