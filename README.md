# csc453-fall15-hw1-1-tests

myhtml2txt: $(OFILES)
	$(CC) $(CFLAGS) $(OFILES) -ll -o myhtml2txt
	(cd csc453-fall15-hw1-1-tests && ./run.zsh)  <--- Add this
