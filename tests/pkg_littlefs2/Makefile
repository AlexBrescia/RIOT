include ../Makefile.tests_common

# Set vfs file and dir buffer sizes
CFLAGS += -DVFS_FILE_BUFFER_SIZE=84 -DVFS_DIR_BUFFER_SIZE=52
# Reduce LFS_NAME_MAX to 31 (as VFS_NAME_MAX default)
CFLAGS += -DLFS_NAME_MAX=31

USEPKG += littlefs2
USEMODULE += embunit

include $(RIOTBASE)/Makefile.include
