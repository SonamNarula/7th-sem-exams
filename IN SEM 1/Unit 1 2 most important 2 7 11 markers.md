# Unit 1 & 2 — High-Priority Exam Question Bank
### AI in Web Development (Generative AI, Prompt Engineering & AI-Assisted Front-End Development)

---

# 🔵 2-MARK QUESTIONS

## Unit 1 — Introduction to Web Development and Generative AI

**[2 Marks] Q1. Briefly describe the evolution of web technologies (Web 1.0 → 2.0 → 3.0).** 🔥
Web 1.0 was static, read-only pages with no user interaction. Web 2.0 introduced interactivity, social media, and user-generated content. Web 3.0 is the emerging, AI-driven, decentralized/semantic web where content is personalized and often AI-generated.

**[2 Marks] Q2. Differentiate between Front-end and Back-end development.** 🔥
Front-end handles the visual, client-side part of a website (HTML, CSS, JS) that users interact with directly. Back-end handles server-side logic, databases, and APIs that power the front-end behind the scenes.

**[2 Marks] Q3. What is Full Stack development?** ⭐
Full Stack development refers to working on both the front-end (client side) and back-end (server side, database) of a web application. A Full Stack developer can independently build a complete, working web app.

**[2 Marks] Q4. Define Artificial Intelligence.** ⭐
AI is the branch of computer science that builds systems capable of performing tasks that normally require human intelligence, such as reasoning, learning, perception, and decision-making.

**[2 Marks] Q5. Define Generative AI.** 🔥
Generative AI is a class of AI systems that create new content — text, images, code, audio, or video — by learning patterns from large training datasets, rather than simply classifying or predicting from existing data.

**[2 Marks] Q6. Differentiate between AI and Generative AI.** 🔥
AI is the broader field covering perception, reasoning, and decision-making systems. Generative AI is a subset of AI focused specifically on generating new, original content (text, code, images) based on learned patterns.

**[2 Marks] Q7. What is a Large Language Model (LLM)? Give two examples.** 🔥
An LLM is a Generative AI model trained on massive amounts of text data to understand and generate human-like language. Examples: GPT (OpenAI), Claude (Anthropic).

**[2 Marks] Q8. What is meant by the AI-assisted Software Development Lifecycle?** ⭐
It refers to integrating AI tools and LLMs into each phase of the SDLC (requirement analysis, design, coding, testing, debugging, documentation, maintenance) to speed up and improve software development.

**[2 Marks] Q9. Name any four phases of the SDLC where AI assistance is commonly used.** ⭐
Requirement Analysis (generating user stories), Coding/Implementation (auto-complete, boilerplate), Testing (generating test cases), and Debugging (explaining errors and suggesting fixes).

**[2 Marks] Q10. What is an AI coding assistant? Give two examples.** 🔥
An AI coding assistant is a tool that uses LLMs to help developers write, complete, test, or debug code through natural-language prompts. Examples: GitHub Copilot, Amazon Q.

**[2 Marks] Q11. Define Prompt Engineering.** 🔥
Prompt Engineering is the practice of designing, structuring, and refining inputs (prompts) given to an LLM to obtain accurate, relevant, and useful outputs. It acts as the "interface language" between humans and AI.

**[2 Marks] Q12. Differentiate between Zero-Shot and Few-Shot prompting.** 🔥
Zero-Shot Prompting asks the model a direct question with no examples (e.g., "Write a function to reverse a string"). Few-Shot Prompting provides 2–3 sample input-output pairs before asking the actual task, guiding the model's response style.

**[2 Marks] Q13. What is Chain-of-Thought (CoT) prompting?** 🔥
CoT prompting asks the model to reason through a problem step-by-step (e.g., "Solve this step by step: ...") rather than jumping directly to an answer, which improves accuracy on complex/logical tasks.

**[2 Marks] Q14. What is Role Prompting?** ⭐
Role Prompting assigns a persona to the LLM to guide its tone and expertise, e.g., "Act as a cybersecurity expert and review this code."

**[2 Marks] Q15. What is Retrieval-Augmented Generation (RAG)?** ⭐
RAG combines external knowledge retrieval with a prompt — relevant documents/context are injected before the query so the model can generate more accurate, grounded answers.

**[2 Marks] Q16. List any four fundamental principles of a good prompt.** 🔥
Clarity (unambiguous instructions), Context (relevant background information), Constraints (format/length/tone rules), and Examples (sample input-output to guide the model). A fifth is Role Assignment.

**[2 Marks] Q17. State any two ethical considerations in using AI tools for software development.** 🔥
(1) Code Ownership & IP Rights — AI-generated code may resemble copyrighted code, so licensing must be verified. (2) Bias and Fairness — LLMs can inherit biases from training data, leading to discriminatory logic.

**[2 Marks] Q18. What is meant by "human-in-the-loop" verification?** ⭐
It means developers remain accountable for reviewing and verifying the correctness of AI-generated code before deployment, rather than blindly trusting AI output.

---

## Unit 2 — AI-Assisted Front-End Development

**[2 Marks] Q19. Define Responsive Web Design (RWD).** 🔥
RWD is a design approach that ensures a website automatically adapts its layout, images, and content to different screen sizes and devices (mobile, tablet, desktop) using fluid grids, flexible images, and CSS media queries.

**[2 Marks] Q20. State two benefits of using Bootstrap.** 🔥
(1) Provides a pre-built responsive 12-column grid system, reducing development time. (2) Offers cross-browser compatible, ready-to-use UI components (navbars, buttons, forms, modals) for design consistency.

**[2 Marks] Q21. What is the Bootstrap 12-column grid system?** ⭐
It is a responsive layout system that divides a page's width into 12 equal columns, allowing developers to arrange content proportionally across different screen sizes without writing custom CSS for each breakpoint.

**[2 Marks] Q22. What does `<!DOCTYPE html>` declare?** 🔥
It declares that the document follows the HTML5 standard, telling the browser how to correctly parse and render the page.

**[2 Marks] Q23. Name any four HTML5 semantic tags and their purpose.** 🔥
`<header>` (site/page heading), `<nav>` (navigation links), `<main>` (primary content), `<footer>` (copyright/contact info). Semantic tags improve accessibility and SEO over generic `<div>`s.

**[2 Marks] Q24. Differentiate between `<head>` and `<body>` in an HTML5 document.** ⭐
`<head>` contains metadata, title, and linked stylesheets/scripts — it is not rendered visually. `<body>` contains the actual visible page content shown to the user.

**[2 Marks] Q25. List any four ways CSS3 improves a webpage's appearance.** 🔥
Selectors & Styling (colors, fonts, spacing), Flexbox & Grid (modern layouts without floats/tables), Animations & Transitions (`@keyframes`, `transition`), and Media Queries (adapting style to screen size).

**[2 Marks] Q26. What are CSS Media Queries used for?** 🔥
Media Queries apply different CSS rules based on screen size/device characteristics (e.g., `@media (max-width: 600px)`), enabling responsive layouts.

**[2 Marks] Q27. Define the CSS Box Model.** ⭐
The Box Model describes how every HTML element is structured as nested boxes of content, padding, border, and margin, which together determine the element's total size and spacing on the page.

**[2 Marks] Q28. What is the DOM (Document Object Model)?** 🔥
The DOM is a tree-like representation of an HTML document that JavaScript can access and manipulate to dynamically add, modify, or remove elements and content after the page has loaded, without a full reload.

**[2 Marks] Q29. Differentiate between `getElementById()` and `querySelector()`.** 🔥
`getElementById()` selects a single element by its unique ID only. `querySelector()` selects the first matching element using any CSS selector (class, tag, attribute, etc.), making it more flexible.

**[2 Marks] Q30. What is the purpose of `classList.add()` / `classList.remove()`?** ⭐
They dynamically apply or remove a CSS class from an element via JavaScript — commonly used to show error states (e.g., `input-error`) or toggle styles without a page reload.

**[2 Marks] Q31. Define Form Validation.** 🔥
Form Validation is the process of checking user input data for correctness and completeness before it is submitted or processed by the server.

**[2 Marks] Q32. Differentiate between Client-side and Server-side validation.** 🔥
Client-side validation runs in the browser (HTML5 attributes/JS) and gives instant feedback while reducing server load. Server-side validation runs on the backend, cannot be bypassed, and is essential for security.

