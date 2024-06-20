pkgname=soraos-gnome
pkgver=1.1
pkgrel=1
pkgdesc="GNOME settings for SoraOS"
arch=('any')
license=('GPL3')
source=('99_soraos-gnome.gschema.override')
sha256sums=('187fd35e0ee26e7933940e62540aeea4058ca3c83e87d19ee767a2938eb0eacc')

package() {
	install -Dm644 "${srcdir}/99_soraos-gnome.gschema.override" "${pkgdir}/usr/share/glib-2.0/schemas/99_soraos-gnome.gschema.override"
}
