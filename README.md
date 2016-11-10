# Securing Your Webservice

This talk was given on 11th September 2016 for Cambridge Coding Academy at the Eagle Labs Cambridge.

This covers a variety of webservice security issues and mitigations.

Links from the last slides are:
* Mozilla Observatory service to scan for security vulnerabilities https://observatory.mozilla.org
* OWASP - great resource for security information https://www.owasp.org/ (see Reference section on left)
* Mozilla Security Blog https://blog.mozilla.org/security/
* CVEs - see the exploits out there https://cve.mitre.org
* SPA Security http://www.slideshare.net/carlo.bonamico/angularjs-security-defend-your-single-page-application
* HTML5 Security Cheatsheet https://www.owasp.org/index.php/HTML5_Security_Cheat_Sheet
* Let's Encrypt - for free SSL certificates https://letsencrypt.org/

These are some of the issues to consider when building a web service:
* Content Security Policy - how complicated it is! https://scotthelme.co.uk/content-security-policy-an-introduction/
* X-Frame-Options header to protect your site from framing https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options
* XSS information https://excess-xss.com/
* Cross Site Request Forgery https://blog.codinghorror.com/preventing-csrf-and-xsrf-attacks/ and prevention cheat sheet https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)_Prevention_Cheat_Sheet