**[2 Marks] Q33. What is an event listener? Give one example.** ⭐
An event listener is a JavaScript function that waits for a specific user action (click, input, submit) on an element and executes code in response. Example: `element.addEventListener("submit", function(){...})`.

**[2 Marks] Q34. What is `document.createElement()` used for?** ○
It dynamically creates a new HTML element (e.g., a `<span>` for an error message) via JavaScript, which can then be inserted into the DOM.

**[2 Marks] Q35. What is meant by AI-assisted UI/UX design and wireframing using AI tools?** ⭐
It refers to using AI tools to generate layout ideas, color schemes, component suggestions, or complete wireframes/mockups from natural-language prompts, speeding up the early design phase of front-end development.

**[2 Marks] Q36. What is meant by website accessibility and optimization?** ⭐
Accessibility means designing a website so it can be used by people with disabilities (proper semantic tags, alt text, contrast, keyboard navigation). Optimization means improving load speed and performance across devices.

---

# 🟡 7-MARK QUESTIONS

## Unit 1

**[7 Marks] Q1. Explain the evolution of web technologies from Web 1.0 to Web 3.0.** ⭐

### Answer Structure
- Web 1.0 — characteristics, era, limitations
- Web 2.0 — characteristics, key shift
- Web 3.0 — characteristics, AI/decentralization angle
- Comparison table

### Exam-Ready Answer
**Web 1.0 (Static Web, ~1990s–2004):**
- Read-only, static HTML pages
- No user interaction or content creation
- Information delivered one-way from site owner to visitor

**Web 2.0 (Social/Participative Web, ~2004–present):**
- Dynamic, interactive websites
- User-generated content (blogs, social media, wikis)
- Rich client-side interactivity via JavaScript/AJAX

**Web 3.0 (Intelligent/AI-driven Web, emerging):**
- AI-personalized and context-aware experiences
- Semantic web — machines understand meaning of content
- Decentralization trends and AI-generated/AI-assisted content

| Aspect | Web 1.0 | Web 2.0 | Web 3.0 |
|---|---|---|---|
| Nature | Static | Interactive | Intelligent/AI-driven |
| User role | Reader | Contributor | Co-creator with AI |
| Example | Basic HTML sites | Facebook, Wikipedia | AI copilots, personalized web apps |

---

**[7 Marks] Q2. Explain Front-end, Back-end, and Full-Stack development with examples.** 🔥

### Answer Structure
- Definitions of each
- Technologies involved
- Real-world example touching all three
- Role of a Full Stack developer

### Exam-Ready Answer
**Front-end development** builds the client-side, user-facing part of a website:
- Technologies: HTML, CSS, JavaScript, frameworks like React/Bootstrap
- Responsible for layout, styling, interactivity, and user experience

**Back-end development** builds the server-side logic:
- Technologies: server languages (Node.js, Python, Java), databases, APIs
- Responsible for business logic, data storage, authentication, and server responses

**Full Stack development** combines both:
- A Full Stack developer designs the UI (front-end) and also builds the server, database, and APIs (back-end) that power it
- Example: An e-commerce site — the front-end shows the product catalog and cart UI; the back-end manages the product database, payment processing, and order logic; a Full Stack developer builds and connects both.

---

**[7 Marks] Q3. What is Generative AI? Explain how it works with a diagram, and its applications in web development.** 🔥

### Answer Structure
- Definition
- Working (diagram: training data → model → content)
- Applications specifically in web development

### Exam-Ready Answer
**Definition:** Generative AI is a class of AI systems that create new content — text, images, code, audio, or video — by learning patterns from large training datasets, rather than simply classifying or predicting from existing data.

**How it works:**
```
[Training Data]        [Generative AI Model]        [New Content]
 (text, code,     -->     (learns patterns)     -->   Text / Code /
  images)                                              Image / Audio / Video
```
The model is trained on massive datasets, learns the statistical patterns/structure within that data, and then generates new, original output that follows those learned patterns when given a prompt.

**Applications in Web Development:**
- AI coding assistants (e.g., GitHub Copilot) generate HTML/CSS/JavaScript snippets from natural-language prompts
- Auto-completing functions and suggesting UI components
- Speeding up development by reducing boilerplate writing
- Generating layout ideas, sample content, and even test data for web projects

---

**[7 Marks] Q4. Explain the role of LLMs and AI coding assistants across the phases of the SDLC.** 🔥

### Answer Structure
- One line on LLMs supporting every phase
- Table: phase → AI role → example
- Key advantages

### Exam-Ready Answer
LLMs and AI coding assistants (ChatGPT, Claude, GitHub Copilot, Amazon Q) support every phase of the Software Development Lifecycle:

| SDLC Phase | Role of AI/LLM | Example |
|---|---|---|
| Requirement Analysis | Clarify/summarize vague requirements, generate user stories | Converting a client brief into structured user stories |
| Design | Suggest architecture patterns, generate ER/UML in text form | Suggesting a microservices architecture for an e-commerce app |
| Coding/Implementation | Auto-complete code, generate boilerplate, convert pseudocode | Copilot generating a REST API controller |
| Testing | Generate unit test cases, identify edge cases | Auto-generating Jest/PyTest test cases |
| Debugging | Explain error/stack traces, suggest fixes | Pasting a traceback and getting root-cause analysis |
| Documentation | Auto-generate docstrings, README, API docs | Generating Swagger/OpenAPI docs from code |
| Maintenance | Refactor legacy code, explain undocumented code | Modernizing old jQuery code to React |

**Key advantages:** reduces development time and repetitive effort, lowers the entry barrier for junior developers, and improves code quality via instant, best-practice suggestions.

---

**[7 Marks] Q5. Discuss the key advantages and limitations of AI coding assistants in software development.** ⭐

### Answer Structure
- Advantages (3–4 points)
- Limitations (2–3 points)
- Why human review remains essential

### Exam-Ready Answer
**Advantages:**
- Reduces development time and repetitive coding effort
- Lowers the entry barrier for junior developers through instant explanations
- Improves code quality via suggestions and best-practice recommendations
- Speeds up every SDLC phase, from requirements to maintenance

**Limitations:**
- Generated code may contain bugs, inefficiencies, or security flaws (e.g., SQL injection, hardcoded secrets)
- Can produce code resembling copyrighted/licensed material, raising IP concerns
- May inherit bias from training data, leading to unfair or incorrect logic
- Over-reliance can cause skill erosion in developers over time

**Conclusion:** Because of these limitations, human review remains essential — AI output must always be verified ("human-in-the-loop") before being trusted in production.

---

**[7 Marks] Q6. Explain any five Prompt Engineering techniques with suitable examples.** 🔥

### Answer Structure
- Table: technique, description, example
- Pick 5 of the 7 (Zero-shot, Few-shot, CoT, Role, Instruction-based, Iterative Refinement, Self-Consistency, RAG)

### Exam-Ready Answer

| Technique | Description | Example |
|---|---|---|
| Zero-Shot Prompting | Direct question, no examples given | "Write a Python function to reverse a string." |
| Few-Shot Prompting | Provide 2–3 examples before the actual task | Show sample input-output pairs, then ask for a new one |
| Chain-of-Thought (CoT) | Ask the model to reason step-by-step | "Solve this step by step: ..." |
| Role Prompting | Assign a persona to guide tone/expertise | "Act as a cybersecurity expert and review this code." |
| Instruction-based | Give explicit formatting/output rules | "Return the answer only as a JSON object." |
| Iterative Refinement | Refine output through follow-up prompts | Asking the model to "make it more concise" |
| Retrieval-Augmented (RAG) | Combine external knowledge retrieval with the prompt | Injecting relevant document context before the query |

Each technique targets a different need — Zero/Few-shot control how much guidance the model gets, CoT and Self-Consistency improve reasoning accuracy, Role and Instruction-based control tone/format, and RAG grounds answers in external facts.

---

**[7 Marks] Q7. Explain the fundamental principles of a good prompt with an example prompt.** 🔥

### Answer Structure
- Five principles, one line each
- One worked example prompt showing all five applied

### Exam-Ready Answer
**Principles:**
- **Clarity** — unambiguous, specific instructions
- **Context** — relevant background information for the task
- **Constraints** — output format, length, and tone specifications
- **Examples** — sample input/output to guide the model
- **Role Assignment** — defining a persona for the model

**Example applying all five:**
> "Act as a senior front-end developer [Role]. I am building a college event registration page in HTML/Bootstrap [Context]. Write a responsive registration form with name, email, and event dropdown fields [Clarity]. Keep the code under 40 lines and use Bootstrap classes only [Constraints]. Here is a similar form I liked: [example form] [Examples]."

This structure removes ambiguity and greatly increases the chance of getting an accurate, directly usable response from the LLM.

---

**[7 Marks] Q8. Discuss the ethical considerations involved in using AI tools for software development.** 🔥

### Answer Structure
- List each ethical concern with a one-line explanation
- Group loosely: legal, technical, human-impact

### Exam-Ready Answer
- **Code Ownership & IP Rights** — AI-generated code may resemble copyrighted/licensed code; licensing compliance must be verified
- **Bias and Fairness** — LLMs can inherit biases from training data, leading to biased or discriminatory logic
- **Security Risks** — AI-suggested code may contain vulnerabilities (e.g., SQL injection, hardcoded secrets) if not reviewed
- **Over-Reliance & Skill Erosion** — excessive dependence may reduce developers' problem-solving and debugging skills
- **Data Privacy** — pasting sensitive project data into public AI tools risks confidentiality breaches
- **Accountability** — developers remain responsible for correctness and impact of deployed code ("human-in-the-loop" verification)
- **Transparency** — disclosing AI-assisted contributions in academic/commercial projects maintains integrity

Responsible use means treating AI as an assistant that speeds up work, not a replacement for human judgment, review, and accountability.

---

**[7 Marks] Q9. Explain how Prompt Engineering acts as an interface between human intent and LLM output.** ⭐

### Answer Structure
- Why LLMs are sensitive to phrasing
- How prompt structure changes output quality
- Link to principles/techniques

### Exam-Ready Answer
Prompt Engineering is the practice of designing, structuring, and refining prompts to obtain accurate, relevant, and useful outputs from an LLM. Since LLMs are highly sensitive to how a query is phrased, prompt engineering functions as the "interface language" between human intent and machine capability — the same underlying task can produce a vague, generic answer or a precise, usable one depending purely on how it is prompted.

By applying principles (clarity, context, constraints, examples, role) and techniques (zero/few-shot, CoT, role prompting, RAG), a developer effectively "programs" the model's behavior using natural language instead of code. This is why prompt engineering is treated as a core skill bridging human problem-solving and AI-assisted execution — poor prompting wastes the model's capability, while good prompting reliably converts intent into correct output.

---

**[7 Marks] Q10. Describe the approach to building an AI-generated Personal Portfolio Website (mini project) using AI tools.** ○

### Answer Structure
- Planning/prompting
- Generation
- Review & customization
- Deployment

### Exam-Ready Answer
- **Requirement definition:** Decide sections needed (About, Projects, Skills, Contact) and overall style/theme
- **Prompting the AI tool:** Use role + context + constraints (e.g., "Act as a front-end developer, generate a responsive one-page portfolio in HTML/CSS with a dark theme, sections for About/Projects/Contact")
- **Generation:** AI coding assistant produces boilerplate HTML/CSS/JS structure
- **Review & customization:** Manually verify code correctness, fix styling issues, personalize content, check responsiveness and accessibility (human-in-the-loop)
- **Testing:** Check the page across screen sizes using media queries/DevTools
- **Deployment:** Host via GitHub Pages or similar
- **Ethical note:** Disclose AI assistance where required, and verify no copied/licensed code was reused without permission

---

## Unit 2

**[7 Marks] Q11. Explain the structure of an HTML5 document with a diagram.** 🔥

### Answer Structure
- Code skeleton
- Diagram of nesting
- Key elements explained

### Exam-Ready Answer
**Basic Structure:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Page Title</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>Header Content</header>
  <nav>Navigation Links</nav>
  <main>
    <section>Main Content</section>
  </main>
  <footer>Footer Content</footer>
</body>
</html>
```

**Nesting diagram:**
```
<html>
 └─ <head>  → meta charset, title, linked stylesheet
 └─ <body>
     ├─ <header>  → Logo / Site Title
     ├─ <nav>     → Navigation Links
     ├─ <main>
     │   └─ <section>/<article> → Main Content
     └─ <footer>  → Copyright / Contact Info
```

**Key elements:**
- `<!DOCTYPE html>` — declares the HTML5 standard
- `<head>` — metadata, title, linked stylesheets/scripts (not rendered visually)
- Semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) — improve accessibility and SEO over generic `<div>`s
- `<body>` — the visible page content

---

**[7 Marks] Q12. Explain how CSS3 improves the appearance of a webpage with an example.** 🔥

### Answer Structure
- Five capabilities
- Example code demonstrating several at once

### Exam-Ready Answer
- **Selectors & Styling** — controls colors, fonts, spacing via classes/IDs
- **Flexbox & Grid** — enable modern, responsive layouts without floats/tables
- **Animations & Transitions** — `@keyframes` and `transition` add smooth visual effects
- **Media Queries** — adapt styling based on screen size
- **Box Model Control** — margin, padding, border-radius, box-shadow enhance visual design

**Example:**
```css
.card {
    display: flex;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
}
.card:hover { transform: scale(1.05); }

@media (max-width: 600px) {
    .card { flex-direction: column; }
}
```
This single example shows the Box Model (padding, border-radius), a transition/animation effect on hover, and a media query adapting the layout on smaller screens.

---

**[7 Marks] Q13. Explain Responsive Web Design and the role/benefits of Bootstrap.** 🔥

### Answer Structure
- Definition of RWD
- Techniques used
- Bootstrap's role and two benefits

### Exam-Ready Answer
**Responsive Web Design (RWD)** is a design approach that ensures a website automatically adapts its layout, images, and content to different screen sizes and devices (mobile, tablet, desktop) using fluid grids, flexible images, and CSS media queries.

**Bootstrap's role:** Bootstrap is a front-end framework that makes implementing RWD faster and more consistent:
- Provides a pre-built responsive 12-column grid system, reducing development time
- Offers cross-browser compatible, ready-to-use UI components (navbars, buttons, forms, modals) for design consistency

Without Bootstrap, developers would need to hand-write custom media queries and components for every breakpoint; Bootstrap standardizes this into reusable classes (e.g., `col-md-6`), letting a layout reflow automatically across devices.

---

**[7 Marks] Q14. Explain Client-side and Server-side Form Validation with a code example.** 🔥

### Answer Structure
- Definitions
- Comparison
- HTML5 + JS code example

### Exam-Ready Answer
**Form Validation** is the process of checking user input data for correctness and completeness before it is submitted or processed.

- **Client-side Validation** — performed in the browser using HTML5 attributes or JavaScript (instant feedback, reduces server load)
- **Server-side Validation** — performed on the backend for security (cannot be bypassed)

**HTML5 built-in validation:**
```html
<form id="regForm">
  <input type="email" required placeholder="Enter email">
  <input type="password" minlength="8" required placeholder="Password">
  <button type="submit">Register</button>
</form>
```

**Custom JavaScript validation:**
```javascript
document.getElementById("regForm").addEventListener("submit", function(e) {
  const email = document.querySelector("input[type=email]").value;
  const password = document.querySelector("input[type=password]").value;
  if (!email.includes("@")) {
    alert("Please enter a valid email address.");
    e.preventDefault();
  }
  if (password.length < 8) {
    alert("Password must be at least 8 characters.");
    e.preventDefault();
  }
});
```
**Benefits:** immediate error feedback, prevents invalid data reaching the server, reduces unnecessary server load — but server-side validation is still required since client-side checks can be bypassed.

---

**[7 Marks] Q15. Explain DOM Manipulation with common methods and an example.** 🔥

### Answer Structure
- Definition
- Method table
- Example

### Exam-Ready Answer
**DOM Manipulation** is using JavaScript to dynamically access, modify, add, or remove HTML elements and their attributes/content after the page has loaded — without requiring a full page reload.

| Method | Purpose |
|---|---|
| `document.getElementById()` | Select an element by ID |
| `document.querySelector()` | Select using CSS selectors |
| `element.innerHTML` | Get/set HTML content |
| `element.classList.add/remove()` | Dynamically apply CSS classes |
| `element.addEventListener()` | Attach interactive event handlers |
| `document.createElement()` | Dynamically create new elements |

**Example — dynamic feedback:**
```javascript
const emailInput = document.querySelector("input[type=email]");
const errorMsg = document.createElement("span");
errorMsg.style.color = "red";

