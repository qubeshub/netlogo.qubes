all:IONTW.nlogo

install:IONTW.nlogo ../data/IONTW.png
	install --mode 0644 -D IONTW.nlogo ../bin
	install --mode 0644 -D IONTW.nlogo /apps/share64/debian7/netlogo/5.1.0/models/QUBESHub
	install --mode 0644 -D ../data/IONTW.png /apps/share64/debian7/netlogo/5.1.0/models/QUBESHub

clean:

distclean: clean
	rm -f ../bin/IONTW.nlogo
	rm -f /apps/share64/debian7/netlogo/5.1.0/models/QUBESHub/IONTW.nlogo
	rm -f /apps/share64/debian7/netlogo/5.1.0/models/QUBESHub/IONTW.png
