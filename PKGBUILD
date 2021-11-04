  # Maintainer: Mathew Li
pkgname=sddm-theme-matuusos
pkgver=r53.2b72ef6
pkgrel=1
pkgdesc="login theme for the SDDM display manager."
arch=('any')
url='https://MatuusOS.github.io'
license=('MIT')
depends=('sddm>=0.18')
makedepends=('git')
provides=("sddm-theme-matuusos")
conflicts=("sddm-theme-matuusos")
source=('https://github.com/MatusModder/sddm-theme-matuusos.git')
sha256sums=('SKIP')
  
  install() { 
  cd "$srcdir/sddm-theme-matuusos"
  install -Dm644 "Main.qml" "$pkgdir/usr/share/sddm/themes/sddm-theme-matuusos/Main.qml"
  install -Dm644 "theme.conf" "$pkgdir/usr/share/sddm/themes/sddm-theme-matuusos/theme.conf"
  install -Dm644 "metadata.desktop" "$pkgdir/usr/share/sddm/themes/sddm-theme-matuusos/metadata.desktop"
  install -Dm644 *.jpg "$pkgdir/usr/share/sddm/themes/sddm-theme-matuusos/{}" \;
  }

pkgver() {
  cd "$srcdir/sugar-candy"
    printf "r%s.%s" "$(git rev-list --count HEAD)" "$(git rev-parse --short HEAD)"
}
