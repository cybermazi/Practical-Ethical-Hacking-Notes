Understanding what subdomains are is essential in performing web application penetration tests  . It's important to note that hunting subdomains can help eliminate unnecessary noise and focus on finding data ex-filtration.

*Tools used:*
- Sublist3r `CLI tool`
	- You can always install it with `apt-get install sublist3r` in Kali Linux
		![image](https://github.com/sec-fortress/Practical-Ethical-Hacking-Notes/assets/132317714/c9ebab8d-58d8-4a6e-977f-9bf5f506bae3)
	- Then you can now run `sublist3r --help` to see how the tool works\
   
- [Crt.sh](https://crt.sh) `domain` - crt.sh is a certificate search tool that allows users to search for certificates by domain name, organization name, fingerprint, or crt.sh ID.
	- Navigate to the site and make sure to denote `%` for subdomains e.g:
		![image](https://github.com/sec-fortress/Practical-Ethical-Hacking-Notes/assets/132317714/56c6483f-1801-4083-95ce-dd464935bf89)

  	- Here are list of possible subdomains after our search result
 		![image](https://github.com/sec-fortress/Practical-Ethical-Hacking-Notes/assets/132317714/e7f72840-f8ae-41f3-b116-ef18b8a48554)
