all:
	node build/genProtocol -p
	
release: all
	git commit -am "$(MESSAGE)"
	git push