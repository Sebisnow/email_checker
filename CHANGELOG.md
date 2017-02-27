## v0.0.3 (2015-11-22)

* Fix a bug when the SMTP doesn't reply
* Fix a bug when the socket is unexpectedly closed

## v0.0.2 (2015-11-21)

* Speedup the library: Remove a retry loop (hack) when MX lookup was empty
* Add a configuration entry for the default DNS used
* Make the app OTP compliant

## v0.0.1 (2015-11-19)

* Check email match a basic email REGEX
* Check the MX exists for the email's domain
* Check the SMTP behind the MX knows this email address
