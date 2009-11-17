# Contributor: Randy Morris <randy rsontech net>
pkgname=shop
pkgver=1.0.1
pkgrel=1
pkgdesc="Show permissions at each level of a given path."
arch=('i686' 'x86_64')
url="http://rsontech.net/projects/shop"
license=('None')
depends=('bash')
source=(http://github.com/rson/${pkgname}/raw/master/${pkgname})
md5sums=('e7ea3ea3be526e9eacf8a810a6348b63')
build() {
  cd ${srcdir}
  install -D -m755 ${pkgname} ${pkgdir}/usr/bin/${pkgname}
}
