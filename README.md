![GitHubBuild](https://github.com/postfixadmin/postfixadmin/workflows/GitHubBuild/badge.svg)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/postfixadmin/Lobby)
[![Coverage Status](https://coveralls.io/repos/github/postfixadmin/postfixadmin/badge.svg?branch=master)](https://coveralls.io/github/postfixadmin/postfixadmin?branch=master)
![GitHub repo size](https://img.shields.io/github/repo-size/postfixadmin/postfixadmin)
[![IRC Chat - #postfixadmin](https://img.shields.io/badge/IRC%20libera-brightgreen.svg)](https://web.libera.chat/#postfixadmin)

# PostfixAdmin 

An open source, web based interface for managing domains/mailboxes/aliases etc on a Postfix based mail server.

Integrates with :

 - Postfix
 - IMAP/POP3 server (e.g. Dovecot or Courier)
 - Database backend (choose one of: sqlite, mysql, postgresql)
 - Fetchmail (optional)

## Features

 - Unlimited domains/aliases/mailboxes 
 - Optional storage quota support
 - Optional password expiry (beta)
 - Multiple password hashing formats 
 - Supports PostgreSQL, MySQL, MariaDB, SQLite database backends (choose one)
 - Supports retrieval of mail from a remote POP3 server (via fetchmail)
 - Vacation / Autoresponder / Out Of Office support
 - Users have the ability to login, change their password or vacation (out of office) status.
 - Integration with Squirrelmail / Roundcube (via plugins)
 - Optional XMLRPC based API 
 - Supports PHP7.2+ (older versions of PHP should work with older releases)

[Some screenshots of Postfixadmin in action (as admin and user)](DOCUMENTS/screenshots/README.md)


## Useful Links

 - [Probably all you need to read (pdf)](http://blog.cboltz.de/uploads/postfixadmin-30-english.pdf)
 - http://postfixadmin.sf.net - the current homepage for the project
 - [Docker Images](https://github.com/postfixadmin/docker)
 - [What is it? (txt)](/DOCUMENTS/POSTFIXADMIN.txt)
 - [Installation instructions](/INSTALL.TXT)
 - [Wiki](https://sourceforge.net/p/postfixadmin/wiki/)
 - [Mailing list](https://sourceforge.net/p/postfixadmin/discussion/676076)
 - [IRC channel](irc://irc.libera.chat/#postfixadmin) (#postfixadmin on Libera.chat).
