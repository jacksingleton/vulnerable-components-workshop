## Presentation
The slides are html/js built using reveal.js

`open presentation/index.html` on mac

For presentation mode and speaker notes: press `s` after opening. Will open in a seperate browser window

Use right and left arrow keys to navigate forward and backwards

`esc` will bring up a side overview`

## Hands on sections
Hands on sections increase participation but add a lot of extra time. Tweak the presentation to fit your needs.
- Slide #2 (Exploitation exercise) is optional
- Slides 6 and 7 are hands on and hands off options, respectively. Pick one

## Edit $IP placeholder
If you are doing slide #2, edit the '$IP' placeholder in `presentation/index.html`

This should be your local network ip address, check that you can communicate to it from another local computer`

## Print / Export PDF
Open `presentation/index.html` in Chrome with the `print-pdf` query parameter

For example: `file:///injection-workshop/presentation/index.html?print-pdf`

Open the print dialog and either select a printer or export to PDF`

## Black box hands on exercise (slide #6)
* everyone will need to be on the same network
* the network must allow computers to communicate to each other via tcp (check this!)
* run application: `mvn jetty:run`
* now participants can browse to the application at `http://$IP:8080/owners`

## Black box demo (slide #3)
* `mvn jetty:run`
* browse to `http://localhost:8080/owners`
* submit with `${1+1}`
* submit with `${applicationScope}`
