# alist-freebsd
Automatically build alist (FreeBSD version)

It seems many people use this project as a template to build other apps for FreeBSD.

Actually, in many situations, this will be not neccessary.

Only apps that requires cgo (like alist) are needed to use a native FreeBSD environment to build, as currently no C cross-compiler for BSD platform exists.

If the app is written in pure Go (and has no cgo depenencies), you can simply using the `go` tool with GOOS=freebsd variable to build a FreeBSD binary.
