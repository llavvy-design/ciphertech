# ✳ CipherTech — The Creative Tech Hub

**A creative, responsive, multi-page technology hub website built with HTML5 and CSS3 as a weekend learning assignment for eMobinis Institute.**

> **Project status: Learning project / Frontend demonstration**
>
> CipherTech is a fictional technology hub created for educational and practice purposes. It demonstrates HTML structure, CSS styling, responsive layouts and common website components. It is **not a fully functional production website**. There is no backend, database, authentication system or working registration management system.

---

## 🌱 About the Project

CipherTech is a fictional learning community designed around one simple idea: technology should be a place where curious minds can explore, experiment and create.

The website introduces a collection of imaginary technology learning programs, showcases project ideas and presents a sample registration experience.

The project was built to practise the fundamentals of web development, including semantic HTML, CSS layouts, forms, navigation, tables and responsive design.

Rather than using a generic corporate technology template, CipherTech follows a more artistic visual direction, combining warm cream backgrounds, forest-green typography, muted orange accents, sage green, soft lilac and playful decorative elements.

The goal was to create something that feels like a creative technology studio while demonstrating the concepts covered in an introductory HTML and CSS assignment.

## 🎨 Design Direction

The visual identity uses:

- **Warm cream and earthy neutrals** for the main backgrounds.
- **Forest green** for typography, navigation and dark sections.
- **Muted orange** for highlights, calls to action and decorative details.
- **Sage green and soft lilac** for cards, illustrations and learning sections.
- **Expressive typography** using Space Grotesk for headings and DM Sans for body text.
- **CSS-generated artwork**, layered shapes, subtle animations and hover effects to make the interface more visually engaging.

The design is intended to feel creative, welcoming and approachable rather than overly corporate or minimal.

## 📄 Website Pages

### 1. Home Page — `index.html`

The home page introduces CipherTech and its fictional learning community.

It includes:

- A header with the website logo and navigation links.
- A hero section with a headline, description and call-to-action buttons.
- An about section explaining the hub's purpose.
- A statistics section using fictional example figures.
- Four cards highlighting services and learning opportunities.
- Ordered and unordered lists explaining the learning journey.
- A description list introducing technical terms.
- Embedded educational video content using an HTML `<iframe>`.
- A call-to-action section and footer with contact details and navigation links.

### 2. Programs Page — `programs.html`

The programs page presents six fictional technology learning pathways:

1. Web Development
2. Python and Data Science
3. Cybersecurity and Networks
4. AI and Machine Learning
5. Cloud Computing and DevOps
6. UI/UX and Creative Technology

The page includes:

- A visually illustrated introduction.
- Six program cards with descriptions, topics, levels and example durations.
- A structured HTML table with a caption, table headings, body rows, footer and a `colspan` example.
- Project idea cards with CSS-generated illustrations.
- A technical glossary using a description list.
- Registration links, navigation and a footer.

The course descriptions and durations are illustrative examples created for this assignment. They do not represent official courses offered by a real institution.

### 3. Registration Page — `register.html`

The registration page demonstrates how an HTML form can be structured and styled.

It includes:

- Personal information fields.
- Email and telephone inputs.
- Number, date and URL inputs.
- Dropdown selections for education level and preferred program.
- Radio buttons for learning preferences.
- Checkboxes for areas of interest.
- A textarea for additional information.
- Five `<fieldset>` sections with `<legend>` headings.
- Labels associated with their corresponding form fields.
- Browser-native required-field validation.
- A sidebar with helpful information.
- Call-to-action content and a footer.

**Important:** The registration form is a frontend demonstration only. It does not save submissions, send registration details to an administrator or connect to a database. Its current GET submission method can place entered values in the URL, so only fictional test information should be used.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Defines the structure and content of the website. |
| CSS3 | Controls colours, typography, spacing, layouts, borders and visual styling. |
| CSS Flexbox | Arranges navigation, buttons, footer content and other flexible layouts. |
| CSS Grid | Organises program cards, project cards, statistics and page sections. |
| CSS Media Queries | Adjusts layouts for different screen sizes. |
| CSS Animations and Transitions | Adds subtle movement and hover effects. |
| Git | Tracks changes and records project history. |
| GitHub | Hosts the project's source code repository. |

Google Fonts provides the Space Grotesk and DM Sans typefaces. The embedded educational video is hosted externally.

No JavaScript framework, CSS framework or backend technology is used in this project.

## 📁 Project Structure

```text
ciphertech/
│
├── index.html
├── programs.html
├── register.html
│
└── static/
    └── css/
        ├── index.css
        ├── programs.css
        └── register.css
```

### File Overview

- `index.html` — Home page structure and content.
- `programs.html` — Program cards, curriculum table and project ideas.
- `register.html` — Registration form and supporting content.
- `static/css/index.css` — Home page styling.
- `static/css/programs.css` — Programs page styling.
- `static/css/register.css` — Registration page styling.

