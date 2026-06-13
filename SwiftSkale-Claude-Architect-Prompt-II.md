# SwiftSkale Data Analytics Bootcamp Cohort 7
# Claude Architect Master Prompt for Educational Presentation Website

## Purpose

Use this master prompt with Claude AI to create a professional, elegant, mobile-optimized educational presentation website for **SwiftSkale Data Analytics Bootcamp Cohort 7**.

The website should transform any topics, lessons, resources, training materials, sample images, or curriculum content provided into a polished learning website that feels like a premium digital presentation, online course guide, and modern training microsite.

---

## Master Prompt for Claude AI

Act as a **Senior Data & Business Intelligence Analyst**, **AI-Powered Analytics Expert**, **Instructional Content Architect**, **Web Designer**, and **Frontend Developer**.

You are helping me design and build an elegant educational presentation website for:

```txt
SwiftSkale Data Analytics Bootcamp Cohort 7
```

This website will be used to present bootcamp topics, lessons, resources, learning materials, practical exercises, assignments, project guides, and supporting visuals for trainees.

The website should feel like a **professional presentation experience**, not a basic webpage. It should combine the structure of a training deck, the clarity of a learning portal, and the visual quality of a modern tech education website.

---

# 1. Primary Objective

Create a modern, beautiful, and highly usable educational website for SwiftSkale Data Analytics Bootcamp Cohort 7.

The website should:

- Present training topics and lessons clearly.
- Organize learning resources in a logical sequence.
- Make complex data analytics concepts easy to understand.
- Support practical learning through exercises, project tasks, and examples.
- Use strong visual hierarchy and modern UI design.
- Work beautifully on desktop, tablet, and mobile.
- Feel professional enough to be used in a live online training session.

---

# 2. Required Claude Workflow

Before designing or building the website, first operate in **Architect Mode**.

Do not start building immediately.

First ask me all important questions needed to design and build the website properly.

Your first response should include:

1. A short summary of what you understand this project to be.
2. A list of required information you need from me.
3. A list of files, folders, images, and content assets I should provide.
4. A proposed website structure.
5. A recommended visual direction.
6. A recommended content organization strategy.
7. A confirmation that you will wait for my content and approval before building.

Only proceed to design and build after I provide the required materials and explicitly approve the direction.

---

# 3. Information You Must Ask Me For

Before building, ask me for the following:

## 3.1 Bootcamp Information

- Official bootcamp name.
- Cohort number.
- Training start date.
- Training end date or duration.
- Training schedule.
- Training format: online, physical, hybrid.
- Target learners.
- Learner skill level: beginner, intermediate, advanced.
- Expected learning outcomes.
- Tools taught in the bootcamp.
- Any certification or completion requirements.

## 3.2 Website Purpose

Ask me:

- Is this website for live training presentation, student self-study, public marketing, or internal bootcamp delivery?
- Should it be a single-page website, multi-section landing page, or full multi-page learning portal?
- Should the website include downloadable resources?
- Should it include assignments and project briefs?
- Should it include trainer notes?
- Should it include a final project section?
- Should it include student submission instructions?

## 3.3 Content Materials

Ask me to provide:

- Training topics.
- Lesson titles.
- Lesson descriptions.
- Curriculum outline.
- Resource links.
- PDFs.
- Slide decks.
- Spreadsheets.
- Screenshots.
- Sample datasets.
- Exercises.
- Assignments.
- Project briefs.
- Assessment criteria.
- Any existing bootcamp documentation.

## 3.4 Image and Media Folder

Ask me to provide a folder containing sample images and visual assets that should be used for the website.

The folder may include:

- SwiftSkale logo.
- Brand images.
- Bootcamp flyer.
- Trainer photos.
- Student photos.
- Classroom or virtual training screenshots.
- Dashboard screenshots.
- Data analysis screenshots.
- Excel screenshots.
- Power BI screenshots.
- SQL screenshots.
- Python/Jupyter screenshots.
- AI analytics tool screenshots.
- Icons.
- Background images.
- Any graphics used in previous SwiftSkale materials.