emailInput.addEventListener("input", function() {
  if (!emailInput.value.includes("@")) {
    errorMsg.textContent = "Invalid email format";
    emailInput.after(errorMsg);
    emailInput.classList.add("input-error");
  } else {
    errorMsg.textContent = "";
    emailInput.classList.remove("input-error");
  }
});
```

---

**[7 Marks] Q16. Explain the combined flow of Form Validation + DOM Manipulation with a diagram.** 🔥

### Answer Structure
- Step-by-step flow
- Diagram
- Both outcomes (valid/invalid)

### Exam-Ready Answer
```
User types in     'input'/'submit'     JS reads value via        Validation check
form field    -->  event fires    -->  getElementById/       --> (regex, length,
                                        querySelector             required)
                                                                       │
                                                    ┌──────────────────┴───────────────┐
                                                    ▼                                    ▼
                                            Valid: submit form data          Invalid: DOM update
                                                                              (classList.add('input-error'),
                                                                               createElement()+textContent,
                                                                               innerHTML update)
```

**Steps:**
1. User types in a form field, triggering an `input` or `submit` event
2. JavaScript reads the current value using `getElementById`/`querySelector`
3. A validation check runs (regex pattern, length, required field)
4. If **valid** — the form data is submitted normally
5. If **invalid** — the DOM is updated instantly: an error message is created/shown (`createElement`, `textContent`) and the field is visually flagged (`classList.add('input-error')`) — all without a page reload

---

**[7 Marks] Q17. Discuss the combined impact of Form Validation and DOM Manipulation on usability.** ⭐

### Answer Structure
- Table of five usability aspects
- One-line takeaway

### Exam-Ready Answer

| Aspect | Contribution |
|---|---|
| Real-time Feedback | Users see validation errors instantly without page reload |
| Reduced Frustration | Errors are caught early, avoiding repeated failed submissions |
| Dynamic UI Updates | DOM manipulation enables live search, dropdowns, modals, dashboards |
| Accessibility | Highlighting specific fields (via classList) guides users to errors |
| Performance | Avoids unnecessary full-page reloads — an app-like (SPA) experience |

Together, form validation ensures data integrity and correctness, while DOM manipulation enables dynamic, responsive interfaces — combined, they form the backbone of modern, user-friendly web applications.

---

**[7 Marks] Q18. Explain how AI tools assist in UI/UX design and generating responsive layouts.** ⭐

### Answer Structure
- Where AI fits in the design process
- Concrete examples of AI-assisted UI/UX
- Benefit over manual design

### Exam-Ready Answer
AI-assisted UI/UX design uses Generative AI tools to speed up and improve the early, exploratory stages of front-end design:
- Generating multiple layout/color-scheme options from a text prompt
- Suggesting component placement based on common UX patterns
- Auto-generating responsive HTML/CSS layouts that already include media queries and grid/flexbox structure
- Producing sample content (placeholder text/images) to preview a design faster

**Benefit:** designers/developers can go from an idea to a working, responsive prototype in minutes instead of hours, though human review is still needed to refine usability, branding consistency, and accessibility.

---

**[7 Marks] Q19. Explain wireframing using AI tools and its role in front-end development.** ⭐

### Answer Structure
- What wireframing is
- How AI changes the process
- Where it fits in the workflow

### Exam-Ready Answer
A **wireframe** is a low-fidelity, skeletal layout of a webpage showing the placement of key elements (header, navigation, content blocks, footer) before visual design or coding begins.

**Role of AI in wireframing:**
- Converts a text description ("a college event page with a banner, event list, and registration form") directly into a rough visual/HTML layout
- Speeds up the ideation phase, letting developers quickly compare multiple layout options
- Reduces reliance on separate design tools for early-stage planning

**In the workflow:** AI-generated wireframes act as a starting point that is then refined with real content, Bootstrap components, and custom CSS — bridging the gap between an idea and a functional responsive page.

---

**[7 Marks] Q20. Explain website accessibility and optimization techniques in web design.** ⭐

### Answer Structure
- Accessibility techniques
- Optimization techniques
- Why both matter

### Exam-Ready Answer
**Accessibility (making a site usable by everyone, including people with disabilities):**
- Using semantic HTML tags (`<nav>`, `<main>`, `<header>`) instead of generic `<div>`s
- Adding `alt` text to images for screen readers
- Ensuring sufficient color contrast and keyboard navigability
- Using ARIA labels where semantic HTML isn't enough

**Optimization (improving speed/performance):**
- Compressing images and minifying CSS/JS
- Using responsive images (`srcset`) so smaller devices don't load oversized files
- Reducing unnecessary DOM elements and reflows
- Leveraging browser caching

Both matter because a fast, accessible site reaches a wider audience, improves SEO ranking, and provides a better overall user experience.

---

**[7 Marks] Q21. Describe the approach to building a College Event Management Website (mini project) with a responsive interface generated using AI tools.** ○

### Answer Structure
- Planning
- AI-assisted generation
- Implementation with Bootstrap
- Testing

### Exam-Ready Answer
- **Requirement gathering:** Identify pages needed — event listing, event details, registration form, admin/contact
- **AI-assisted wireframing:** Prompt an AI tool for a responsive layout structure (banner, event cards grid, registration form)
- **Front-end build:** Implement using semantic HTML5 + Bootstrap grid for the event cards and CSS3 for styling/animations
- **Form validation:** Add client-side validation (HTML5 attributes + JS) for the registration form, with DOM manipulation for real-time error feedback
- **Responsiveness testing:** Verify layout across mobile/tablet/desktop using media queries and browser DevTools
- **Review:** Manually verify AI-generated code for bugs, accessibility (alt text, semantic tags), and correctness before final submission

---

# 🔴 11-MARK QUESTIONS

## Unit 1

**[11 Marks] Q1. Explain Generative AI in detail — concept, working, and applications in software/web development.** 🔥

### Answer Structure
- Definition (2 marks worth)
- Working with diagram (3 marks worth)
- Applications in web dev (3 marks worth)
- Applications in broader software development (2 marks worth)
- Conclusion (1 mark worth)

### Exam-Ready Answer
**Concept:** Generative AI is a class of artificial intelligence systems that create new content — text, images, code, audio, or video — by learning patterns from large training datasets, rather than simply classifying or predicting from existing data. Unlike traditional/discriminative AI (which labels or predicts), Generative AI produces original output.

**How it works:**
```
[Training Data]        [Generative AI Model]        [New Content]
 (text, code,     -->     (learns patterns)     -->   Text / Code /
  images)                                              Image / Audio / Video
```
The model is trained on massive datasets and internalizes statistical patterns/structure. Given a prompt, it generates new output consistent with those learned patterns — e.g., GitHub Copilot generates HTML/CSS/JS code from a natural-language description.

**Applications in Web Development:**
- AI coding assistants generating HTML/CSS/JavaScript snippets, complete functions, or UI component suggestions
- Auto-generating responsive layouts and wireframes
- Generating placeholder/sample content for prototypes

**Applications in broader Software Development:**
- Requirement analysis — turning briefs into user stories
- Design — suggesting architecture patterns
- Testing — auto-generating test cases
- Documentation — generating README/API docs
- Maintenance — refactoring and explaining legacy code

**Conclusion:** Generative AI has become central to modern software/web development by compressing the time between idea and working prototype, though outputs still require human verification for correctness, security, and originality.

---

**[11 Marks] Q2. Discuss in detail the role of LLMs and AI coding assistants across the SDLC, including advantages and limitations.** 🔥

### Answer Structure
- Intro
- Phase-wise table with examples
- Advantages
- Limitations
- Conclusion

### Exam-Ready Answer
Large Language Models (LLMs) and AI coding assistants (ChatGPT, Claude, GitHub Copilot, Amazon Q) support every phase of the Software Development Lifecycle:

```
[Requirement    [Design]    [Coding/       [Testing]   [Debugging]  [Documentation] [Maintenance]
 Analysis]                  Implementation]
    │              │              │             │            │              │              │
