# Maintainer: Wojtek Gawroński <afronski@gmail.com>
# https://github.com/afronski/aur-packages/tree/master/aur/nomad-bin

pkgname=nomad-bin
pkgver=0.5.4
pkgrel=1
pkgdesc="Easily deploy applications at any scale - A Distributed, Highly Available, Datacenter-Aware Scheduler"
arch=('i686' 'x86_64')
url="https://nomadproject.io/"
license=('MPL')
provides=('nomad')
source_i686=("https://releases.hashicorp.com/nomad/${pkgver}/nomad_${pkgver}_linux_386.zip")
source_x86_64=("https://releases.hashicorp.com/nomad/${pkgver}/nomad_${pkgver}_linux_amd64.zip")
sha256sums_i686=('3aecb8cd130c228524973f8ee2418c595bed57d3e778de7deb2431a665677012')
sha256sums_x86_64=('ed9eb471b9f5bab729cfa402db5aa56e1d935c328ac48327267e0ea53568d5c2')

package() {
	install -Dm0755 nomad "$pkgdir/usr/bin/nomad"
}
