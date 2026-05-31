# Ambuja Foundation Pvt. ITI Darlaghat Website

This repository contains a responsive static website for **Ambuja Foundation Pvt. ITI Darlaghat**. The website presents institute information, available courses, gallery images, course career details, and an admission enquiry form.

## Project Overview

The website is built with simple frontend technologies:

- HTML
- CSS
- JavaScript
- Local image assets

No framework or backend server is required. The pages can be opened directly in a browser.

## Main Pages

### `assignment.html`

The main home page of the website.

Features:

- Header with ITI and Adani logos
- Responsive navigation bar
- Dropdown menu for NCVT and short-term courses
- Image slider
- Admission announcement marquee
- Course cards
- Gallery section with clickable image preview
- Footer with contact details, social links, newsletter form, and apply button

### `courses.html`

The course details page.

Features:

- Interactive course selection
- Dynamic course image, duration, benefits, career options, and best-fit student profile
- Course tabs for quick switching
- Enquiry form layout
- Links back to the home page and admission form
- Supports direct course links such as:

```text
courses.html?course=Electrician
courses.html?course=COPA
courses.html?course=Mechanic%20Motor%20Vehicle
```

### `admissionform.html`

The admission enquiry form page.

Features:

- Student name, email, phone, course, gender, category, and address fields
- Course selection dropdown
- Simple captcha-style checkbox
- Submit and reset buttons
- Responsive form layout for mobile screens

### `assignmentstyle00.css`

The shared stylesheet for the main website page.

Includes:

- Header and logo layout
- Navigation and dropdown styling
- Slider styling and animation
- Course card layout
- Gallery layout
- Footer design
- Tablet and mobile responsive breakpoints

## Course List

The website includes the following courses:

- Electrician
- Computer Operator & Programming Assistant (COPA)
- Mechanic Motor Vehicle (MMV)
- Electronics Mechanic
- Accounts Executive Tally
- General Duty Assistant
- Sewing Machine Operator
- Soft Skills

## Image Assets

The repository includes local images for:

- Slider images
- Course images
- Gallery images
- Logos
- Background sections

Important assets include:

- `ACF.jpg`
- `ITI.png`
- `ADANI.png`
- `Ambuja Foundation SEDI.png`
- `Electrician.jpg`
- `COPA.jpg`
- `MMV.jpeg`
- `Electronics.jpeg`
- `Tally.jpeg`
- `GDA.jpeg`
- `SMO.jpeg`
- `SoftSkill.jpeg`

## Responsive Design

The website has been updated for desktop, tablet, and mobile layouts.

Responsive improvements include:

- Navigation stacks on smaller screens
- Dropdown menus become full-width on mobile
- Course cards switch from two columns to one column
- Gallery images resize for small screens
- Footer columns stack on mobile
- Form fields become single-column on smaller screens
- Long button and navigation text wraps safely
- Mobile background images avoid fixed attachment issues
- Horizontal overflow is reduced with safer layout rules

## How to Run

Open the project folder and double-click:

```text
assignment.html
```

Or open it from your browser using:

```text
File > Open > assignment.html
```

No installation is required.

## Recommended Repository Structure

```text
.
├── assignment.html
├── assignmentstyle00.css
├── courses.html
├── admissionform.html
├── README.md
├── ITI.png
├── ADANI.png
├── Ambuja Foundation SEDI.png
├── ACF.jpg
├── Electrician.jpg
├── COPA.jpg
├── MMV.jpeg
├── Electronics.jpeg
├── Tally.jpeg
├── GDA.jpeg
├── SMO.jpeg
├── SoftSkill.jpeg
└── gallery images
```

## Future Improvements

Possible improvements for future development:

- Connect admission and newsletter forms to a backend
- Add form validation messages
- Add a mobile hamburger menu
- Compress images for faster loading
- Improve accessibility with more descriptive alt text
- Deploy the site using GitHub Pages

## Author

Created as a static website project for Ambuja Foundation Pvt. ITI Darlaghat.
