pkgname=hugo
pkgver=0.16
pkgrel=1
pkgdesc="Fast and Flexible Static Site Generator in Go"
arch=('x86_64')
url="http://hugo.spf13.com/"
license=('Apache')

source=("https://github.com/spf13/hugo/releases/download/v${pkgver}/${pkgname}_${pkgver}_linux-64bit.tgz")
sha256sums=('13e299dc45bea4fad5bdf8c2640305a5926e2acd02c3aa03b7864403e513920e')


package() {
  install -Dm755 "${srcdir}/${pkgname}" "${pkgdir}/usr/bin/${pkgname}"
  install -Dm644 "${srcdir}/LICENSE.md" "${pkgdir}/usr/share/licenses/${pkgname}/LICENSE"
} 
