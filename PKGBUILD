pkgname=jack_output_for_deadbeef
pkgver=0.2
pkgrel=1
pkgdesc="jack output plugin for DeaDBeeF music player"
arch=("i686" "x86_64")
license=('GPL')
url="http://sourceforge.net/projects/deadbeef/files/plugins/0.5.1"
depends=('deadbeef')
source=("http://sourceforge.net/projects/deadbeef/files/plugins/0.5.1/ddb_jack-0.2.zip")
sha1sums=("c458cf18ac222e4f175df7fb35adf4aa075e5a24")

package() {
   cd "$srcdir/plugins"
   install -D ddb_jack.so "$pkgdir/usr/lib/deadbeef/ddb_jack.so"
}
