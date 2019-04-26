all:Ebolamodel.nlogo

install:Ebolamodel.nlogo ../data/Ebolamodel.png
	install --mode 0644 -D Ebolamodel.nlogo ../bin
	install --mode 0644 -D Ebolamodel.nlogo /apps/share64/debian7/netlogo/5.1.0/models/QUBESHub
	install --mode 0644 -D ../data/Ebolamodel.png /apps/share64/debian7/netlogo/5.1.0/models/QUBESHub
	
clean:

distclean: clean
	rm -f ../bin/Ebolamodel.nlogo
	rm -f /apps/share64/debian7/netlogo/5.1.0/models/QUBESHub/Ebolamodel.nlogo
	rm -f /apps/share64/debian7/netlogo/5.1.0/models/QUBESHub/Ebolamodel.png
