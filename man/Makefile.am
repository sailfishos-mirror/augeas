
EXTRA_DIST=$(wildcard *.pod) $(wildcard *.[0-9])

man1_MANS=augtool.1 augparse.1 augmatch.1 augprint.1

%.1: %.pod
	pod2man -c "Augeas" -r "Augeas $(VERSION)" $< > $@
