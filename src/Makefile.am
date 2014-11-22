install:
	$(MKDIR_P) $(DESTDIR)/$(prefix)/opt
	$(MKDIR_P) $(DESTDIR)/$(prefix)/srv
	$(MKDIR_P) $(DESTDIR)/$(prefix)/srv/ftp
	$(MKDIR_P) $(DESTDIR)/$(prefix)/srv/http
	$(MKDIR_P) $(DESTDIR)/$(prefix)/boot
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/opt
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/log
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/log/old
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/spool
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/spool/mail
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/local
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/mail
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/run
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/lock
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/games
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/cache
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/lib
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/lib/misc
	$(MKDIR_P) $(DESTDIR)/$(prefix)/var/empty
	$(MKDIR_P) $(DESTDIR)/$(prefix)/proc
	$(MKDIR_P) $(DESTDIR)/$(prefix)/sbin
	$(MKDIR_P) $(DESTDIR)/$(prefix)/run
	$(MKDIR_P) $(DESTDIR)/$(prefix)/dev
	$(MKDIR_P) $(DESTDIR)/$(prefix)/mnt
	$(MKDIR_P) $(DESTDIR)/$(prefix)/etc
	$(MKDIR_P) $(DESTDIR)/$(prefix)/etc/skel
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/include
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/local
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/local/man
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/local/include
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/local/sbin
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/local/etc
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/local/share
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/local/share/man
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/local/src
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/local/games
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/local/bin
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/local/lib
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/sbin
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/share
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/share/man
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/share/man/man5
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/share/man/man3
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/share/man/man1
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/share/man/man8
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/share/man/man4
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/share/man/man2
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/share/man/man7
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/share/man/man6
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/share/licenses
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/share/misc
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/src
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/bin
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/lib
	$(MKDIR_P) $(DESTDIR)/$(prefix)/usr/lib/modprobe.d
	$(MKDIR_P) $(DESTDIR)/$(prefix)/home
	$(MKDIR_P) $(DESTDIR)/$(prefix)/bin
	$(MKDIR_P) $(DESTDIR)/$(prefix)/sys
	$(INSTALL) -d -m 0750 $(DESTDIR)/$(prefix)/root
	$(INSTALL) -d -m 1777 $(DESTDIR)/$(prefix)/tmp $(DESTDIR)/$(prefix)/var/tmp
	$(LN_S) -f $(DESTDIR)/$(prefix)/usr/lib $(DESTDIR)/$(prefix)/lib
	$(LN_S) -f $(DESTDIR)/$(prefix)/usr/lib $(DESTDIR)/$(prefix)/lib64
	$(LN_S) -r $(DESTDIR)/$(prefix)/usr/lib $(DESTDIR)/$(prefix)/usr/lib64

uninstall:
	rm -r $(DESTDIR)/$(prefix)/*

