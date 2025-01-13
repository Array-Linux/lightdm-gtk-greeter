pkgname=arraylinux-greeter
pkgver=1.0
pkgrel=1
pkgdesc="Arraylinux configuration file for LightDM GTK Greeter"
arch=('x86_64')
url="https://github.com/Array-Linux/PKGBUILDS/"
license=('GPL')
depends=('lightdm-gtk-greeter')
source=("$pkgname-$pkgver.tar.gz::https://github.com/Array-Linux/PKGBUILDS/blob/main/arraylinux-greeter/$pkgname-$pkgver.tar.gz")
sha256sums=('SKIP')

package() {
    install -dm777 "$pkgdir/etc/lightdm/"
    cp "$srcdir/lightdm-gtk-greeter.conf" "$pkgdir/etc/lightdm/lightdm-gtk-greeter.conf"
}
