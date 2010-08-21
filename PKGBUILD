# Maintainer: Yejun Yang <yejunx AT gmail DOT com>
pkgname=ec2arch
pkgver=1.0
pkgrel=1
pkgdesc="Initial script for EC2"
arch=(any)
url="http://github.com/yejun/ec2arch"
license=('BSD')
depends=(initscripts)
source=(http://github.com/yejun/ec2arch/raw/master/ec2)
md5sums=('73a0c7930d100d0435144b8a5cbd57e2')

build() {
  cd "$srcdir"
}

package() {
  cd "$srcdir"
  install -m755 -D ec2 "$pkgdir/etc/rc.d/ec2"
}

# vim:set ts=2 sw=2 et:
