NAME =			ubuntu
VERSION =		vivid
VERSION_ALIASES =	15.04 latest
TITLE =			Ubuntu Vivid
DESCRIPTION =		Ubuntu Vivid (15.04)
SOURCE_URL =		https://github.com/scaleway/image-ubuntu
VENDOR_URL =		http://www.ubuntu.com

IMAGE_NAME =		Ubuntu Vivid (15.04 latest)
IMAGE_BOOTSCRIPT =	latest
IMAGE_VOLUME_SIZE =	50G


##
## Image tools  (https://github.com/scaleway/image-tools)
##
all:	../docker-rules.mk
../docker-rules.mk:
	$(MAKE) -C .. docker-rules.mk
-include ../docker-rules.mk
