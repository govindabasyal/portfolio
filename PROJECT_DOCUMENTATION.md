# Portfolio Website Project Documentation
**Running head:** PORTFOLIO WEBSITE PROJECT

# Personal Portfolio Website: Design, Development, and Evaluation

Nirmal Basyal  
Kavya School  
Computer Science (CS-4271)  
Grade 11 Final Project (2082)  
April 8, 2026

---

## Table of Contents
1. Introduction  
2. Project Goals and Scope  
3. Project Planning and Feasibility Study  
4. Requirements Analysis and Design  
5. Wireframe Design  
6. Implementation and Development  
7. Testing and Quality Assurance  
8. Deployment and Web Address  
9. Conclusion and Reflection  
10. References

---

## Introduction
This project presents a personal portfolio website developed using HTML and CSS only. The site includes four required pages: an about page, a skills page, an interests page, and a contact page. The project demonstrates foundational web development skills, including semantic page structure, responsive layouts, and user-friendly interface design. According to MDN Web Docs (n.d.-a), semantic HTML improves accessibility and structure, while CSS supports maintainable visual design and layout control.

## Project Goals and Scope
### Goals
- Develop a complete multi-page portfolio website using HTML and CSS.
- Demonstrate use of inline, internal, and external CSS.
- Apply accessibility and responsive design practices.
- Document the full development process in a professional academic format.

### Scope
The implementation includes the following pages and stylesheets:
- `index.html` + `about.css`
- `skills.html` + `skills.css`
- `interests.html` + `interests.css`
- `contact.html` + `contact.css`
- Shared stylesheet: `styles.css`

The project excludes JavaScript frameworks, CSS frameworks, and third-party animation packages, in line with coursework constraints.

## Project Planning and Feasibility Study
### Feasibility Analysis
- **Technical feasibility:** The project is feasible with beginner-to-intermediate HTML/CSS skills.
- **Time feasibility:** The project can be completed within a four-week schedule.
- **Resource feasibility:** Required tools are available (VS Code, browser, and GitHub).

### Project Timeline (Gantt-Style Schedule)

**Table 1**  
*Project Timeline and Milestones*

| Week | Activity | Deliverable |
|---|---|---|
| Week 1 | Requirement gathering and planning | Site map, page structure, rubric mapping |
| Week 2 | HTML development for all pages | Four completed HTML pages |
| Week 3 | CSS styling and responsive improvements | Completed CSS and polished UI |
| Week 4 | Testing, documentation, and deployment | Final report and hosted website |

## Requirements Analysis and Design
### Functional Requirements
1. Navigation links available on every page.
2. About section with full name and personal description.
3. Skills section with categorized skill information.
4. Interests section with short explanations.
5. Contact form with name, email, and message fields.

### Non-Functional Requirements
- Consistent visual design and typography.
- Mobile-friendly layout behavior.
- Readable spacing, contrast, and user flow.
- Basic accessibility features (semantic sections, labels, skip link, and current-page indicators).

## Wireframe Design
The website follows a shared structure on each page: header, navigation, main content cards, and footer.

**Figure 1**  
*Low-Fidelity Wireframe Layout (Text Representation)*

```text
+--------------------------------------------------+
| Header (Name / Page title / subtitle)            |
+--------------------------------------------------+
| Navigation (About | Skills | Interests | Contact)|
+--------------------------------------------------+
| Main Content Area                                |
| - Card 1 (core page content)                     |
| - Card 2 (supporting details / highlights)       |
+--------------------------------------------------+
| Footer                                            |
+--------------------------------------------------+
```

## Implementation and Development
### Development Highlights
- Added semantic HTML structure for clarity and accessibility.
- Implemented visual hierarchy using reusable card and grid patterns.
- Applied responsive design with media queries and flexible containers.
- Improved contact form usability using labels, field constraints, and clear form controls.
- Added richer portfolio content to strengthen presentation quality.

### CSS Techniques Used
- **Inline CSS:** Applied to highlighted text in `index.html`.
- **Internal CSS:** Included in `index.html` for component-level styling.
- **External CSS:** Used through `styles.css` and page-specific CSS files.

### Source Code Organization
- Global/shared styles are managed in `styles.css`.
- Page-specific theme and components are managed in per-page CSS files.
- Navigation and layout patterns are consistent across all pages.

## Testing and Quality Assurance
Testing was performed manually using browser checks and file validation.

**Table 2**  
*Test Cases and Results*

| Test Case ID | Test Description | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC-01 | Open each page from navigation menu | Correct page opens every time | All links route correctly | Pass |
| TC-02 | Resize browser from mobile to desktop | Layout remains readable and aligned | Responsive behavior is stable | Pass |
| TC-03 | Enter valid/invalid form input on contact page | Required constraints activate correctly | Validation works as expected | Pass |
| TC-04 | Check active nav item per page | Current page is visually indicated | `aria-current` and active style work | Pass |
| TC-05 | Verify content readability and contrast | Text remains readable on all sections | Contrast and spacing are clear | Pass |

## Deployment and Web Address
### Deployment Plan (GitHub Pages)
1. Create a repository and push all website files.
2. Enable GitHub Pages in repository settings.
3. Select branch and root folder for deployment.
4. Copy and submit generated web address.

### Domain/Web Address Requirement
This coursework requires a web address generation step. GitHub Pages URL can be used to satisfy this criterion.

## Conclusion and Reflection
This project improved my practical understanding of HTML and CSS, especially semantic structuring, responsive design, and clean visual presentation. I also learned the importance of project planning, testing, and documentation. Through iterative refinement, the final version became more accessible, more professional, and better aligned with assessment criteria.

## References
GitHub. (n.d.). *Configuring a publishing source for your GitHub Pages site*. https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

MDN Web Docs. (n.d.-a). *HTML: HyperText Markup Language*. https://developer.mozilla.org/en-US/docs/Web/HTML

MDN Web Docs. (n.d.-b). *CSS: Cascading Style Sheets*. https://developer.mozilla.org/en-US/docs/Web/CSS

World Wide Web Consortium. (2018). *Web Content Accessibility Guidelines (WCAG) 2.1*. https://www.w3.org/TR/WCAG21/

---

### Appendix A: Submission Checklist
- [ ] ZIP file of source code
- [ ] Hosted website link
- [ ] Final documentation exported to PDF
- [ ] Screenshots of each page included in final PDF
- [ ] Final proofreading and formatting check
- Export this documentation to PDF for submission.
