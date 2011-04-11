# Maintainer: Antoine Martin <antoine AT openance DOT com>
pkgname=ec2arch
pkgver=1.0
pkgrel=2
pkgdesc="Initial script for EC2"
arch=(any)
url="http://github.com/antoinemartin/ec2arch"
license=('BSD')
depends=(initscripts)
source=(http://github.com/antoinemartin/ec2arch/raw/master/ec2)

build() {
  cd "$srcdir"
}

package() {
  cd "$srcdir"
  install -m755 -D ec2 "$pkgdir/etc/rc.d/ec2"
}

# vim:set ts=2 sw=2 et:

md5sums=('3f36d53aafa19396d5e56e1df48f5c02')
