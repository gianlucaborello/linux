CFLAGS += -Wall -O2 -I../../../../usr/include
CFLAGS += -I../../../../bld_x64/usr/include

test_objs = test_verifier test_maps test_lru_map

TEST_PROGS := test_verifier test_maps test_lru_map test_kmod.sh
TEST_FILES := $(test_objs)

all: $(test_objs)

include ../lib.mk

clean:
	$(RM) $(test_objs)
