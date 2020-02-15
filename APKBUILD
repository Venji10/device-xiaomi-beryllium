# Reference: <https://postmarketos.org/devicepkg>
pkgname="device-xiaomi-beryllium"
pkgdesc="Xiaomi Poco F1"
pkgver=0.3
pkgrel=2
url="https://postmarketos.org"
license="MIT"
arch="aarch64"
options="!check !archcheck"
depends="postmarketos-base linux-xiaomi-beryllium mkbootimg mesa-dri-freedreno"
makedepends="devicepkg-dev"
source="deviceinfo"

build() {
	devicepkg_build $startdir $pkgname
}

package() {
	devicepkg_package $startdir $pkgname
}

sha512sums="67a8cb1060601edca7a5ffdb978dc7ad1de0bdedeb5ac5eccdd73e5504ac43d845cb023aa8de8f16d3e875233d22a4531c301d815381b175a0b7699febfd0024  deviceinfo"
