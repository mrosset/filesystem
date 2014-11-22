install:
	$(MKDIR_P) $(prefix)/opt
	$(MKDIR_P) $(prefix)/srv
	$(MKDIR_P) $(prefix)/srv/ftp
	$(MKDIR_P) $(prefix)/srv/http
	$(MKDIR_P) $(prefix)/boot
	$(MKDIR_P) $(prefix)/var
	$(MKDIR_P) $(prefix)/var/opt
	$(MKDIR_P) $(prefix)/var/log
	$(MKDIR_P) $(prefix)/var/log/old
	$(MKDIR_P) $(prefix)/var/spool
	$(MKDIR_P) $(prefix)/var/spool/mail
	$(MKDIR_P) $(prefix)/var/local
	$(MKDIR_P) $(prefix)/var/mail
	$(MKDIR_P) $(prefix)/var/run
	$(MKDIR_P) $(prefix)/var/lock
	$(MKDIR_P) $(prefix)/var/games
	$(MKDIR_P) $(prefix)/var/cache
	$(MKDIR_P) $(prefix)/var/lib
	$(MKDIR_P) $(prefix)/var/lib/misc
	$(MKDIR_P) $(prefix)/var/empty
	$(MKDIR_P) $(prefix)/proc
	$(MKDIR_P) $(prefix)/sbin
	$(MKDIR_P) $(prefix)/run
	$(MKDIR_P) $(prefix)/dev
	$(MKDIR_P) $(prefix)/mnt
	$(MKDIR_P) $(prefix)/etc
	$(MKDIR_P) $(prefix)/etc/skel
	$(MKDIR_P) $(prefix)/usr
	$(MKDIR_P) $(prefix)/usr/include
	$(MKDIR_P) $(prefix)/usr/local
	$(MKDIR_P) $(prefix)/usr/local/man
	$(MKDIR_P) $(prefix)/usr/local/include
	$(MKDIR_P) $(prefix)/usr/local/sbin
	$(MKDIR_P) $(prefix)/usr/local/etc
	$(MKDIR_P) $(prefix)/usr/local/share
	$(MKDIR_P) $(prefix)/usr/local/share/man
	$(MKDIR_P) $(prefix)/usr/local/src
	$(MKDIR_P) $(prefix)/usr/local/games
	$(MKDIR_P) $(prefix)/usr/local/bin
	$(MKDIR_P) $(prefix)/usr/local/lib
	$(MKDIR_P) $(prefix)/usr/sbin
	$(MKDIR_P) $(prefix)/usr/share
	$(MKDIR_P) $(prefix)/usr/share/man
	$(MKDIR_P) $(prefix)/usr/share/man/man5
	$(MKDIR_P) $(prefix)/usr/share/man/man3
	$(MKDIR_P) $(prefix)/usr/share/man/man1
	$(MKDIR_P) $(prefix)/usr/share/man/man8
	$(MKDIR_P) $(prefix)/usr/share/man/man4
	$(MKDIR_P) $(prefix)/usr/share/man/man2
	$(MKDIR_P) $(prefix)/usr/share/man/man7
	$(MKDIR_P) $(prefix)/usr/share/man/man6
	$(MKDIR_P) $(prefix)/usr/share/licenses
	$(MKDIR_P) $(prefix)/usr/share/misc
	$(MKDIR_P) $(prefix)/usr/src
	$(MKDIR_P) $(prefix)/usr/bin
	$(MKDIR_P) $(prefix)/usr/lib
	$(MKDIR_P) $(prefix)/usr/lib/modprobe.d
	$(MKDIR_P) $(prefix)/home
	$(MKDIR_P) $(prefix)/bin
	$(MKDIR_P) $(prefix)/sys
	$(INSTALL) -d -m 0750 $(prefix)/root
	$(INSTALL) -d -m 1777 $(prefix)/tmp $(prefix)/var/tmp
	$(LN_S) -f $(prefix)/usr/lib $(prefix)/lib
	$(LN_S) -f $(prefix)/usr/lib $(prefix)/lib64
	$(LN_S) -r $(prefix)/usr/lib $(prefix)/usr/lib64

uninstall:
	rm -r $(prefix)/*

