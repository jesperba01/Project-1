# Testing

Return back to the [README.md](README.md) file.

🛑🛑🛑🛑🛑 START OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

In this section, you need to convince the assessors that you have conducted enough testing to legitimately believe that the site works well.
Essentially, in this part, you should go over all of your project's features, and ensure that they all work as intended,
with the project providing an easy and straightforward way for the users to achieve their goals.

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/#validate_by_input) | ![screenshot](documentation/testing/test-index.png) | pass: No Errors|
| Race Helper | [W3C](https://validator.w3.org/#validate_by_input) | ![screenshot](documentation/testing/test-racewow.png) | pass: No Errors |
| Final Boss | [W3C](https://validator.w3.org/#validate_by_input) | ![screenshot](documentation/testing/test-me.png) | Pass: No Errors |
| Feedback | [W3C](https://validator.w3.org/#validate_by_input) | ![screenshot](documentation/testing/test-feedback.png) | pass: No Errors |
| Confermation | [W3C](https://validator.w3.org/#validate_by_input) | ![screenshot](documentation/testing/test-conf.png) | Pass: No Errors |
| deployed page | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjesperba01.github.io%2FProject-1%2F) | ![screenshot](documentation/testing/test-pages.png) | Pass: No Errors |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjesperba01.github.io%2FProject-1%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv#css) | ![screenshot](documentation/testing/test-css.png) | Pass: No Errors |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Race Helper | Final Boss | Feedback | Notes |
| --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/browsers/chrome/chrome-home.png) | ![screenshot](documentation/browsers/chrome/chrome-race.png) | ![screenshot](documentation/browsers/chrome/chrome-final.png) | ![screenshot](documentation/browsers/chrome/chrome-feedback.png) | Works as expected |
| Edge | ![screenshot](documentation/browsers/edge/edge-home.png) | ![screenshot](documentation/browsers/edge/edge-race.png) | ![screenshot](documentation/browser-chrome-edge.png) | ![screenshot](documentation/browsers/edge/edge-feedback.png) | Works as expected |
| Safari | ![screenshot](documentation/browsers/safari/safari-home.png) | ![screenshot](documentation/browsers/safari/safari-race.png) | ![screenshot](documentation/browsers/safari/safari-final.png) | ![screenshot](documentation/browsers/safari/safari-feedback.png) | Minor CSS differences to button and link colors|

## Responsiveness

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

I've tested my deployed project on multiple devices to check for responsiveness issues.
to make it easier and test my desired devices at the same time i've used a chrome extension calle Responsive viewer that yoou can download here
[Responsive viewer](https://chromewebstore.google.com/detail/responsive-viewer/inmopeiepgfljkpkidclfgbgbmfcennb)
and another chrome extension called GoFullPage that you can fin here [GoFullPage](https://chromewebstore.google.com/detail/gofullpage-full-page-scre/fdpohaocaechififmbbbbbknoalclacl)

## Responsiveness

Tested devices: Iphone 8, plus 7, plus 6s, plus | Galaxy S9, Note 8, S8 | Ipad(standard) | Nexus 10 | Desktop |
<details> <summary>Click here to see the Screenshots</summary>

- Home 
  ![screenshot](documentation/responsive/responsive-home.png)

- Race Helper
  ![screenshot](documentation/responsive/responsive-race.png)

- Final Boss
  ![screenshot](documentation/responsive/responsive-final.png)

- Feedback
  ![screenshot](documentation/responsive/responsive-feedback.png)  
  
</details>

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/ligthhouse/ligthhouse-homemobile.png) | ![screenshot](documentation/ligthhouse/ligthhouse-homedesk.png) | no issues |
| Race Helper | ![screenshot](documentation/ligthhouse/ligthhouse-racemobile.png) | ![screenshot](documentation/ligthhouse/ligthhouse-racedesk.png) | some minor warnings about color contrast |
| Final Boss| ![screenshot](documentation/ligthhouse/ligthhouse-finalmobile.png) | ![screenshot](documentation/ligthhouse/ligthhouse-finaldesk.png) | no issues |
| Feedback| ![screenshot](documentation/ligthhouse/ligthhouse-feedbackmobile.png) | ![screenshot](documentation/ligthhouse/ligthhouse-feedbackdesk.png) | takes long time to load |

## Bugs

🛑🛑🛑🛑🛑 START OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

This section is primarily used for JavaScript and Python applications,
but feel free to use this section to document any HTML/CSS bugs you might run into.

It's very important to document any bugs you've discovered while developing the project.
Make sure to include any necessary steps you've implemented to fix the bug(s) as well.

**PRO TIP**: screenshots of bugs are extremely helpful, and go a long way!

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

- JS Uncaught ReferenceError: `foobar` is undefined/not defined

    ![screenshot](documentation/bug01.png)

    - To fix this, I _____________________.

- JS `'let'` or `'const'` or `'template literal syntax'` or `'arrow function syntax (=>)'` is available in ES6 (use `'esversion: 11'`) or Mozilla JS extensions (use moz).

    ![screenshot](documentation/bug02.png)

    - To fix this, I _____________________.

- Python `'ModuleNotFoundError'` when trying to import module from imported package

    ![screenshot](documentation/bug03.png)

    - To fix this, I _____________________.

- Django `TemplateDoesNotExist` at /appname/path appname/template_name.html

    ![screenshot](documentation/bug04.png)

    - To fix this, I _____________________.

- Python `E501 line too long` (93 > 79 characters)

    ![screenshot](documentation/bug04.png)

    - To fix this, I _____________________.

## Unfixed Bugs

🛑🛑🛑🛑🛑 START OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

You will need to mention unfixed bugs and why they were not fixed.
This section should include shortcomings of the frameworks or technologies used.
Although time can be a big variable to consider, paucity of time and difficulty understanding
implementation is not a valid reason to leave bugs unfixed.

If you've identified any unfixed bugs, no matter how small, be sure to list them here.
It's better to be honest and list them, because if it's not documented and an assessor finds the issue,
they need to know whether or not you're aware of them as well, and why you've not corrected/fixed them.

Some examples:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

- On devices smaller than 375px, the page starts to have `overflow-x` scrolling.

    ![screenshot](documentation/unfixed-bug01.png)

    - Attempted fix: I tried to add additional media queries to handle this, but things started becoming too small to read.

- For PP3, when using a helper `clear()` function, any text above the height of the terminal does not clear, and remains when you scroll up.

    ![screenshot](documentation/unfixed-bug02.png)

    - Attempted fix: I tried to adjust the terminal size, but it only resizes the actual terminal, not the allowable area for text.

- When validating HTML with a semantic `section` element, the validator warns about lacking a header `h2-h6`. This is acceptable.

    ![screenshot](documentation/unfixed-bug03.png)

    - Attempted fix: this is a known warning and acceptable, and my section doesn't require a header since it's dynamically added via JS.

🛑🛑🛑🛑🛑 START OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

If you legitimately cannot find any unfixed bugs or warnings, then use the following sentence:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

There are no remaining bugs that I am aware of.
