EXTRA_DIST = \
	LICENSE.CC \
	LICENSE.GPL \
	README.md

themedir = $(datadir)/themes/Blackbird

install-data-hook:
	$(MKDIR_P) 			$(DESTDIR)$(themedir)
	cp -r $(srcdir)/gtk-*		$(DESTDIR)$(themedir)
	cp -r $(srcdir)/metacity-1	$(DESTDIR)$(themedir)
	cp -r $(srcdir)/xfce-notify-4.0	$(DESTDIR)$(themedir)
	cp -r $(srcdir)/xfwm4		$(DESTDIR)$(themedir)
	cp    $(srcdir)/index.theme	$(DESTDIR)$(themedir)

uninstall-hook:
	test -e $(DESTDIR)$(themedir) && rm -rfv $(DESTDIR)$(themedir)
