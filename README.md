# Oracle java jdk7 debian package

##BUILD DEB PACKAGE
### Download 

    git clone https://github.com/puppetnix/java_7u45.jdk.git
	mkdir build-area
	cd java_7u45.jdk

### Make changes and create release (option)

    git commit -m "after some changes"
	git-dch --qa --git-author -a --release

### Build package

    git-buildpackage --git-tag --git-export-dir=../build-area



