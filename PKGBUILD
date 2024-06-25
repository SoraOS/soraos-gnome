pkgname=soraos-gnome
pkgver=1.2
pkgrel=1
pkgdesc="GNOME settings for SoraOS"
arch=('any')
license=('GPL3')
source=('99_soraos-gnome.gschema.override')
sha256sums=('c04102d8d6607ab6af872a10f15e2d46f17dc398fba1f8bcf63fb753cfc451df')

package() {
	install -Dm644 "${srcdir}/99_soraos-gnome.gschema.override" "${pkgdir}/usr/share/glib-2.0/schemas/99_soraos-gnome.gschema.override"
}