Clarify reqs,  Suggest      Auto-complete,  Generate    Explain       Auto-generate    Refactor
generate       architecture boilerplate     test cases  errors,       docs/README      legacy code
user stories                                            fix bugs
```

| SDLC Phase | Role of AI/LLM | Example |
|---|---|---|
| Requirement Analysis | Clarify/summarize requirements, generate user stories | Converting a client brief into structured user stories |
| Design | Suggest architecture patterns, generate ER/UML in text | Suggesting microservices for an e-commerce app |
| Coding/Implementation | Auto-complete code, generate boilerplate, convert pseudocode | Copilot generating a REST API controller |
| Testing | Generate unit test cases, identify edge cases | Auto-generating Jest/PyTest test cases |
| Debugging | Explain error/stack traces, suggest fixes | Root-cause analysis from a pasted traceback |
| Documentation | Auto-generate docstrings, README, API docs | Generating Swagger/OpenAPI docs |
| Maintenance | Refactor legacy code, explain undocumented code | Modernizing old jQuery code to React |

**Advantages:** reduces development time and repetitive effort, lowers the entry barrier for junior developers, improves code quality through instant best-practice suggestions.

**Limitations:** generated code may contain bugs or security flaws (SQL injection, hardcoded secrets); can raise IP concerns by resembling licensed code; can inherit training-data bias; over-reliance risks skill erosion.

**Conclusion:** AI assistance now touches every SDLC phase, but human review ("human-in-the-loop") remains essential to ensure security, correctness, and originality.

---

**[11 Marks] Q3. Explain Prompt Engineering in detail — definition, fundamental principles, and all major techniques with examples.** 🔥

### Answer Structure
- Definition
- Why it matters
- Principles
- Techniques table (all 7)
- Conclusion

### Exam-Ready Answer
**Definition:** Prompt Engineering is the practice of designing, structuring, and refining inputs (prompts) given to an LLM to obtain accurate, relevant, and useful outputs. Since LLMs are highly sensitive to how a query is phrased, prompt engineering acts as the "interface language" between humans and AI systems.

**Fundamental Principles of a Good Prompt:**
- **Clarity** — unambiguous, specific instructions
- **Context** — relevant background information for the task
- **Constraints** — output format, length, tone specifications
- **Examples** — sample input/output to guide the model
- **Role Assignment** — defining a persona for the model (e.g., "Act as a senior Python developer")

**Key Prompt Engineering Techniques:**

| Technique | Description | Example |
|---|---|---|
| Zero-Shot Prompting | Direct question, no examples | "Write a Python function to reverse a string." |
| Few-Shot Prompting | Provide 2–3 examples before the task | Sample input-output pairs, then a new request |
| Chain-of-Thought (CoT) | Ask the model to reason step-by-step | "Solve this step by step: ..." |
| Role Prompting | Assign a persona to guide tone/expertise | "Act as a cybersecurity expert and review this code." |
| Instruction-based | Give explicit formatting/output rules | "Return the answer only as a JSON object." |
| Iterative Refinement | Refine output through follow-up prompts | Asking the model to "make it more concise" |
| Self-Consistency | Generate multiple reasoning paths, pick the most consistent | Useful in complex math/logic problems |
| Retrieval-Augmented (RAG) | Combine external knowledge retrieval with the prompt | Injecting relevant document context before the query |

**Conclusion:** Prompt Engineering is a critical, structured skill — mastering its principles and techniques directly determines how effectively a developer can extract accurate, production-ready output from an LLM.

---

**[11 Marks] Q4. Discuss in detail the ethical and responsible use of AI in software development.** 🔥

### Answer Structure
- Intro (why ethics matters here)
- Each concern explained (7 points)
- Mitigation/best practice for each briefly
- Conclusion

### Exam-Ready Answer
As AI tools become embedded in the SDLC, using them responsibly is as important as using them effectively. Key ethical dimensions:

- **Code Ownership & IP Rights** — AI-generated code may resemble copyrighted/licensed code. *Mitigation:* verify licensing compliance before reuse.
- **Bias and Fairness** — LLMs can inherit biases from training data, leading to biased or discriminatory logic. *Mitigation:* review AI-generated logic/content for fairness, especially in user-facing decisions.
- **Security Risks** — AI-suggested code may contain vulnerabilities (SQL injection, hardcoded secrets) if not reviewed. *Mitigation:* mandatory code review/security scanning before deployment.
- **Over-Reliance & Skill Erosion** — excessive dependence may reduce developers' problem-solving and debugging skills. *Mitigation:* use AI to assist, not replace, core learning and practice.
- **Data Privacy** — pasting sensitive project data into public AI tools risks confidentiality breaches. *Mitigation:* avoid sharing proprietary/sensitive data with public-facing AI tools.
- **Accountability** — developers remain responsible for the correctness and impact of deployed code. *Mitigation:* human-in-the-loop verification at every stage.
- **Transparency** — disclosing AI-assisted contributions in academic/commercial projects maintains integrity. *Mitigation:* explicitly document what was AI-generated vs. human-written.

**Conclusion:** Prompt Engineering and Generative AI significantly boost developer productivity, but responsible use — grounded in accountability, transparency, and human review — is essential to safeguard code quality, security, and professional integrity.

---

**[11 Marks] Q5. Explain Front-end, Back-end, and Full-Stack development in detail, along with how Generative AI assists each.** ⭐

### Answer Structure
- Define each layer
- Technologies
- AI's role in each
- Example tying all together

### Exam-Ready Answer
**Front-end development** is the client-side layer users directly see and interact with — built using HTML, CSS, JavaScript, and frameworks/libraries (Bootstrap, React). It handles layout, styling, and interactivity.
*AI's role:* generating HTML/CSS/JS snippets, suggesting responsive layouts, wireframing, and UI component code from prompts.

**Back-end development** is the server-side layer — built using server languages (Node.js, Python, Java), databases, and APIs. It handles business logic, data storage, and authentication.
*AI's role:* generating REST API boilerplate, suggesting database schemas, writing server-side validation logic, and explaining backend error traces.

**Full-Stack development** combines both — a Full Stack developer builds the complete application, connecting the front-end UI to the back-end logic and database.
*AI's role:* assisting across the entire stack simultaneously — e.g., generating both the front-end form and the back-end endpoint that receives its data, keeping them consistent.

**Example:** For a college event registration site, the front-end (HTML/CSS/Bootstrap form) is AI-assisted for responsive design, while the back-end (API that stores registrations in a database) is AI-assisted for boilerplate code generation — together forming a Full Stack, AI-accelerated build.

---

**[11 Marks] Q6. Discuss the evolution of web technologies (Web 1.0 → 3.0) and the impact of Generative AI on modern web development.** ⭐

### Answer Structure
- Web 1.0/2.0/3.0 explained
- Comparison table
- How Generative AI fits into/accelerates Web 3.0
- Conclusion

### Exam-Ready Answer
**Web 1.0 (Static Web):** Read-only pages, no interactivity, one-way information delivery.

**Web 2.0 (Social/Participative Web):** Dynamic, interactive sites with user-generated content (blogs, social media), enabled by JavaScript/AJAX.

**Web 3.0 (Intelligent/AI-driven Web):** Emerging web characterized by AI-personalization, semantic understanding, and AI-assisted or AI-generated content and interfaces.

| Aspect | Web 1.0 | Web 2.0 | Web 3.0 |
|---|---|---|---|
| Nature | Static | Interactive | Intelligent/AI-driven |
| Content creation | Owner-only | Users | Users + AI co-creation |
| Personalization | None | Limited (algorithms) | Deep (LLM-driven) |
| Example | Basic HTML pages | Facebook, Wikipedia | AI copilots, adaptive web apps |

**Impact of Generative AI on modern web development:** Generative AI accelerates every stage of building a Web 3.0-style site — auto-generating front-end code, suggesting personalized layouts, and even producing dynamic content on the fly. This shifts the developer's role from writing every line manually to prompting, reviewing, and refining AI output — making rapid, iterative web development the new norm.

**Conclusion:** Web technology has evolved from static delivery to social interaction to AI-driven intelligence, and Generative AI is now a core enabler of this latest shift, directly influencing how developers build and how users experience the web.

---

**[11 Marks] Q7. With reference to the AI-generated Personal Portfolio Website mini project, explain the end-to-end process of using AI tools to build a web project, highlighting ethical/quality considerations.** ○

### Answer Structure
- Planning
- Prompting
- Generation
- Review/quality checks
- Ethical checks
- Deployment
- Conclusion

### Exam-Ready Answer
**1. Planning:** Define the sections needed (About, Skills, Projects, Contact), target audience, and visual style.

**2. Prompting:** Apply prompt engineering principles — Role ("Act as a front-end developer"), Context (portfolio purpose), Constraints (responsive, dark theme, under X lines), and Examples (reference site/style) — to get a well-targeted AI response.

**3. Generation:** The AI coding assistant produces an HTML/CSS/JS skeleton — layout, navigation, sections, and basic styling.

**4. Review & Quality Checks:**
- Verify HTML5 semantic structure and accessibility (alt text, contrast)
- Test responsiveness across devices using media queries
- Check for bugs, broken links, and unoptimized code

**5. Ethical Considerations:**
- Confirm no copyrighted design/code was reused without attribution
- Avoid pasting personal/sensitive data into public AI tools
- Disclose AI assistance if required by the course/evaluator
- Apply human-in-the-loop review before treating the output as final

**6. Deployment:** Host the finished site (e.g., GitHub Pages) and verify it loads correctly in production.

**Conclusion:** This mini project demonstrates the full AI-assisted development loop — prompt, generate, review, refine, deploy — while reinforcing that responsible, verified use of AI is what makes the output genuinely production-ready.

---

## Unit 2

**[11 Marks] Q8. Explain the structure of an HTML5 document in detail, covering DOCTYPE, head, body, and semantic tags, with a diagram and code example.** 🔥

### Answer Structure
- Full code skeleton
- Diagram
- Detailed explanation of every key element
- Why semantic tags matter

### Exam-Ready Answer
**Code:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Page Title</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>Header Content</header>
  <nav>Navigation Links</nav>
  <main>
    <section>Main Content</section>
  </main>
  <footer>Footer Content</footer>
</body>
</html>
```

