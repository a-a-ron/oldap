# Learning Open LDAP
A repo documenting notes on creating an Open LDAP server and connecting it to AWS. 

https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-a-basic-ldap-server-on-an-ubuntu-12-04-vps

http://opensourceforu.efytimes.com/2010/02/openldap-part-1-setting-up-directory-server/ ( instructions for running ldap clients or servers using fedora on Linux)

https://github.com/IntersectAustralia/acdata/wiki/Setting-up-OpenLDAP
http://krypted.com/mac-security/starting-openldap-on-mac-os-x-client/

Introduction to OpenLDAP

A directory is a database optimized for reading, browsing, and searching. LDAP stands for Lightweight Directory Access Protocol. It is a lightweight protocol for accessing directory services, specifically X.500 based directory services. LDAP runs over TCP/IP.

The LDAP information model is based on entries. An entry is a collection of attributes that has a globally-unique Distinguished Name (DN). Each of the entry’s attributes has a type and one or more values.

LDAP is based on a client-server model. One ore more LDAP servers contain the data making up the directory information tree (DIT). The client connects to servers and asks it a questions. The server responds with an answer. No matter which LDAP server a client connects to, it sees the same view of the directory.
