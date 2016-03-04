## Introduction to LDAP

A directory server must have the means for adding, modifying, and deleting information. This information is assumed to be primarily a resource for reading and not
writing to the directory server.

#### A Unique Name: The DN, or Distinguished name

The DN reflects where the record is in the directory. A DN is composed of a combination of directory information, and looks something like:

dn: o=Acme Services, l=Chicago, st=Illinois, c=US
dn: o=Acme Services, l=Springfield, st=Illinois, c=US

Note: DNs are not case sensitive

#### An Example LDAP Entry or record

dn: o=Acme Services, l=Chicago, st=Illinois, c=US
o: Acme Services
postalAddress: 123 West First Street
l: Chicago
st: Illinois
postalCode: 60616-1234
c: US
telephoneNumber: +1 773 333 8463
objectclass: organization

The first line is the DN and all other lines in the record represent attributes.

o = Organization name
postalAddress = Mailing address
l = Locality (city, town)
st = State or Providence
postalCode = postal code
c = country
telephoneNumber = telephone number
objectclass = specifies which type or types this of record this entry is
