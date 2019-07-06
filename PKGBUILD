pkgname="jak-social-parler"
pkgver=1.0
pkgrel=1
pkgdesc="Parler"
arch=('x86_64')
url="https://parler.com"
license=('GPL')
depends=('jade-application-kit-git')
source=("git+https://github.com/realKennyStrawn93/triggerbox-parler#branch=master")

package() {
  cd $srcdir
  mkdir -p $pkgdir/usr/bin
  mkdir -p $pkgdir/usr/share/applications
  cp $srcdir/parler.desktop $pkgdir/usr/share/applications
  cp $srcdir/parler $pkgdir/usr/bin
  cp $srcdir/parler-wrapper $pkgdir/usr/bin
}