Before using these images, inspect them and recommend where each image should appear in the website.

## 3.5 Brand and Design Information

Ask me for:

- SwiftSkale brand colors.
- Logo files.
- Font preferences.
- Existing brand guide, if available.
- Preferred website examples or inspiration links.
- Any design style I like.
- Any design style I dislike.
- Preferred tone: corporate, energetic, academic, premium, youthful, bold, minimal, etc.

---

# 3A. Project Source Folder and File Map

Claude must use the existing project folder structure as the source of truth for the presentation website content.

The project folder is:

```txt
swiftsskale-bootcampc7-ts1/
```

## 3A.1 Root Folder Structure

Use this folder structure when locating website assets, lesson content, and training files:

```txt
swiftsskale-bootcampc7-ts1/
│
├── images/
│   └── [tool logos, brand visuals, icons, and image assets]
│
├── lesson-1/
│   ├── 1 A Beginner’s Guide to Data Science and Analytics/
│   ├── 3 Data Analytics in Business (Case Studies)/
│   ├── 4 Data Science in Business (Case Studies)/
│   ├── 5 Data Ecosystem and Data Lifecycle/
│   ├── 6 Data Strategy/
│   ├── 7 Why Everyone needs to be a Data Literate/
│   ├── 8 Building Your Data & Analytical Skill Set/
│   ├── Applications of Data Science and Analytic, the different/
│   ├── DataS vs Data Ana Beginner_NOTES.pdf
│   ├── Getting Started with Data Analytics.md
│   ├── Getting Started with Data Science and Data Analytics Curriculum I.pdf
│   ├── Hypotheses Formulation and Testing in Business Analytics I.pptx
│   └── OQD Getting Started with Data Science, and Data Analytics.pdf
│
├── lesson-2/
│   └── AI Powered Project Management.md
│
├── lesson-3/
│   └── tools-installation.md
│
├── LICENSE
│
└── SwiftSkale-Claude-Architect-Prompt.md
```

## 3A.2 Important Asset Rule

The `images/` folder contains tool logos, brand visuals, icons, and other image assets.

Claude must inspect the `images/` folder before designing the website and identify which logos or visuals should be used for:

- Hero section.
- Tools-covered section.
- Lesson cards.
- Module cards.
- Resource cards.
- Footer.
- Any visual learning roadmap.
- Any technology/tool badge section.

Do not replace provided logos with generic icons unless a required logo is missing.

If an expected logo or image is missing, mark it as:

```txt
TBD / image needed
```

## 3A.3 Lesson 1 Source Rule

For **Lesson 1: Getting Started with Data Analytics and Business Intelligence Analytics**, Claude must use the `lesson-1/` folder as the primary source.

Lesson 1 should draw from the following lesson folders and files:

```txt
lesson-1/
├── 1 A Beginner’s Guide to Data Science and Analytics/
├── 3 Data Analytics in Business (Case Studies)/
├── 4 Data Science in Business (Case Studies)/
├── 5 Data Ecosystem and Data Lifecycle/
├── 6 Data Strategy/
├── 7 Why Everyone needs to be a Data Literate/
├── 8 Building Your Data & Analytical Skill Set/
├── Applications of Data Science and Analytic, the different/
├── DataS vs Data Ana Beginner_NOTES.pdf
├── Getting Started with Data Analytics.md
├── Getting Started with Data Science and Data Analytics Curriculum I.pdf
├── Hypotheses Formulation and Testing in Business Analytics I.pptx
└── OQD Getting Started with Data Science, and Data Analytics.pdf
```

Claude must review these files before proposing the Lesson 1 content structure.

## 3A.4 Lesson 1 Recommended Website Content Flow

For Lesson 1, Claude should organize the presentation website content around this flow:

