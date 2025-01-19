
# GLPaper (fork of https://todo.sr.ht/~scoopta/glpaper)
GLPaper is a wallpaper program for wlroots based wayland compositors such as sway that allows you to render glsl shaders as your wallpaper

## Dependencies
	libwayland-dev
	libegl-dev
	pkg-config
	meson
## Building
	git clone https://github.com/BobVarioa/glpaper-fork
	cd glpaper
	meson setup build
	ninja -C build
## Installing
	sudo ninja -C build install
## Uninstalling
	sudo ninja -C build uninstall
## Bug Reports
Please file bug reports at https://github.com/BobVarioa/glpaper-fork/issues
