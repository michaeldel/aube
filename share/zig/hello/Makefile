ZIGC ?= zig build-exe

hello: hello.zig
	$(ZIGC) $^

.PHONY: clean
clean:
	$(RM) hello

.PHONY: distclean
distclean: clean
	$(RM) -r zig-cache

