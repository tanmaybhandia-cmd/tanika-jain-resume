# Tanika Jain | Personal resume

An existing personal resume website, originally created during the HTML module and subsequently enhanced using CSS for the web development CSS module. Built with semantic HTML and an external CSS stylesheet, with no JavaScript or external libraries.

## Desktop screenshots

Home page and introduction.

![Desktop home page and introduction](assets/screenshots/1-desktop-home.png)

Experience and selected projects.

![Desktop experience and selected projects](assets/screenshots/2-desktop-experience-projects.png)

Education, leadership, skills and contact.

![Desktop education, leadership, skills and contact](assets/screenshots/3-desktop-education-contact.png)

## Files
- `index.html`: resume sections, accessible navigation and contact link.
- `styles.css`: blue palette, typography, layouts, decorative details, responsive and print rules.
- `favicon.svg`: initials icon.

## CSS concepts
- **Fonts:** Georgia for editorial headings and Arial/Helvetica for readable body copy.
- **Palette:** navy text, medium-blue accents, pale-blue cards and white space, controlled through CSS custom properties.
- **Selectors:** element selectors (`body`, `h1`, `a`); classes (`.nav`, `.project-card`, `.button`); IDs (`#home`, `#contact`); state selectors (`:hover`, `:focus-visible`) and pseudo-elements (`::before`).
- **Display:** Flexbox for navigation, actions, tags and impact figures; Grid for the hero, experience, project and education layouts.
- **Position:** sticky navigation; relative positioning for the profile card; absolute decorative flower/sparkle placement.
- **Alignment:** centred max-width container, shared spacing, padding, margin, gap and consistent line heights.
- **Responsive:** layouts adapt at 950px and 680px; phone layouts use a single column. No external font download is required.
- **Accessibility:** semantic headings and landmarks, skip link, keyboard focus, reduced-motion preference, decorative artwork hidden from assistive technology, and print styles.

## Sections
Home, About, Experience (Blues & Pinks and Brainsnac), Projects (Amaya, MagCore and Indian Oil), Education (CHRIST, IIM Bangalore and school), Leadership and Recognition, Skills, and Contact.

## Content and privacy
Content is based on the supplied resumes and creative marketing portfolio. No unprovided internship dates, graduation year for IIM Bangalore, unsupported performance figures, private phone number or home address have been added. Amaya is described as a business-plan concept, not a launched medical product. Contact uses the email provided in the resumes.

## Run locally
Open `index.html` in a modern browser, keeping all files in this folder. It works offline except for opening the contact email in your mail application.

## Host
GitHub Pages can serve the repository's `main` branch at the root folder. No build step is required. Use the actual deployment link shown by Settings > Pages.

## Assignment submission
Submit only the final 1-2 page PDF, named `26121325_WD_MTProject.pdf`, containing the working website and GitHub repository links, CSS improvements, and section/design explanations. Use a computer browser. The course instructions allow only one submission, so do not submit an incomplete draft.
