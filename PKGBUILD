pkgname=2gis-ekaterinburg
pkgver=104
pkgrel=1
pkgdesc="Map of Ekaterinburg for 2GIS, August 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/ekaterinburg/products/download#linux"
license=('custom')
depends=('2gis>=3.14.7.0')
source=("http://download.2gis.com/arhives/2GISData_Ekaterinburg-104.orig.zip")
md5sums=('5f27957be3877daba3567f18a24229ad')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Ekaterinburg.dgdat" "${pkgdir}/opt/2gis/2gis-ekaterinburg.dgdat" || return 1
  
}
