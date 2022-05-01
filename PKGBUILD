# Original PKGBUILD by Mark Wagie (https://aur.archlinux.org/packages/caja-mediainfo-tab)
# Based on caja-mediainfo-tab 1.0.4 PKGBUILD
pkgname=caja-exif-tab
pkgver=2022.05.01
pkgrel=1
pkgdesc="View EXIF informations of file from the properties tab"
arch=('any')
url=""
license=('GPL3')
depends=('python-pyexiftool' 'python-caja')
source=("caja-exif-tab.py")
sha256sums=('SKIP')

package() {
    install -Dm644 "$pkgname.py" -t "$pkgdir/usr/share/caja-python/extensions"
}