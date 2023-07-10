Understanding what subdomains are is essential in performing web application penetration tests  . It's important to note that hunting subdomains can help eliminate unnecessary noise and focus on finding data ex-filtration.

*Tools used:*
- Sublist3r `CLI tool`
	- You can always install it with `apt-get install sublist3r` in Kali Linux
		[image]
- [Crt.sh](https://crt.sh) `domain` - crt.sh is a certificate search tool that allows users to search for certificates by domain name, organization name, fingerprint, or crt.sh ID.
	- Navigate to the site and make sure to denote `%` for subdomains e.g:
		[image]