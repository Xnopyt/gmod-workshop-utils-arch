# Maintainer: Xnopyt <billy@xnopyt.info>
pkgname=gmod-workshop-utils-bin
pkgver=1.1
pkgrel=1
pkgdesc="Garry's Mod workshop utilities for arch (gmad and gmpublish)."
arch=('x86_64')
url="https://wiki.garrysmod.com/page/Workshop_Addon_Creation"
depends=(
  'steam'
)
provides=('gmod-workshop-utils-bin')

source=("gmad_linux"
        "gmpublish_linux"
        "libsteam_api.so")

sha512sums=("bdf4f068b1127c0192ed5429c3700a56f45806ab5f872c7a304153dc7a1f81ba26229ee38549917e6f9ad52e4ad421a96915811bb03636cdbe5af579e2ce3b33"
            "a52a7f95f7f8e4b31b74c19104c3383887665e3392639112348acce2029c5d8686f311f7f007e18275f4a2e407c02013e988d243e0f434ffe2ea066f6cca6b73"
            "5aa7bfa0f0a62cbe102aafadfa5dd4269f3dab4fb872b196bcdeb51568fc850c19e67a132df909a27b53f2788b0ec1f4db6b460bebc96b1e870b32d2cbe79f34")

package() {
    install -Dm755 gmad_linux "$pkgdir"/usr/bin/gmad
    install -Dm755 gmpublish_linux "$pkgdir"/usr/bin/gmpublish
    install -Dm755 libsteam_api.so "$pkgdir"/usr/lib32/libsteam_api.so
}
