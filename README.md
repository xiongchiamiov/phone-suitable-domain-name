# Phone-Suitable Domain Name

I have many email addresses.  However, I've found that none of them work well
over the phone; the letters or words are easily misheard, which ends up with me
not receiving emails.

To remedy this, I decided to register a domain name composed only of unambiguous
characters.  This program searches for words in `/usr/share/dict/words` for
entries solely composed of those letters, then does whois lookups to find
unregistered .com domains.

## Status

No command-line help.  No commenting.  No error handling.  Domains with multiple
matching records (eg `willow.com` and `willow.compsys.com.au`) are reported as
available.

But it worked enough for me to find a domain name.

