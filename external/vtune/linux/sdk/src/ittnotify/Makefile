OBJ := ittnotify_static.o jitprofiling.o

LIBNAME := libittnotify.a

INCLUDE += -I ../../../include

CFLAGS += $(INCLUDE) -fPIC

.PHONY: all
all: $(LIBNAME)

$(LIBNAME): $(OBJ)
	$(AR) rcs $@ $^

.PHONY: clean
clean:
	@$(RM) $(LIBNAME) $(OBJ)
