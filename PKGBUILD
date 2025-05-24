cat > PKGBUILD << 'EOF'
pkgname=nite
pkgver=1.0
pkgrel=1
pkgdesc="fun terminal stuff"
arch=('any')
url="https://github.com/pgpz/nite"
license=('MIT')
depends=('python' 'python-pyfiglet')
source=("nite")
md5sums=('SKIP')

package() {
    install -Dm755 "$srcdir/nite" "$pkgdir/usr/bin/nite"
}
EOF