Each HTML page is connected to its own external stylesheet. The project does not use inline CSS or `<style>` elements.

## 🚀 How to Run the Project

You can view the project locally without installing a backend or database.

### Option 1: Open the HTML files directly

1. Download or clone the repository.
2. Open the project folder.
3. Double-click `index.html` to open the home page in your browser.
4. Use the navigation links to explore the other pages.

### Option 2: Use Visual Studio Code and Live Server

1. Clone or download the repository.
2. Open the project folder in Visual Studio Code.
3. Install the Live Server extension if it is not already installed.
4. Right-click `index.html`.
5. Select **Open with Live Server**.
6. Navigate through the website and test the layouts.

An internet connection is needed for the externally hosted Google Fonts and embedded YouTube video. The core HTML and CSS layouts are stored in the repository.

## 📱 Responsive Design

The website uses CSS media queries to adapt its layouts to different viewport sizes.

Responsive adjustments include:

- Switching from desktop navigation to a mobile navigation menu.
- Changing multi-column layouts into fewer columns or a single column.
- Adjusting heading sizes, padding and spacing.
- Making the curriculum table horizontally scrollable on smaller screens.
- Reorganising the registration form and sidebar for mobile devices.

The project is designed to demonstrate responsive web design, although testing across different browsers and devices is still necessary.

## 📚 HTML and CSS Concepts Practised

This project explores the following concepts:

**HTML**
- Document structure and metadata.
- Semantic elements such as `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>` and `<footer>`.
- Headings, paragraphs and hyperlinks.
- Ordered lists, unordered lists and description lists.
- Tables with `<caption>`, `<thead>`, `<tbody>`, `<tfoot>` and `colspan`.
- Forms, labels, different input types, dropdowns and textareas.
- Grouping related form fields with `<fieldset>` and `<legend>`.
- Basic browser-native form validation.
- Embedded content using `<iframe>`.

**CSS**
- External stylesheets and class selectors.
- CSS custom properties and reusable design values.
- Colours, backgrounds, typography and borders.
- The CSS box model.
- Margins, padding, widths and heights.
- Flexbox and CSS Grid.
- Positioning and layered decorative elements.
- Hover states and transitions.
- Keyframe animations.
- Table and form styling.
- Responsive media queries.
- Focus indicators and reduced-motion preferences.

## ⚠️ Limitations and Scope

CipherTech is intentionally a **static frontend practice project**.

The following features have not been implemented:

- No backend or server-side application logic.
- No database or permanent data storage.
- No working account creation, login or authentication.
- No registration submission processing.
- No automated confirmation emails.
- No real course enrolment or payment processing.
- No administrative dashboard.
- No JavaScript-powered application functionality.
- No connection to a real educational institution.

Navigation between the three HTML pages works as ordinary website navigation. Browser-native form validation also works, but it does not replace server-side validation or data handling in a real application.

The statistics, course descriptions, durations and contact details are fictional demonstration content. The email address uses the reserved `.example` domain and is not a real support address.

This project should not be used to collect real personal information or presented as a functioning educational registration service.

## 🔮 Possible Future Improvements

Possible next steps for expanding the project include:

- Adding a custom favicon.
- Improving keyboard navigation and accessibility testing.
- Adding more visual illustrations and refined animations.
- Introducing JavaScript for interactive features.
- Building a backend and database for actual form submissions.
- Implementing secure authentication and an administrative dashboard.
- Adding automated HTML validation and cross-browser testing.

These are potential extensions, not features currently implemented.

## 🎯 Learning Objectives

The main objective was to apply introductory HTML and CSS concepts to a cohesive, multi-page website rather than isolated exercises.

The project provides practice in organising files, structuring semantic HTML, creating layouts, styling forms and tables, connecting pages through navigation, adding responsive behaviour and using Git and GitHub to manage and share source code.

## 🧪 Project Information

| Item | Details |
|---|---|
| Project name | CipherTech — The Creative Tech Hub |
| Project type | Static multi-page frontend website |
| Purpose | HTML and CSS learning assignment |
| Learning programme | eMobinis Institute |
| Status | Educational practice project |
| Frontend technologies | HTML5 and CSS3 |
| Backend | Not implemented |
| Database | Not implemented |
| Repository | [GitHub — llavvy-design/ciphertech](https://github.com/llavvy-design/ciphertech) |

## 💚 Final Note

CipherTech is a small learning project built to explore the foundations of web development, experiment with visual design and put HTML and CSS concepts into practice.

It is not intended to be a finished commercial product. It represents a step in the learning process: taking what has been taught, applying it in a practical project and discovering what can be improved next.

**Learn by doing. Stay curious. Keep building.** ✳