**Diagram:**
```
<html>
 └─ <head>  → <meta charset>, <title>, <link rel="stylesheet">
 └─ <body>
     ├─ <header>  → Logo / Site Title
     ├─ <nav>     → Navigation Links
     ├─ <main>
     │   └─ <section>/<article> → Main Content
     └─ <footer>  → Copyright / Contact Info
```

**Detailed explanation:**
- `<!DOCTYPE html>` — declares the document as HTML5, so the browser renders it in standards mode
- `<html lang="en">` — root element; the `lang` attribute aids accessibility and SEO
- `<head>` — contains metadata, page title, and linked stylesheets/scripts; not rendered visually. The `viewport` meta tag is essential for responsive design on mobile devices
- `<body>` — contains all visible content
- **Semantic tags** (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) replace generic `<div>`s with meaningful structure. This improves:
  - **Accessibility** — screen readers can navigate the page structure meaningfully
  - **SEO** — search engines better understand page hierarchy and importance
  - **Maintainability** — code is easier to read and edit

**Conclusion:** A well-structured HTML5 document isn't just functional — it directly supports accessibility, SEO, and long-term maintainability, which is why examiners test this structure closely.

---

**[11 Marks] Q9. Explain CSS3 in detail — selectors, box model, Flexbox/Grid, media queries, and animations — with code examples.** 🔥

### Answer Structure
- Five capability areas explained
- Code example combining several
- Why CSS3 matters for responsive design

### Exam-Ready Answer
CSS3 improves a webpage's appearance and behavior through five major capabilities:

- **Selectors & Styling** — target elements by tag, class, or ID to control colors, fonts, and spacing
- **Box Model Control** — every element is a box of `content → padding → border → margin`; controlling these (plus `border-radius`, `box-shadow`) shapes visual design
- **Flexbox & Grid** — modern layout systems that arrange elements in flexible rows/columns or a full 2D grid, replacing older float/table-based layouts
- **Animations & Transitions** — `@keyframes` define multi-step animations; `transition` smoothly animates property changes (e.g., on hover)
- **Media Queries** — apply different CSS rules based on screen width/device, the foundation of responsive design

**Example combining these:**
```css
.card {
    display: flex;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
}
.card:hover { transform: scale(1.05); }

@media (max-width: 600px) {
    .card { flex-direction: column; }
}
```
Here, `display: flex` arranges card content, the box model properties (`padding`, `border-radius`, `box-shadow`) style it, `transition` animates the hover effect, and the `@media` query reflows the layout on small screens.

**Why it matters:** Together, these CSS3 features let developers build visually polished, responsive interfaces without relying on images/tables for layout — directly enabling Responsive Web Design.

---

**[11 Marks] Q10. Explain Responsive Web Design and Bootstrap in detail, covering the grid system, components, and benefits, with code example.** 🔥

### Answer Structure
- RWD definition and techniques
- Bootstrap grid explained
- Bootstrap components
- Benefits
- Code example

### Exam-Ready Answer
**Responsive Web Design (RWD)** ensures a website automatically adapts its layout, images, and content to different screen sizes and devices, using:
- Fluid grids (relative units instead of fixed pixels)
- Flexible images (scale within their container)
- CSS media queries (apply different styles per screen size)

**Bootstrap** is a front-end framework that implements RWD principles out of the box:
- **12-column grid system** — the page width is divided into 12 equal columns; developers assign elements a column-span (e.g., `col-md-6` = half-width on medium screens+), and Bootstrap automatically reflows this on smaller screens
- **Pre-built UI components** — navbars, buttons, forms, modals, cards — all cross-browser compatible and styled consistently

**Benefits:**
- Reduces development time (no need to hand-code grid/media-query logic)
- Ensures design consistency across the site
- Cross-browser compatibility out of the box
- Mobile-first by default

**Example:**
```html
<div class="row">
  <div class="col-md-6">Left Column</div>
  <div class="col-md-6">Right Column</div>
</div>
```
On medium+ screens this shows two equal columns side by side; Bootstrap automatically stacks them vertically on smaller screens without extra media query code.

**Conclusion:** Bootstrap operationalizes Responsive Web Design principles into reusable classes, making it a standard tool for quickly building consistent, responsive front-ends.

---

**[11 Marks] Q11. Explain Form Validation in detail — client-side vs server-side, HTML5 built-in validation, and custom JavaScript validation — with code examples.** 🔥

### Answer Structure
- Definition
- Client vs server comparison
- HTML5 validation code
- Custom JS validation code
- Benefits

### Exam-Ready Answer
**Definition:** Form Validation is the process of checking user input data for correctness and completeness before it is submitted or processed.

**Client-side vs Server-side:**

| Aspect | Client-side | Server-side |
|---|---|---|
| Where it runs | Browser | Backend server |
| Feedback speed | Instant | After submission |
| Can be bypassed? | Yes | No |
| Purpose | UX/immediate feedback | Security/data integrity |

**HTML5 built-in validation:**
```html
<form id="regForm">
  <input type="email" required placeholder="Enter email">
  <input type="password" minlength="8" required placeholder="Password">
  <button type="submit">Register</button>
</form>
```
The `required`, `type="email"`, and `minlength` attributes let the browser auto-validate without any JavaScript.

**Custom JavaScript validation:**
```javascript
document.getElementById("regForm").addEventListener("submit", function(e) {
  const email = document.querySelector("input[type=email]").value;
  const password = document.querySelector("input[type=password]").value;
  if (!email.includes("@")) {
    alert("Please enter a valid email address.");
    e.preventDefault();
  }
  if (password.length < 8) {
    alert("Password must be at least 8 characters.");
    e.preventDefault();
  }
});
```
Custom JS validation allows more complex rules (regex patterns, matching password fields, custom error messages) beyond what HTML5 attributes alone can express.

**Benefits:** immediate error feedback improves UX, prevents invalid/incomplete data reaching the server, and reduces unnecessary server load — but server-side validation must always back it up since client-side checks can be disabled or bypassed.

---

**[11 Marks] Q12. Explain DOM Manipulation in detail — definition, key methods, and a working example.** 🔥

### Answer Structure
- Definition
- Full method table
- Detailed example with explanation
- Real-world use cases

