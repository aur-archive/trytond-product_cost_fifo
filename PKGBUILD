# Maintainer: Robin Baumgartner <robin@baumgartners.ch>
pkgname=trytond-product_cost_fifo
_pkgname=trytond_product_cost_fifo
pkgver=2.2.0
_pkgdir=2.2
pkgrel=1
pkgdesc="The product_cost_fifo module of the Tryton application platform"
arch=('any')
url='http://www.tryton.org/'
license=('GPL3')
groups=('trytond-modules')
depends=('trytond>=2.2' 'trytond-product>=2.2' 'trytond-stock>=2.2')
makedepends=('python2-distribute')
source=("http://downloads.tryton.org/$_pkgdir/$_pkgname-$pkgver.tar.gz")
md5sums=("80f52f182d49ed42c27a3c6ad106042a")

build() {
  cd $srcdir/$_pkgname-$pkgver
  python setup.py install --root=$pkgdir
}