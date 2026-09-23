# Maintainer: boronology <boronology@gmail.com>

pkgbase=ttf-genzui
pkgname=(
    ttf-genzui-sans
    ttf-genzui-serif
)

pkgver=0.113
pkgrel=1

pkgdesc='Japanese type family with hentaigana, historical kana and Unicode 18.0 additions.'
arch=(any)
url='https://genzui.mkpo.li/'
source=(
    'https://genzui.mkpo.li/downloads/GenZuiSans-Regular.ttf'
    'https://genzui.mkpo.li/downloads/GenZuiSerif-Regular.ttf'
    'https://genzui.mkpo.li/downloads/OFL.txt'
)
sha256sums=(
    '9f1f84e8c9049350005ebfb710504c34bdea5db2a3ddd3552f678cee698168ac'
    'b104e98d7adb448ca6b834b0e7e7ba59093c17dba2d90dc4cf422fbe3927cd4c'
    'SKIP'
)
license=('OFL-1.1')
arch=('any')

package_ttf-genzui-sans() {
  install -Dm644 -t "$pkgdir/usr/share/fonts/TTF" "GenZuiSans-Regular.ttf"
  install -Dm644 -t "$pkgdir/usr/share/licenses/$pkgname" "OFL.txt"
}


package_ttf-genzui-serif() {
    install -Dm644 -t "$pkgdir/usr/share/fonts/$pkgname" "GenZuiSerif-Regular.ttf"
    install -Dm644 -t "$pkgdir/usr/share/licenses/$pkgname" "OFL.txt"
}
