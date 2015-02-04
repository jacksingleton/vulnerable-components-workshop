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