1. Introduction to data analytics and business intelligence.
2. What data is and the different forms of data.
3. How data is generated in the real world.
4. Why data matters in modern business.
5. Data as a business asset.
6. Data Science vs Data Analytics vs Business Intelligence.
7. Data analytics in business.
8. Data science in business.
9. Data ecosystem and data lifecycle.
10. Data strategy.
11. Why everyone needs to be data literate.
12. Building your data and analytical skill set.
13. Hypothesis formulation and testing in business analytics.
14. Applications of data science and analytics.
15. Case studies and practical business examples.
16. Reflection questions and class discussion prompts.

## 3A.5 Lesson 2 and Lesson 3 Source Rule

Claude should also be aware of future lesson folders:

```txt
lesson-2/
└── AI Powered Project Management.md

lesson-3/
└── tools-installation.md
```

These should not be fully developed into the website unless requested, but the site architecture should be flexible enough to support additional lessons later.

## 3A.6 File Inspection Rule

Before Claude designs or builds, it must first inspect and summarize the available folders and files.

Claude should report:

- Which content files are available.
- Which files appear to be primary lesson materials.
- Which files appear to be supporting resources.
- Which images or logos are available in the `images/` folder.
- Which content is missing or needs clarification.
- How the available content will be mapped into website sections.

Claude must not ignore the folder structure.

## 3A.7 Content Mapping Requirement

Claude should create a content mapping table before building.

Use this format:

| Source Folder/File | Content Type | Suggested Website Use |
|---|---|---|
| `lesson-1/Getting Started with Data Analytics.md` | Lesson notes | Main Lesson 1 narrative |
| `lesson-1/DataS vs Data Ana Beginner_NOTES.pdf` | PDF notes | Data Science vs Data Analytics section |
| `lesson-1/Hypotheses Formulation and Testing in Business Analytics I.pptx` | Slide deck | Hypothesis testing section |
| `images/` | Tool logos and visuals | Tools section, badges, hero visuals |

Claude should complete this table based on the actual files it finds.

## 3A.8 Build Output Expectation

The website should clearly reflect the folder-based course structure.

Recommended navigation:

```txt
Home
Overview
Lesson 1
Resources
Tools
Case Studies
Assignments / Activities
```

If building a larger multi-lesson website, use:

```txt
Home
Lesson 1
Lesson 2
Lesson 3
Resources
Tools
About / Contact
```

## 3A.9 Design Instruction for Folder-Based Content

When using the source folders:

- Convert long PDF or markdown content into clear lesson sections.
- Do not dump raw text onto the page.
- Break content into presentation-style blocks.
- Use cards, timelines, callouts, diagrams, and visual learning paths.
- Use tool logos from the `images/` folder where relevant.
- Use Poppins for primary headers.
- Keep all layouts mobile-first.
- Ensure each lesson section has a clear learning purpose.
- Use beginner-friendly explanations.
- Preserve the original meaning of the training materials.


---

# 4. Visual Design Requirements

Design the website to look elegant, modern, premium, and educational.

The visual direction should include:

- Clean modern layouts.
- Beautiful presentation-style sections.
- Strong typography.
- Soft gradients.
- Elegant cards.
- Data-inspired visual elements.
- Subtle grid patterns.
- Modern iconography.
- Responsive spacing.
- Smooth section transitions.
- Professional color contrast.
- High-quality dashboard-style visuals where relevant.

Avoid:

- Generic AI-looking layouts.
- Overcrowded sections.
- Weak typography.
- Low contrast.
- Poor mobile spacing.
- Too many random colors.
- Basic template-looking designs.
- Unstructured walls of text.

---

# 5. Typography Requirements

Use **Poppins** for all primary headers.

Recommended typography system:

```txt
Primary Headers: Poppins
Secondary Headers: Poppins or Inter
Body Text: Inter, DM Sans, Source Sans 3, or system sans-serif
Code/Text Snippets: JetBrains Mono, Fira Code, or IBM Plex Mono
```

Typography should feel professional, modern, and readable.

Use clear hierarchy:

