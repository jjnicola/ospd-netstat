About OSPD-NETSTAT
-------------------

This is a OSP server implementation to allow GVM to remotely control
the netstat tool.
OSPD-NETSTAT can collect open ports on the local system.

Once running, you need to configure the Scanner for Greenbone Vulnerability
Manager, for example via the web interface Greenbone Security Assistant.
Then you can create scan tasks to use this scanner.

OSPD-NETSTAT is licensed under GNU General Public License Version 2 or
any later version.  Please see file COPYING for details.

All parts of OSP-NETSTAT are Copyright (C) by Greenbone Networks GmbH
(see http://www.greenbone.net).


How to start OSPD-NETSTAT
-------------------------

There are no special usage aspects for this module
beyond the general usage guide.

Please follow the general usage guide for ospd-based scanners:

  https://github.com/greenbone/ospd/blob/master/doc/USAGE-ospd-scanner

Noteworthy is that starting a scan requires a ssh credential parameter because
ospd-debsecan needs to log into the target systems to run the locally installed
debsecan tool.
