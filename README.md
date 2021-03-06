DevOps tools
============

A curated list of development and operational tools for Unix-like operating
systems.

## Databases

* **[squirrelsql](http://squirrel-sql.sourceforge.net/)**: Multi-database
  graphical SQL client. Supports anything JDBC supports (MySQL, Postgres,
  MSSQL, etc).


## Data filtering and transformations

* **[xmlstarlet](http://xmlstar.sourceforge.net/)**: Commandline tools to work
  with XML. Validate (DTD, XSD), XPath, XSLT, modify and visualize XML
  documents.
* **[xlstproc](http://xmlsoft.org/XSLT/xsltproc.html)**: Process XSLT on the
  commandline.
* **[xmllint](http://xmlsoft.org/xmllint.html)**: parses one or more XML
  files, specified on the command line as xmlfile. It prints various types of
  output, depending upon the options selected. It is useful for detecting
  errors both in XML code and in the XML parser itself.
* **[jq](https://stedolan.github.io/jq/)**: a lightweight and flexible
  command-line JSON processor.
* **[meld](http://meldmerge.org/)**: a visual diff and merge tool targeted at
  developers. Meld helps you compare files, directories, and version
  controlled projects. It provides two- and three-way comparison of both files
  and directories, and has support for many popular version control systems.
* **[expect](https://linux.die.net/man/1/expect)**: Systematically interact
  with programs that can't be scripted but require human interaction.


## Dev stubbing

* **[fakesmtp](http://nilhcem.com/FakeSMTP/index.html)**: a Fake SMTP Server
  with GUI for testing emails in applications easily.
* **[tcconfig](https://github.com/thombashi/tcconfig/blob/master/README.rst)**:
  Easy to set up traffic control of network bandwidth/latency/packet
  loss/packet-corruption to a network interface.


## Documentation

* **[pandoc](https://pandoc.org/)**: convert files from one markup format into
  another. Supports a large number of formats.
* **[asciidoc](http://www.methods.co.nz/asciidoc/)**: a text document format
  for writing notes, documentation, articles, books, ebooks, slideshows, web
  pages, man pages and blogs. AsciiDoc files can be translated to many formats
  including HTML, PDF, EPUB, man page.
* **[mkdocs](http://www.mkdocs.org/)**: a fast, simple and downright gorgeous
  static site generator that's geared towards building project documentation.
  Documentation source files are written in Markdown, and configured with a
  single YAML configuration file.


## Filesystems

* **[mhddfs](https://romanrm.net/mhddfs)**: join several filesystems together to
  form a single larger one.
* **[sshfs](https://github.com/libfuse/sshfs)**: allows you to mount a remote
  filesystem using SFTP. Most SSH servers support and enable this SFTP access
  by default, so SSHFS is very simple to use - there's nothing to do on the
  server-side.
* **[squashfs](http://squashfs.sourceforge.net/)**: Create and mount compressed
  filesystem images.
* **[xdiskusage](http://xdiskusage.sourceforge.net/)**: Visually represent
  disk usage in and below a directory.
* **[rsync](https://rsync.samba.org/)**: Provides fast, reliable, configurable
  incremental file transfer on local disk or over the network. Archive,
  mirror, etc.


## Linting

* **[httpolice](https://github.com/vfaronov/httpolice)**: a validator for HTTP
  requests and responses. It can spot bad header syntax, inappropriate status
  codes, and other interoperability problems in your HTTP server or client.
* **[shellcheck](http://www.shellcheck.net/)**: a tool that gives warnings and
  suggestions for bash/sh shell scripts.


## Networking

* **[mtr](https://www.bitwizard.nl/mtr/)**: My TraceRoute. combines the
  functionality of the 'traceroute' and 'ping' programs in a single network
  diagnostic tool.
* **[lft](https://linux.die.net/man/8/lft)**: display the route packets take
  to a network host/socket using one of several layer-4 protocols and
  methods. Basically traceroute for TCP, UDP and ICMP.
* **[netcat](https://en.wikipedia.org/wiki/Netcat)**: a computer networking
  utility for reading from and writing to network connections using TCP or
  UDP. Replacement for telnet. Can also act as a server.
* **[sshuttle](https://github.com/apenwarr/sshuttle)**: Sshutle is VPN over
  SSH without requiring a remote VPN server or admin rights. Instead, it
  builds up an ssh session and than locally forwards traffic over it by
  creating local PREROUTING firewall rules.
* **[stunnel](https://www.stunnel.org/)**: a proxy designed to add TLS
  encryption functionality to existing clients and servers without any changes
  in the programs' code.
* **[tcptraceroute](https://linux.die.net/man/1/tcptraceroute)**: A traceroute
  implementation using TCP packets
* **[wavemon](https://github.com/uoaerg/wavemon)**: an ncurses-based
  monitoring application for wireless network devices.
* **[rinetd](https://www.boutell.com/rinetd/)**: Redirects TCP connections
  from one IP address and port to another. 
* **[dig](https://en.wikipedia.org/wiki/Dig_(command))**: The multitool for
  DNS enquiries.


## Monitoring

* **[monit](https://mmonit.com/monit/)**: a small utility for managing and
  monitoring Unix systems. Monit conducts automatic maintenance and repair and
  can execute meaningful causal actions in error situations.
* **[iotop](http://guichaz.free.fr/iotop/)**: Show disk and swap I/O per
  process.
* **[logtail](https://www.fourmilab.ch/webtools/logtail/)**: Watch Multiple
  Log Files on Multiple Machines.


## Security

* **[fail2ban](https://www.fail2ban.org/wiki/index.php/Main_Page)**: Fail2ban
  scans log files and bans IPs that show the malicious signs.
* **[fern](http://ferm.foo-projects.org/)**:  a tool to maintain complex
  firewalls, without having the trouble to rewrite the complex rules over and
  over again. 
* **[testssl](https://testssl.sh/)**: checks a server's service on any port
  for the support of TLS/SSL ciphers, protocols as well as recent
  cryptographic flaws and more. 
* **[pwgen](https://github.com/jbernard/pwgen)**: Generate pronouncable and
  easy to type passwords.


## Source control

* **[tig](https://github.com/jonas/tig)**: an ncurses-based text-mode
  interface for git.
* **[git cola](https://git-cola.github.io/)**: a sleek and powerful graphical
  user interface for Git.
* **[multi-git-status](https://github.com/fboender/multi-git-status)**: Show
  uncommitted, untracked and unpushed changes for multiple Git repos.
