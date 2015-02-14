## 0. Prepare for the workshop

The following commands should run without errors

* `git clone https://github.com/jacksingleton/vulnerable-components-workshop.git`
* `cd vulnerable-components-workshop/example-app`
* `mvn jetty:run`

## 1. Run App
* `cd example-app`
* `mvn jetty:run`
* Browse to `http://localhost:8080/owners`

## 2. Exploit
* Browse to `http://localhost:8080/owners/search`
* Submit with `${1+1}`
* What else can you do?

## 3. Review slides (or become a facilitator!)
* The slides are html/js
* Open presentation/index.html in a web browser

## Learn more
- OWASP Page: https://www.owasp.org/index.php/Top_10_2013-A9-Using_Components_with_Known_Vulnerabilities
- CVE Standard: http://cve.mitre.org/
- Dependency Check: https://www.owasp.org/index.php/OWASP_Dependency_Check
- Spring EL Injection Disclosure: http://support.springsource.com/security/cve-2011-2730
