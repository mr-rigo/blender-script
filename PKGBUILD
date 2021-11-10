pkgname='blender-script'
pkgver=0.1.1
pkgrel=1
pkgdesc="Shebang blender script"
arch=(any)

depends=(python blender)

package() {
    install -d $pkgdir/usr/bin/
    install -t $pkgdir/usr/bin/ -m775 $startdir/blender-script    
}

# makepkg -fci; rm *.zst
