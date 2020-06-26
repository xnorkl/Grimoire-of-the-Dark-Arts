#DNS


##MX lookup
nslookup -query=mx domain.org
dig domain.org MX

##NS lookup
nslookup -type=ns domain.org
dig domain.org NS

##SOA lookup
nslookup -type=soa domain.org

##ANY
nslookup -type=any domain.org

##Reverse lookup
nslookup ip

##SPF
dig txt domain.org
##DKIM
dig txt rndsubdomain._domainkey.domain.org

ex: dig TXT monhealthsys110519._domainkey.monhealthsys.org

##DMARC
dig txt _dmarc.domain.org


