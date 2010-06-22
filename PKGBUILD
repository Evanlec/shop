# Contributor: Randy Morris <randy rsontech net>
pkgname=shop
pkgver=1.1
pkgrel=1
pkgdesc="Show permissions at each level of a given path."
arch=('i686' 'x86_64')
url="http://rsontech.net/projects/shop"
license=('None')
depends=('bash')
source=(http://github.com/rson/${pkgname}/raw/master/${pkgname})
md5sums=('edadcc10525ed35ac79e8217051444a5')
build() {
  cd ${srcdir}
  install -D -m755 ${pkgname} ${pkgdir}/usr/bin/${pkgname}
}