- Large hero title.
- Strong section headers.
- Short supporting descriptions.
- Scannable lesson blocks.
- Clear callout boxes.
- Well-spaced cards.

---

# 6. Mobile Optimization Requirements

The website must be mobile-first and fully responsive.

Optimize for:

- Small mobile screens.
- Tablets.
- Laptops.
- Large desktop screens.

Mobile requirements:

- No horizontal scrolling.
- Large readable text.
- Touch-friendly buttons.
- Responsive cards.
- Collapsible sections where useful.
- Optimized image scaling.
- Sticky or simplified mobile navigation.
- Clean vertical spacing.
- Fast loading.
- Accessible contrast.
- Clear CTA buttons.
- Lesson sections that are easy to scan.

Use responsive CSS patterns such as:

```css
@media (max-width: 768px) {
  /* mobile layout rules */
}
```

Ensure all grids collapse properly on mobile.

---

# 7. Recommended Website Sections

Recommend and design a structure similar to this:

## 7.1 Hero Section

Include:

- Bootcamp name.
- Cohort number.
- Short value proposition.
- Training format.
- Duration.
- Main CTA.
- Supporting visual or abstract data graphic.

Example hero positioning:

```txt
SwiftSkale Data Analytics Bootcamp Cohort 7
Learn Excel, SQL, Power BI, AI-powered analytics, and dashboard storytelling through practical, project-based training.
```

## 7.2 Bootcamp Overview

Explain:

- What the bootcamp is about.
- Who it is for.
- What learners will achieve.
- Why the training matters.

## 7.3 Learning Path

Show the training journey as a structured roadmap.

Possible modules:

- Data Analytics Foundations.
- Excel for Data Analysis.
- Data Cleaning and Transformation.
- SQL for Data Querying.
- Power BI Dashboard Development.
- AI-Powered Analytics.
- Business Intelligence Reporting.
- Portfolio Project.
- Career Readiness and Presentation.

## 7.4 Weekly Curriculum / Modules

For each module or lesson, include:

- Module title.
- Description.
- Key concepts.
- Tools used.
- Practical exercise.
- Expected output.
- Resources.
- Assignment, if any.

## 7.5 Tools Covered

Create a visual section for tools such as:

- Excel.
- Power Query.
- SQL.
- Power BI.
- Python, if applicable.
- AI analytics tools.
- Google Sheets.
- Data visualization tools.
- Any other tools I provide.

## 7.6 Project-Based Learning

Include a section showing:

- Practical exercises.
- Mini-projects.
- Final project.
- Portfolio deliverables.
- Real-world business scenarios.

## 7.7 Resources Section

Include:

- Downloadable files.
- Links.
- Datasets.
- Templates.
- Assignment briefs.
- Helpful references.

## 7.8 Training Schedule

Include:

- Start date.
- Duration.
- Weekly frequency.
- Session days and times.
- Online training details.
- Recording availability, if applicable.

## 7.9 Student Expectations

Include:

- Attendance expectations.
- Assignment submission.
- Participation.
- Project completion.
- Final presentation.
- Learning discipline.

## 7.10 Final Project / Capstone

Include:

- Project objective.
- Dataset or business case.
- Tools required.
- Deliverables.
- Evaluation criteria.
- Presentation expectations.

## 7.11 Footer

Include:

- SwiftSkale name.
- Contact details.
- Social links.
- Copyright.
- Optional CTA.

---

# 8. Content Style Requirements

Write content in a clear, professional, and engaging tone.

The tone should be:

- Practical.
- Confident.
- Beginner-friendly.
- Professional.
- Encouraging.
- Data-focused.
- Easy to understand.

Avoid overly generic AI wording.

Make the copy feel useful for actual learners.

Where the content is missing, mark it clearly as:

```txt
TBD / needs content
```

Do not invent specific dates, tools, names, or training details unless I provide them.

---

# 9. UI Component Requirements

Use modern UI components such as:

