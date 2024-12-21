pkgname=base
pkgver=3
pkgrel=3
pkgdesc='Minimal package set to define a basic Laniakea installation'
url='https://www.laniakeaos.com'
arch=('any')
license=('GPL')
depends=(
  # very very base
  'filesystem' 'gcc-libs' 'glibc' 'bash'

  # POSIX tools
  'coreutils' 'file' 'findutils' 'gawk' 'grep' 'procps-ng' 'sed' 'tar'

  # standard linux toolset
  'gettext' 'pciutils' 'psmisc' 'shadow' 'util-linux' 'bzip2' 'gzip' 'xz'

  # distro defined requirements
  'licenses' 'pacman' 'archlinux-keyring' 'laniakea-keyring' 'systemd' 'systemd-sysvcompat'

  # networking, ping, etc
  'iputils' 'iproute2'
)
optdepends=(
  'linux: bare metal support'
)

