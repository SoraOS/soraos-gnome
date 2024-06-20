pkgname=soraos-gnome
pkgver=1.0
pkgrel=1
pkgdesc="GNOME settings for SoraOS"
arch=('any')
license=('GPL3')
source=('99_soraos-gnome.gschema.override')
sha256sums=('76d32f91b2b9f75adfe411bc8ddf7535009282142ba9145c9740b4cebe287da4')

package() {
	install -Dm644 "${srcdir}/99_soraos-gnome.gschema.override" "${pkgdir}/usr/share/glib-2.0/schemas/99_soraos-gnome.gschema.override"
}
