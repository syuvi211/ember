# Maintainer: Rachel Litjens
pkgname=ember
pkgver=2.0
pkgrel=0
pkgdesc="Ember — a minimal AUR helper written in Ruby"
arch=('x86_64' 'aarch64')
url="https://github.com/syuvi211/ember"
license=('GPL')
depends=('ruby' 'curl' 'git')
makedepends=()
source=()
sha256sums=()

package() {
    install -Dm755 "$startdir/bin/ember" "$pkgdir/usr/bin/ember"
    install -Dm755 "$startdir/bin/ember" "$pkgdir/usr/bin/emb"
    install -Dm644 "$startdir/README.md" "$pkgdir/usr/share/doc/ember/README.md"
}
