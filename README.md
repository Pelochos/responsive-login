# Accessible Login Form with Validation
This is a simple, accessible login form built with semantic HTML and vanilla CSS.  It includes client-side validation using the `required` and `:invalid` pseudo-classes, as well as visible error messages that display when form fields are invalid.

## Features
- Fully semantic HTML5 structure
- Accessible markup using `aria-label` and `aria-describedby`
- Email validation using `type="email"` and `:invalid`
- Error messages that appear only when validation fails
- Graceful fallback for older browsers
- CSS-only logic for showing errors (no JavaScript needed)

## Browser compatibility
Tested in Firefox and Chrome on desktop and mobile.  This form is designed to work without JavaScript, ensuring compatibility even in environments with limited scripting support.

## File structure
.<br>
├── Images/<br>
│ ├── champagne.png<br>
│ ├── exclamation-mark-triangle-svgrepo-com.svg<br>
│ ├── gmaillogo.png<br>
│ ├── grandreservelogoblack.png<br>
│ ├── grandreservelogonobackground.png<br>
│ ├── tgr.ico<br>
│ └── thumbs-up-svgrepo-com.svg<br>
├── README.md<br>
├── LICENCE<br>
├── index.html<br>
└── styles.css

## Usage
You can view the live version of the login page on [GitHub Pages](https://pelochos.github.io/responsive-login/).
Simply visit the link, and you’ll be able to see the page in action, including the responsive design and interactive elements.
#### Alternatively:-
1. Clone the repo.
2. Open `index.html` in your browser.
3. Try submitting the form with an invalid email to see validation in action.

## Customization
You can customise:-
- field labels and placeholder text
- validation error messages
- styling via `styles.css`


## License
MIT — use freely for personal or commercial projects.
