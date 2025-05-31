all:
	mkdir out
	for i in *.svg; do scour --remove-descriptive-elements --enable-comment-stripping --enable-id-stripping --shorten-ids $$i out/$$i; done
	mv out/*.svg .
	rmdir out
