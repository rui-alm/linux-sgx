OBJ := ittnotify_static.o jitprofiling.o

LIBNAME := libittnotify.a

INCLUDE += -I ../../../include

CFLAGS += $(INCLUDE) -fPIC -Wno-strict-prototypes -frandom-seed=1

.PHONY: all
all: $(LIBNAME)

$(LIBNAME): $(OBJ)
	$(AR) rcsD $@ $^

.PHONY: clean
clean:
	@$(RM) $(LIBNAME) $(OBJ)
