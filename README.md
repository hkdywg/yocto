# 使用说明

##安装依赖


	sudo apt install gawk wget git diffstat unzip texinfo gcc build-essential chrpath socat cpio python3 python3-pip python3-pexpect xz-utils debianutils iputils-ping python3-git python3-jinja2 libegl1-mesa libsdl1.2-dev pylint3 xterm python3-subunit mesa-common-dev zstd liblz4-tool

##使用方法

	git clone https://github.com/hkdywg/yocto.git
	cd poky
	source oe-init-build-env
	bitbake core-image-minimal
	runqemu qemux86-64