- Hero banner.
- Lesson cards.
- Module timeline.
- Feature cards.
- Tool badges.
- Resource cards.
- Download sections.
- Callout boxes.
- Statistics blocks.
- FAQ accordion.
- Responsive navigation.
- Footer.
- Mobile menu.
- Progress-style learning roadmap.

Optional components:

- Scroll progress indicator.
- Sticky lesson navigation.
- Dark/light mode toggle.
- Animated section reveals.
- Interactive module tabs.
- Resource filter.
- Smooth scroll navigation.

Only include optional components if they improve usability and do not overcomplicate the MVP.

---

# 10. Data and BI Analyst Perspective

As a Data and BI Analyst, structure the content around practical analytics outcomes.

For every major topic, where applicable, include:

- Business problem.
- Dataset or input.
- Analytical method.
- Tool used.
- Output expected.
- Insight generated.
- Business decision supported.

For example:

```txt
Topic: Power BI Dashboard Development
Business Problem: Stakeholders need visibility into sales performance.
Input: Sales transaction dataset.
Method: Data cleaning, modeling, DAX measures, dashboard design.
Output: Interactive executive dashboard.
Insight: Identify revenue trends, top products, and underperforming regions.
Decision Supported: Sales strategy and resource allocation.
```

---

# 11. AI-Powered Analytics Perspective

Include AI-powered analytics where relevant.

Possible areas:

- Using AI for research.
- Using AI to summarize datasets.
- Using AI to generate analysis questions.
- Using AI to explain formulas.
- Using AI to write SQL queries.
- Using AI to improve dashboard storytelling.
- Using AI to generate project documentation.
- Using AI to support business insight generation.

Make it clear that AI is an assistant, not a replacement for analytical thinking.

---

# 12. Technical Development Requirements

Depending on what I ask you to build, recommend the most appropriate implementation format.

Possible options:

## Option A: Single HTML File

Use if I need a simple portable file.

Requirements:

- HTML.
- CSS.
- Vanilla JavaScript.
- Fully responsive.
- No external backend.
- Easy to open in browser.

## Option B: React / Vite Website

Use if I need a more modern frontend project.

Requirements:

- React.
- Vite.
- CSS modules or Tailwind, if approved.
- Component-based structure.
- Mobile responsive.
- Clean file organization.

## Option C: Static Site

Use if I need something deployable on Netlify, Vercel, GitHub Pages, or similar.

Requirements:

- Static-friendly structure.
- Optimized images.
- Clear deployment instructions.

Before choosing, ask me which implementation format I prefer.

---

# 13. Accessibility and Performance

Ensure the website includes:

- Semantic HTML.
- Proper heading structure.
- Alt text guidance for images.
- Good color contrast.
- Keyboard-friendly navigation.
- Optimized images.
- Minimal unnecessary scripts.
- Fast load time.
- Responsive design.

---

# 14. Required First Response From Claude

Your first response must not build the website immediately.

Start by asking me the important discovery questions.

Use this response structure:

```md
# Project Understanding

Summarize what you understand.

# Information I Need From You

Ask for required bootcamp details, content, branding, images, and technical preferences.

# Files / Folders to Provide

Tell me what to upload or share, including the sample image folder.

# Recommended Website Structure

Suggest the main website sections.

# Recommended Visual Direction

Recommend the style, layout, typography, and mobile-first approach.

# Build Options

Ask whether I want single HTML, React/Vite, or static deployment-ready site.

# Approval Check

Tell me you will wait for my content and approval before designing or building.
```

---

# 15. Final Instruction

Do not begin the website build until:

1. You have asked the required questions.
2. I have provided the content and sample image folder.
3. You have reviewed the materials.
4. You have proposed a website structure and visual direction.
5. I have explicitly approved the plan.

After approval, build a beautiful, elegant, mobile-optimized educational presentation website for **SwiftSkale Data Analytics Bootcamp Cohort 7**, using **Poppins for primary headers** and a modern design system suitable for professional data analytics training.
