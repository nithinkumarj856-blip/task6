# Laundry Mart – Login Page (Task 6)

A responsive login page built with pure HTML and CSS, using **Flexbox** for layout (no margin/padding hacks, no Bootstrap).

## Structure

- `index.html` – page markup
- `index.css` – all styling
- `laundry-illustration.png` – washing machine + laundry basket illustration (blue background)
- `Readme.md` – this file

## Layout

- `.container` – `display: flex`, `height: 100vh`, centers its two children.
- `.left-section` – flex child (`flex: 1`), displays `laundry-illustration.png` full-bleed (`object-fit: cover`) so the image's own blue background fills the panel.
- `.right-section` – flex child (`flex: 1`) holding the login form, centered with flexbox.
- `.login-form` – `display: flex; flex-direction: column` for neat vertical stacking of label/input pairs.

## Features

- Email and password inputs with `placeholder` text and `required` validation.
- "Forgot Password" link aligned to the right via `align-self: flex-end`.
- Styled "Login" button with a gradient matching the illustration panel.
- "Not a member? Register Now" link at the bottom.
- Responsive: on screens narrower than 700px, the layout switches from side-by-side to stacked (`flex-direction: column`).

## How to run

Open `index.html` in any browser (CSS is linked automatically via `<link rel="stylesheet" href="index.css">`).

## Notes

- Centering is done entirely with Flexbox (`justify-content` / `align-items`), as required — no `margin: auto` or manual padding tricks used for centering.
- Container height is set to `100vh` as specified.