### Exam-Ready Answer
**Definition:** DOM Manipulation is the use of JavaScript to dynamically access, modify, add, or remove HTML elements and their attributes/content after the page has loaded — without requiring a full page reload. The DOM (Document Object Model) represents the HTML document as a tree structure that JavaScript can traverse and change.

**Key Methods:**

| Method | Purpose |
|---|---|
| `document.getElementById()` | Select an element by ID |
| `document.querySelector()` | Select using CSS selectors |
| `element.innerHTML` | Get/set HTML content |
| `element.classList.add()/remove()` | Dynamically apply/remove CSS classes |
| `element.addEventListener()` | Attach interactive event handlers |
| `document.createElement()` | Dynamically create new elements |

**Example — dynamic feedback using DOM:**
```javascript
const emailInput = document.querySelector("input[type=email]");
const errorMsg = document.createElement("span");
errorMsg.style.color = "red";

emailInput.addEventListener("input", function() {
  if (!emailInput.value.includes("@")) {
    errorMsg.textContent = "Invalid email format";
    emailInput.after(errorMsg);
    emailInput.classList.add("input-error");
  } else {
    errorMsg.textContent = "";
    emailInput.classList.remove("input-error");
  }
});
```
Here, `createElement()` builds a new `<span>` for the error message, `addEventListener()` listens for typing, `classList.add/remove()` visually flags the invalid field, and `after()` inserts the error message into the DOM — all live, with no page reload.

**Real-world use cases:** live search suggestions, dynamic dropdowns, interactive dashboards, real-time form feedback, single-page-application (SPA)-like experiences.

---

**[11 Marks] Q13. Explain the combined flow of Form Validation and DOM Manipulation with a diagram, and discuss its impact on usability.** 🔥

### Answer Structure
- Combined flow diagram
- Step-by-step explanation
- Usability impact table
- Conclusion

### Exam-Ready Answer
**Combined flow diagram:**
```
User types in     'input'/'submit'     JS reads value via        Validation check
form field    -->  event fires    -->  getElementById/       --> (regex, length,
                                        querySelector             required)
                                                                       │
                                                    ┌──────────────────┴───────────────┐
                                                    ▼                                    ▼
                                            Valid: submit form data          Invalid: DOM update
                                                                              (classList.add('input-error'),
                                                                               createElement()+textContent,
                                                                               innerHTML update)
```

**Step-by-step:**
1. The user types into a form field, triggering an `input` or `submit` event
2. JavaScript reads the value via `getElementById`/`querySelector`
3. A validation check runs (regex, length, required)
4. If valid, the form submits normally; if invalid, the DOM is updated instantly with an error message and a visual flag on the field

**Usability impact:**

| Aspect | Contribution |
|---|---|
| Real-time Feedback | Users see validation errors instantly without page reload |
| Reduced Frustration | Errors are caught early, avoiding repeated failed submissions |
| Dynamic UI Updates | DOM manipulation enables live search, dropdowns, modals, dashboards |
| Accessibility | Highlighting specific fields (via classList) guides users to errors |
| Performance | Avoids unnecessary full-page reloads — an app-like (SPA) experience |

**Conclusion:** Form validation ensures data integrity and correctness, while DOM manipulation enables dynamic, responsive, interactive interfaces. Together, they form the backbone of modern, user-friendly web applications — reducing errors, improving engagement, and enhancing overall usability.

---

**[11 Marks] Q14. Discuss AI-assisted UI/UX design, AI-generated responsive layouts, and wireframing using AI tools in detail.** ⭐

### Answer Structure
- UI/UX design with AI
- Responsive layout generation
- Wireframing with AI
- Overall workflow and benefit

### Exam-Ready Answer
**AI-assisted UI/UX design:** AI tools generate layout options, color palettes, and component suggestions from a text description, letting designers/developers quickly explore multiple directions before committing to one. Instead of manually sketching every option, a prompt like "suggest 3 card-based layouts for a product page" produces instant starting points.

**AI-generated responsive layouts:** Generative AI can directly output HTML/CSS structured with Flexbox/Grid and media queries already built in, producing a layout that adapts across devices without the developer manually writing every breakpoint.

**Wireframing using AI tools:** A wireframe is a low-fidelity skeletal layout showing element placement (header, nav, content blocks, footer) before visual design begins. AI tools can convert a plain-text description directly into a rough layout/HTML skeleton, replacing hours of manual wireframing with a quick draft that's then refined.

**Combined workflow:**
```
Text prompt  -->  AI-generated wireframe  -->  AI-generated responsive HTML/CSS  -->  Human review & refinement
```

**Benefit:** This workflow drastically compresses the time from idea to a working, responsive prototype — but human review remains essential to fix usability issues, ensure brand consistency, and verify accessibility, since AI output is a starting point, not a final product.

---

**[11 Marks] Q15. Explain website accessibility and optimization in detail, with best practices.** ⭐

### Answer Structure
- Accessibility — definition + techniques
- Optimization — definition + techniques
- Why both matter (business/legal/UX angle)

### Exam-Ready Answer
**Website Accessibility** means designing a site so it can be used by everyone, including people with visual, auditory, motor, or cognitive disabilities.

**Best practices:**
- Use semantic HTML (`<nav>`, `<main>`, `<header>`, `<footer>`) instead of generic `<div>`s so screen readers can interpret structure
- Provide `alt` text for all meaningful images
- Ensure sufficient color contrast between text and background
- Make all interactive elements keyboard-navigable (tab order, focus states)
- Use ARIA attributes where native semantics fall short
- Label form fields clearly for assistive technology

**Website Optimization** means improving a site's speed and performance across devices and network conditions.

**Best practices:**
- Compress and lazy-load images
- Minify CSS/JS files
- Use responsive images (`srcset`) so smaller devices don't download oversized files
- Reduce unnecessary DOM elements and reflows
- Leverage browser caching and a CDN where possible

**Why both matter:** Accessibility ensures legal compliance and inclusivity, widening the reach of the site. Optimization directly affects user retention (slow sites lose visitors) and SEO ranking, since search engines factor in page speed. Together, they represent the difference between a site that merely works and one that works well for everyone.

---

**[11 Marks] Q16. Describe in detail the approach to building a College Event Management Website (mini project) with a responsive interface generated using AI tools.** ○

### Answer Structure
- Requirement gathering
- AI-assisted wireframing
- Front-end implementation
- Form validation + DOM manipulation
- Testing
- Review/ethical checks
- Conclusion

### Exam-Ready Answer
**1. Requirement gathering:** Identify core pages — homepage/event listing, event detail page, registration form, and admin/contact section.

**2. AI-assisted wireframing:** Prompt an AI tool (with role + context + constraints) to generate a responsive layout skeleton — a banner/hero section, a grid of event cards, and a registration form.

**3. Front-end implementation:**
- Use semantic HTML5 structure (`<header>`, `<nav>`, `<main>`, `<section>` for each event, `<footer>`)
- Use Bootstrap's 12-column grid for the responsive event-card layout
- Apply CSS3 (Flexbox/Grid, media queries, transitions) for styling and hover effects

**4. Form validation + DOM manipulation:**
- Add HTML5 attributes (`required`, `type="email"`) for instant client-side checks
- Add custom JavaScript validation for stricter rules (e.g., valid event selection)
- Use DOM manipulation (`classList.add/remove`, `createElement`) to show real-time error messages without reloading the page

**5. Responsiveness testing:** Test the layout across mobile, tablet, and desktop breakpoints using browser DevTools and media queries.

**6. Review & ethical checks:** Manually verify AI-generated code for bugs and security issues, check accessibility (alt text, semantic tags, contrast), and confirm no unlicensed code/assets were used.

**7. Conclusion:** This mini project demonstrates the complete AI-assisted front-end workflow — from AI-generated wireframe to a validated, responsive, accessible event management interface — reinforcing that AI accelerates development while human review ensures quality and correctness.

---

# 🚨 ABSOLUTE MUST-PREPARE QUESTIONS

