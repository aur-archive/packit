# Contributor: ice-man <icemanf@gmail.com>
pkgname=packit
pkgver=1.0
pkgrel="3" 
pkgdesc="Packit (Packet toolkit) is a network auditing tool. Its value is derived from its ability to customize, inject, monitor, and manipulate IP traffic."
makedepends=('libnet')
depends=('libpcap') 
source=("http://packit.sourceforge.net/downloads/$pkgname-$pkgver.tgz")
url="http://packit.sourceforge.net/"
arch=('i686')
md5sums=('270594ff97f6c203131136208bb4d2ca')
license="GPL"

build() {
  cd $startdir/src/$pkgname-$pkgver

   ./configure --prefix=/usr 
  make
  make DESTDIR=$startdir/pkg install

}
