ssl-cookie
==========

OpenSSL Cookie Stealer
Cloned from https://gist.github.com/mitsuhiko/10130454
Credit to https://github.com/mitsuhiko and http://s3.jspenguin.org/ssltest.py

Summary:

PoC that abuses the OpenSSL heartbleed bug to expose session cookie values in web server memory.  Will extract semicolon separated values representing found session variables.

WARNING:  this is PoC code and appropriate usage of the tool is to test your web server to determine if it is leaking session cookie data.

Usage:

python stealcookie.py site [options -p PORT]