## 🔥 TOP 10 — MUST DO
1. **[11M]** Generative AI — concept, working, applications (U1-11M-Q1)
2. **[11M]** Prompt Engineering — principles + all techniques (U1-11M-Q3)
3. **[7M]** Role of LLMs/AI coding assistants across SDLC (U1-7M-Q4)
4. **[11M]** Ethical and responsible use of AI in software development (U1-11M-Q4)
5. **[11M]** HTML5 document structure in detail (U2-11M-Q8)
6. **[11M]** CSS3 in detail — selectors, box model, Flexbox/Grid, media queries (U2-11M-Q9)
7. **[11M]** DOM Manipulation in detail (U2-11M-Q12)
8. **[11M]** Form Validation in detail — client vs server, HTML5 + JS (U2-11M-Q11)
9. **[7M]** Responsive Web Design + Bootstrap (U2-7M-Q13)
10. **[2M]** Define Prompt Engineering (U1-2M-Q11)

## ⭐ NEXT 15 — SHOULD DO
1. **[7M]** Front-end, Back-end, Full-Stack development (U1-7M-Q2)
2. **[7M]** Five Prompt Engineering techniques with examples (U1-7M-Q6)
3. **[7M]** Fundamental principles of a good prompt (U1-7M-Q7)
4. **[7M]** Ethical considerations in using AI tools (U1-7M-Q8)
5. **[7M]** Advantages and limitations of AI coding assistants (U1-7M-Q5)
6. **[7M]** HTML5 document structure (U2-7M-Q11)
7. **[7M]** How CSS3 improves webpage appearance (U2-7M-Q12)
8. **[7M]** Client-side vs Server-side Form Validation (U2-7M-Q14)
9. **[7M]** DOM Manipulation with methods and example (U2-7M-Q15)
10. **[7M]** Combined flow of Form Validation + DOM Manipulation (U2-7M-Q16)
11. **[11M]** Front-end, Back-end, Full-Stack + AI's role in each (U1-11M-Q5)
12. **[11M]** Web 1.0→3.0 evolution + impact of Generative AI (U1-11M-Q6)
13. **[11M]** Responsive Web Design + Bootstrap in detail (U2-11M-Q10)
14. **[11M]** Combined flow + usability impact (U2-11M-Q13)
15. **[2M]** Differentiate Zero-shot vs Few-shot prompting (U1-2M-Q12)

## ○ IF TIME PERMITS
1. **[2M]** Evolution of web technologies (U1-2M-Q1)
2. **[2M]** AI-assisted SDLC definition (U1-2M-Q8)
3. **[2M]** RAG definition (U1-2M-Q15)
4. **[2M]** Bootstrap 12-column grid (U2-2M-Q21)
5. **[2M]** Box Model definition (U2-2M-Q27)
6. **[7M]** AI-generated Personal Portfolio Website mini project (U1-7M-Q10)
7. **[7M]** College Event Management Website mini project (U2-7M-Q21)
8. **[7M]** AI-assisted UI/UX design and responsive layouts (U2-7M-Q18)
9. **[7M]** Wireframing using AI tools (U2-7M-Q19)
10. **[7M]** Website accessibility and optimization (U2-7M-Q20)
11. **[11M]** AI-generated Portfolio Website — end-to-end process (U1-11M-Q7)
12. **[11M]** College Event Management Website — full mini project (U2-11M-Q16)
13. **[11M]** AI-assisted UI/UX, layouts, wireframing in detail (U2-11M-Q14)
14. **[11M]** Website accessibility and optimization in detail (U2-11M-Q15)

---

# 📊 SYLLABUS COVERAGE MATRIX

| Syllabus Topic | 2M | 7M | 11M | Priority |
|---|---|---|---|---|
| Evolution of web technologies | ✓ | ✓ | ✓ | High |
| Front-end / Back-end / Full Stack | ✓ | ✓ | ✓ | High |
| Introduction to AI & Generative AI | ✓ | ✓ | ✓ | Very High |
| Large Language Models (LLMs) | ✓ | — | — | Very High |
| AI-assisted SDLC | ✓ | ✓ | ✓ | Very High |
| Overview of AI coding assistants | ✓ | ✓ | — | High |
| Prompt Engineering fundamentals | ✓ | ✓ | ✓ | Very High |
| Ethical & responsible AI use | ✓ | ✓ | ✓ | Very High |
| Mini Project — AI Portfolio Website | — | ✓ | ✓ | Medium |
| HTML5 | ✓ | ✓ | ✓ | Very High |
| CSS3 | ✓ | ✓ | ✓ | Very High |
| Responsive Web Design | ✓ | ✓ | ✓ | Very High |
| Bootstrap | ✓ | ✓ | ✓ | Very High |
| JavaScript fundamentals | ✓ | ✓ | ✓ | High |
| DOM Manipulation | ✓ | ✓ | ✓ | Very High |
| Forms and Validation | ✓ | ✓ | ✓ | Very High |
| AI-assisted UI/UX design | ✓ | ✓ | ✓ | Medium |
| AI-generated responsive layouts | ✓ | ✓ | ✓ | Medium |
| Wireframing using AI tools | ✓ | ✓ | — | Medium |
| Website accessibility and optimization | ✓ | ✓ | ✓ | Medium |
| Mini Project — Event Management Website | — | ✓ | ✓ | Medium |

Every major syllabus topic has at least one question across the mark categories — no topic is left completely untouched.

---

# 🔁 ONE TOPIC → MULTIPLE MARKS

**Generative AI**
- → 2M: Define Generative AI
- → 7M: Explain Generative AI and how it works, with applications in web development
- → 11M: Explain Generative AI in detail — concept, working, and applications in software/web development

**Prompt Engineering**
- → 2M: Define Prompt Engineering
- → 7M: Explain the fundamental principles of a good prompt / any five techniques
- → 11M: Explain Prompt Engineering in detail — principles and all major techniques

**Role of AI in SDLC**
- → 2M: Name phases of SDLC where AI helps
- → 7M: Explain the role of LLMs and AI coding assistants across the SDLC
- → 11M: Discuss the role of LLMs/AI coding assistants across SDLC, with advantages and limitations

**Ethical Use of AI**
- → 2M: State any two ethical considerations
- → 7M: Discuss ethical considerations in using AI tools for software development
- → 11M: Discuss in detail the ethical and responsible use of AI in software development

**HTML5 Structure**
- → 2M: What does `<!DOCTYPE html>` declare? / Name semantic tags
- → 7M: Explain the structure of an HTML5 document with a diagram
- → 11M: Explain the HTML5 document structure in detail with diagram and code

**Responsive Web Design + Bootstrap**
- → 2M: Define RWD / state two benefits of Bootstrap
- → 7M: Explain RWD and the role/benefits of Bootstrap
- → 11M: Explain RWD and Bootstrap in detail — grid system, components, benefits

**DOM Manipulation**
- → 2M: Define DOM / differentiate `getElementById()` vs `querySelector()`
- → 7M: Explain DOM Manipulation with methods and example
- → 11M: Explain DOM Manipulation in detail with method table and worked example

**Form Validation**
- → 2M: Define Form Validation / differentiate client vs server-side
- → 7M: Explain client-side and server-side validation with code example
- → 11M: Explain Form Validation in detail — client vs server, HTML5 + custom JS

---

# 🎯 FINAL EXAM PRIORITY ORDER

1. Generative AI — concept, working, applications — **Very High Priority**
2. Prompt Engineering — principles + techniques — **Very High Priority**
3. Role of AI/LLMs across the SDLC — **Very High Priority**
4. HTML5 document structure & semantic tags — **Very High Priority**
5. CSS3 — Box Model, Flexbox/Grid, Media Queries — **Very High Priority**
6. DOM Manipulation — methods and examples — **Very High Priority**
7. Form Validation — client vs server, HTML5 + JS — **Very High Priority**
8. Ethical considerations in AI-assisted software development — **High Priority**
9. Responsive Web Design & Bootstrap — **High Priority**
10. Front-end / Back-end / Full-Stack development — **High Priority**
11. Advantages and limitations of AI coding assistants — **High Priority**
12. Combined Form Validation + DOM Manipulation flow and usability — **High Priority**
13. Evolution of web technologies (Web 1.0 → 3.0) — **Medium Priority**
14. AI-assisted UI/UX design, responsive layouts, wireframing — **Medium Priority**
15. Website accessibility and optimization — **Medium Priority**
16. Mini projects — AI Portfolio Website / Event Management Website — **Medium Priority**

*No question is guaranteed to appear exactly as listed — this order reflects concept importance and examination likelihood based on the syllabus and reference material, not a guarantee.*
