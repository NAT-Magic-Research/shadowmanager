ShadowManager - A shadowsocks manager
---

Copyright MagicNAT 2015

### Usage

ShadowManager is a script to maintaince multiple shadowsocks server with different encryption method at a time.

	usage: shadowmanager add <port> <password> <method>
	                     start
	                     stop
	                     restart
	                     show
	                     remove <id>

commands explained:

	add:     add a server to shadowmanager handler, accepting 3 parameters,
	         port, password and method.
	start:   start shadowmanager, no parameters required.
	stop:    stop shadowmanager, no parameters required.
	restart: restart shadowmanager, no parameters required.
	show:    show all the servers handling, no parameters required.
	remove:  remove server with given ID. Use "show" command to show all
	         servers, accepting 1 parameter, server ID.

### Override & Include

To change the way that shadowmanager act which not able to be adjust in configure file, the overrides and includes might be needed. The former one read after the shdowmanager script loaded, the latter one read before it. 

### License

MIT License
