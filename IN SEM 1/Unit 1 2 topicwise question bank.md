# Unit 1 & 2 — Topic-Wise High-Priority Exam Question Bank
### Har topic ke andar 2M + 7M + 11M saath — priority order mein (sabse pehle = sabse zyada chance)

---

# 🔥 SECTION A — VERY HIGH PRIORITY TOPICS (padhna hi padhna)

## Topic 1: Generative AI

**[2 Marks]** Define Generative AI.
Generative AI is a class of AI systems that create new content — text, images, code, audio, or video — by learning patterns from large training datasets, rather than simply classifying or predicting from existing data.

**[7 Marks]** What is Generative AI? Explain how it works with a diagram, and its applications in web development.
### Answer Structure: Definition → Working (diagram) → Applications
### Exam-Ready Answer
**Definition:** as above.
**How it works:**
```
[Training Data] (text, code, images) --> [Generative AI Model] (learns patterns) --> [New Content] (Text/Code/Image/Audio/Video)
```
The model learns statistical patterns from massive training data, then generates new output consistent with those patterns when prompted.
**Applications in Web Development:**
- AI coding assistants (e.g., GitHub Copilot) generate HTML/CSS/JS snippets, complete functions, or suggest UI components from natural-language prompts
- Speeds up development by reducing boilerplate writing
- Generates layout ideas, sample content, test data

**[11 Marks]** Explain Generative AI in detail — concept, working, and applications in software/web development.
### Answer Structure: Concept → Working+diagram → Web dev applications → Broader SDLC applications → Conclusion
### Exam-Ready Answer
**Concept:** Same definition as above — key distinction from discriminative AI: Generative AI *creates* new content instead of only classifying/predicting.
**Working:** same diagram as above, explained: trained on massive datasets → internalizes structure/patterns → given a prompt, produces new output following those patterns.
**Applications in Web Development:** generating HTML/CSS/JS snippets, auto-generating responsive layouts and wireframes, generating placeholder content for prototypes.
**Applications in broader Software Development:** Requirement analysis (user stories), Design (architecture suggestions), Testing (test case generation), Documentation (README/API docs), Maintenance (refactoring, explaining legacy code).
**Conclusion:** Generative AI compresses the time from idea to working prototype across the SDLC, though output still needs human verification for correctness, security, and originality.

---

## Topic 2: Prompt Engineering

**[2 Marks]** Define Prompt Engineering.
Prompt Engineering is the practice of designing, structuring, and refining inputs (prompts) given to an LLM to obtain accurate, relevant, and useful outputs. It acts as the "interface language" between humans and AI.

**[7 Marks — version A]** Explain the fundamental principles of a good prompt with an example.
### Exam-Ready Answer
- **Clarity** — unambiguous, specific instructions
- **Context** — relevant background information
- **Constraints** — output format/length/tone rules
- **Examples** — sample input/output to guide the model
- **Role Assignment** — defining a persona (e.g., "Act as a senior Python developer")

**Worked example:** "Act as a senior front-end developer [Role]. I am building a college event registration page [Context]. Write a responsive registration form with name, email, event dropdown [Clarity]. Keep it under 40 lines, Bootstrap classes only [Constraints]. Here is a similar form I liked: [example] [Examples]."

**[7 Marks — version B]** Explain any five Prompt Engineering techniques with examples.
### Exam-Ready Answer
| Technique | Description | Example |
|---|---|---|
| Zero-Shot | Direct question, no examples | "Write a Python function to reverse a string." |
| Few-Shot | 2–3 examples before the task | Sample input-output pairs, then a new request |
| Chain-of-Thought (CoT) | Model reasons step-by-step | "Solve this step by step: ..." |
| Role Prompting | Assign a persona | "Act as a cybersecurity expert and review this code." |
| Instruction-based | Explicit format/output rules | "Return the answer only as JSON." |

**[11 Marks]** Explain Prompt Engineering in detail — definition, fundamental principles, and all major techniques with examples.
### Exam-Ready Answer
**Definition:** same as above — "interface language" between humans and AI.
**Principles:** Clarity, Context, Constraints, Examples, Role Assignment (as in 7M-A).
**All techniques (full table):**
| Technique | Description | Example |
|---|---|---|
| Zero-Shot | Direct question, no examples | "Write a Python function to reverse a string." |
| Few-Shot | 2–3 examples before the task | Sample input-output pairs |
| Chain-of-Thought (CoT) | Step-by-step reasoning | "Solve this step by step: ..." |
| Role Prompting | Assign a persona | "Act as a cybersecurity expert..." |
| Instruction-based | Explicit format rules | "Return only as JSON." |
| Iterative Refinement | Refine via follow-ups | "Make it more concise" |
| Self-Consistency | Multiple reasoning paths, pick most consistent | Complex math/logic problems |
| RAG | External knowledge injected into prompt | Injecting document context before query |
**Conclusion:** Mastering both principles and techniques directly determines how effectively you extract accurate, usable output from an LLM.

### 🔁 Quick-fire related 2-markers (same topic, different angle — likely direct short questions too)
- **Zero-Shot vs Few-Shot:** Zero-shot = direct question, no examples. Few-shot = 2–3 examples given first to guide style.
- **Chain-of-Thought (CoT):** asks the model to reason step-by-step rather than jump to an answer — improves accuracy on logical/complex tasks.
- **Role Prompting:** assigning a persona to the LLM to guide tone/expertise, e.g. "Act as a cybersecurity expert."
- **RAG (Retrieval-Augmented Generation):** combines external knowledge retrieval with the prompt so the model generates more grounded, accurate answers.

---

## Topic 3: Role of AI/LLMs in SDLC + AI Coding Assistants

**[2 Marks]** What is an AI coding assistant? Give two examples. / Define LLM with examples.
An AI coding assistant uses LLMs to help write, complete, test, or debug code via natural-language prompts (e.g., GitHub Copilot, Amazon Q). An LLM (e.g., GPT, Claude) is a Generative AI model trained on massive text data to understand/generate human-like language.

**[7 Marks — version A]** Explain the role of LLMs and AI coding assistants across the phases of SDLC.
### Exam-Ready Answer
| SDLC Phase | Role of AI/LLM | Example |
|---|---|---|
| Requirement Analysis | Clarify requirements, generate user stories | Client brief → structured user stories |
| Design | Suggest architecture patterns | Suggesting microservices for e-commerce app |
| Coding/Implementation | Auto-complete, generate boilerplate | Copilot generating a REST API controller |
| Testing | Generate unit test cases | Auto-generating Jest/PyTest tests |
| Debugging | Explain errors, suggest fixes | Root-cause analysis from a traceback |
| Documentation | Auto-generate docstrings/README | Generating Swagger/OpenAPI docs |
| Maintenance | Refactor legacy code | Modernizing jQuery code to React |

**[7 Marks — version B]** Discuss the advantages and limitations of AI coding assistants.
### Exam-Ready Answer
**Advantages:** reduces development time, lowers entry barrier for juniors, improves code quality via suggestions.
**Limitations:** may contain bugs/security flaws (SQLi, hardcoded secrets), may resemble licensed code (IP risk), can inherit bias, over-reliance risks skill erosion.
**Conclusion:** human review ("human-in-the-loop") remains essential.

**[11 Marks]** Discuss in detail the role of LLMs and AI coding assistants across the SDLC, including advantages and limitations.
### Exam-Ready Answer
Combine the full SDLC table (from 7M-A) + advantages/limitations (from 7M-B) into one full answer, with this diagram:
```
[Requirement Analysis] -> [Design] -> [Coding/Implementation] -> [Testing] -> [Debugging] -> [Documentation] -> [Maintenance]
```
**Conclusion:** AI assistance now touches every SDLC phase, but human review remains essential to ensure security, correctness, and originality.

---

## Topic 4: Ethical & Responsible AI Use

**[2 Marks]** State any two ethical considerations in using AI tools for software development.
(1) Code Ownership & IP Rights — AI-generated code may resemble copyrighted code. (2) Bias and Fairness — LLMs can inherit training-data bias, causing discriminatory logic.

**[7 Marks]** Discuss the ethical considerations involved in using AI tools for software development.
### Exam-Ready Answer
- **Code Ownership & IP Rights** — verify licensing before reuse
- **Bias and Fairness** — LLMs can inherit bias
- **Security Risks** — AI code may have vulnerabilities (SQLi, hardcoded secrets)
- **Over-Reliance & Skill Erosion** — reduces problem-solving skill over time
- **Data Privacy** — pasting sensitive data into public AI tools risks breaches
- **Accountability** — developers remain responsible ("human-in-the-loop")
- **Transparency** — disclose AI-assisted contributions

**[11 Marks]** Discuss in detail the ethical and responsible use of AI in software development.
### Exam-Ready Answer
Same 7 points as above, each with a one-line mitigation:
- IP Rights → verify licensing compliance
- Bias → review AI logic for fairness
- Security → mandatory code review/scanning
- Over-reliance → use AI to assist, not replace, learning
- Privacy → don't share proprietary data with public AI tools
- Accountability → human-in-the-loop at every stage
- Transparency → document what's AI-generated vs human-written
**Conclusion:** AI boosts productivity, but responsible use safeguards code quality, security, and professional integrity.

---

## Topic 5: HTML5 Document Structure

**[2 Marks]** What does `<!DOCTYPE html>` declare? / Name any four semantic tags and their purpose.
`<!DOCTYPE html>` declares the document as HTML5 so the browser renders it correctly. Semantic tags: `<header>` (title), `<nav>` (navigation), `<main>` (primary content), `<footer>` (contact/copyright) — improve accessibility and SEO over generic `<div>`s.

**[7 Marks]** Explain the structure of an HTML5 document with a diagram.
### Exam-Ready Answer
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
  <main><section>Main Content</section></main>
  <footer>Footer Content</footer>
</body>
</html>
```
```
<html>
 └─ <head>  → meta charset, title, linked stylesheet
 └─ <body>
     ├─ <header> ├─ <nav> ├─ <main><section> ├─ <footer>
```
Key elements: DOCTYPE declares HTML5; `<head>` = metadata, not visible; semantic tags improve accessibility/SEO; `<body>` = visible content.

**[11 Marks]** Explain the structure of an HTML5 document in detail, covering DOCTYPE, head, body, and semantic tags, with diagram and code.
### Exam-Ready Answer
Same code + diagram as 7M, PLUS detailed explanation of each element:
- `<!DOCTYPE html>` → standards-mode rendering
- `<html lang="en">` → `lang` attribute aids accessibility/SEO
- `<head>` → viewport meta tag essential for responsive design
- `<body>` → visible content
- Semantic tags improve **Accessibility** (screen readers), **SEO** (search engines understand hierarchy), **Maintainability** (easier to read/edit)
**Conclusion:** Good HTML5 structure directly supports accessibility, SEO, and maintainability.

---

## Topic 6: CSS3

**[2 Marks]** List any four ways CSS3 improves a webpage's appearance. / What are Media Queries?
Selectors & Styling, Flexbox & Grid (layouts), Animations & Transitions (`@keyframes`, `transition`), Media Queries (adapt style to screen size via `@media`).

**[7 Marks]** Explain how CSS3 improves the appearance of a webpage with an example.
### Exam-Ready Answer
- Selectors & Styling — colors/fonts/spacing
- Box Model Control — padding, border-radius, box-shadow
- Flexbox & Grid — modern layouts
- Animations & Transitions
- Media Queries — responsive breakpoints

```css
.card {
    display: flex; padding: 20px; border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
}
.card:hover { transform: scale(1.05); }
@media (max-width: 600px) { .card { flex-direction: column; } }
```

**[11 Marks]** Explain CSS3 in detail — selectors, box model, Flexbox/Grid, media queries, and animations — with code examples.
### Exam-Ready Answer
Same 5 capabilities as 7M, explained in more depth (Box Model = content→padding→border→margin nesting), same code example, plus:
**Why it matters:** CSS3 features together enable Responsive Web Design without relying on images/tables for layout.

---

## Topic 7: Responsive Web Design & Bootstrap

**[2 Marks]** Define RWD. / State two benefits of Bootstrap.
RWD ensures a website adapts its layout/images/content to different screen sizes using fluid grids, flexible images, and media queries. Bootstrap benefits: (1) pre-built 12-column grid reduces dev time, (2) ready-to-use cross-browser UI components.

**[7 Marks]** Explain Responsive Web Design and the role/benefits of Bootstrap.
### Exam-Ready Answer
RWD definition (as above) + Bootstrap's role: standardizes RWD into reusable classes (e.g., `col-md-6`) instead of hand-written media queries; provides 12-column grid + components (navbars, buttons, forms, modals).

**[11 Marks]** Explain Responsive Web Design and Bootstrap in detail — grid system, components, benefits, with code.
### Exam-Ready Answer
Same as 7M plus code example:
```html
<div class="row">
  <div class="col-md-6">Left Column</div>
  <div class="col-md-6">Right Column</div>
</div>
```
Benefits: reduces dev time, design consistency, cross-browser compatible, mobile-first by default.
**Conclusion:** Bootstrap operationalizes RWD principles into reusable classes.

---

## Topic 8: DOM Manipulation

**[2 Marks]** What is the DOM? / Differentiate `getElementById()` vs `querySelector()`.
DOM = tree-like representation of an HTML document that JS can access/modify dynamically without a full reload. `getElementById()` selects by unique ID only; `querySelector()` selects via any CSS selector (more flexible).

**[7 Marks]** Explain DOM Manipulation with common methods and an example.
### Exam-Ready Answer
| Method | Purpose |
|---|---|
| `getElementById()` | Select by ID |
| `querySelector()` | Select via CSS selector |
| `innerHTML` | Get/set HTML content |
| `classList.add/remove()` | Apply/remove CSS classes |
| `addEventListener()` | Attach event handlers |
| `createElement()` | Create new elements |

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

**[11 Marks]** Explain DOM Manipulation in detail — definition, key methods, and a working example.
### Exam-Ready Answer
Same definition + full method table + same example as 7M, plus:
**Real-world use cases:** live search, dynamic dropdowns, dashboards, real-time form feedback, SPA-like experiences.

---

## Topic 9: Form Validation

**[2 Marks]** Define Form Validation. / Differentiate Client-side vs Server-side validation.
Form Validation = checking user input correctness/completeness before submission. Client-side runs in browser (instant feedback, can be bypassed); Server-side runs on backend (cannot be bypassed, security-critical).

**[7 Marks]** Explain Client-side and Server-side Form Validation with a code example.
### Exam-Ready Answer
```html
<form id="regForm">
  <input type="email" required placeholder="Enter email">
  <input type="password" minlength="8" required placeholder="Password">
  <button type="submit">Register</button>
</form>
```
```javascript
document.getElementById("regForm").addEventListener("submit", function(e) {
  const email = document.querySelector("input[type=email]").value;
  const password = document.querySelector("input[type=password]").value;
  if (!email.includes("@")) { alert("Please enter a valid email address."); e.preventDefault(); }
  if (password.length < 8) { alert("Password must be at least 8 characters."); e.preventDefault(); }
});
```

**[11 Marks]** Explain Form Validation in detail — client vs server, HTML5 built-in validation, custom JS validation.
### Exam-Ready Answer
Same code + comparison table:
| Aspect | Client-side | Server-side |
|---|---|---|
| Where it runs | Browser | Backend |
| Feedback speed | Instant | After submission |
| Can be bypassed? | Yes | No |
| Purpose | UX | Security |
**Conclusion:** Server-side validation must always back up client-side checks since the latter can be disabled.

---

## Topic 10: Form Validation + DOM Manipulation — Combined Flow

**[7 Marks — version A]** Explain the combined flow of Form Validation + DOM Manipulation with a diagram.
```
User types --> 'input'/'submit' event --> JS reads value (getElementById/querySelector) --> Validation check
                                                                    |
                                              ┌─────────────────────┴─────────────────────┐
                                              ▼                                             ▼
                                    Valid: submit form data                    Invalid: DOM update
                                                                    (classList.add('input-error'), createElement()+textContent)
```

**[7 Marks — version B]** Discuss the combined impact of Form Validation + DOM Manipulation on usability.
| Aspect | Contribution |
|---|---|
| Real-time Feedback | No page reload needed |
| Reduced Frustration | Errors caught early |
| Dynamic UI Updates | Live search, modals, dashboards |
| Accessibility | classList highlights error fields |
| Performance | Avoids full-page reloads (SPA-like) |

**[11 Marks]** Explain the combined flow with diagram, and discuss its usability impact.
### Exam-Ready Answer
Combine both 7M versions above into one answer (flow diagram + usability table).
**Conclusion:** Form validation ensures data integrity; DOM manipulation enables dynamic interfaces — together they're the backbone of modern user-friendly web apps.

---

# ⭐ SECTION B — HIGH PRIORITY TOPICS

## Topic 11: Front-end / Back-end / Full-Stack Development

**[2 Marks]** Differentiate Front-end vs Back-end. / Define Full Stack development.
Front-end = client-side, user-facing (HTML/CSS/JS). Back-end = server-side logic/database/APIs. Full Stack = working on both.

**[7 Marks]** Explain Front-end, Back-end, and Full-Stack development with examples.
### Exam-Ready Answer
Front-end: HTML/CSS/JS/React/Bootstrap — layout, styling, UX.
Back-end: Node.js/Python/Java, databases, APIs — business logic, data storage.
Full Stack: builds both. Example: e-commerce site — front-end shows catalog/cart UI, back-end manages DB/payments; a Full Stack dev builds and connects both.

**[11 Marks]** Explain Front-end, Back-end, and Full-Stack development in detail, along with how Generative AI assists each.
### Exam-Ready Answer
Same three definitions as 7M, PLUS AI's role in each:
- Front-end: AI generates HTML/CSS/JS snippets, responsive layouts, wireframes
- Back-end: AI generates REST API boilerplate, DB schema suggestions, server-side validation logic
- Full Stack: AI assists across the whole stack simultaneously, keeping front-end/back-end consistent
**Example:** College event site — AI-assisted responsive front-end form + AI-assisted back-end API to store registrations.

---

## Topic 12: Evolution of Web Technologies

**[2 Marks]** Briefly describe the evolution of web technologies (Web 1.0 → 3.0).
Web 1.0 = static, read-only. Web 2.0 = interactive, user-generated content. Web 3.0 = AI-driven, personalized, semantic web.

**[7 Marks]** Explain the evolution of web technologies from Web 1.0 to Web 3.0.
### Exam-Ready Answer
| Aspect | Web 1.0 | Web 2.0 | Web 3.0 |
|---|---|---|---|
| Nature | Static | Interactive | Intelligent/AI-driven |
| User role | Reader | Contributor | Co-creator with AI |
| Example | Basic HTML sites | Facebook, Wikipedia | AI copilots, personalized apps |

**[11 Marks]** Discuss the evolution of web technologies and the impact of Generative AI on modern web development.
### Exam-Ready Answer
Same table as 7M, PLUS: Generative AI accelerates Web 3.0-style development — auto-generating front-end code, personalized layouts, dynamic content — shifting the developer's role from writing every line to prompting/reviewing/refining AI output.

---

## Topic 13: AI-Assisted UI/UX Design, Responsive Layouts & Wireframing

**[2 Marks]** What is meant by AI-assisted UI/UX design and wireframing using AI tools?
Using AI tools to generate layout ideas, color schemes, component suggestions, or full wireframes/mockups from natural-language prompts, speeding up the design phase.

**[7 Marks]** Explain how AI tools assist in UI/UX design and generating responsive layouts. / Explain wireframing using AI tools.
### Exam-Ready Answer
- Generates layout/color options from a prompt
- Auto-generates responsive HTML/CSS with media queries built in
- Converts a text description directly into a wireframe/HTML skeleton
- Speeds up idea → working prototype, though human review is still needed

**[11 Marks]** Discuss AI-assisted UI/UX design, AI-generated responsive layouts, and wireframing using AI tools in detail.
### Exam-Ready Answer
Same points as 7M, expanded, plus workflow diagram:
```
Text prompt --> AI-generated wireframe --> AI-generated responsive HTML/CSS --> Human review & refinement
```
**Conclusion:** Compresses idea-to-prototype time, but human review remains essential for usability, branding, accessibility.

---

## Topic 14: Website Accessibility & Optimization

**[2 Marks]** What is meant by website accessibility and optimization?
Accessibility = designing so people with disabilities can use the site (semantic tags, alt text, contrast, keyboard navigation). Optimization = improving load speed/performance.

**[7 Marks]** Explain website accessibility and optimization techniques in web design.
### Exam-Ready Answer
**Accessibility:** semantic HTML, alt text, color contrast, keyboard navigability, ARIA labels.
**Optimization:** compress/lazy-load images, minify CSS/JS, responsive images (`srcset`), reduce DOM reflows, caching.

**[11 Marks]** Explain website accessibility and optimization in detail, with best practices.
### Exam-Ready Answer
Same points as 7M, expanded with more best practices each, PLUS:
**Why it matters:** Accessibility = legal compliance + inclusivity; Optimization = user retention + SEO ranking.

---

# ○ SECTION C — MEDIUM PRIORITY (if time permits)

## Topic 15: Mini Projects

**[7 Marks]** Describe the approach to building the AI-generated Personal Portfolio Website mini project.
Planning sections → prompting (role+context+constraints) → AI generation → review/customization (human-in-the-loop) → responsiveness testing → deployment (GitHub Pages) → disclose AI assistance.

**[11 Marks]** Explain the end-to-end process of the Portfolio Website mini project, highlighting ethical/quality considerations.
Same steps as 7M in more detail, PLUS explicit ethics checks: no copied code/design reused without attribution, no sensitive data pasted into public AI tools, disclose AI assistance, human-in-the-loop before treating output as final.

**[7 Marks]** Describe the approach to building the College Event Management Website mini project.
Requirement gathering → AI-assisted wireframing → front-end build (semantic HTML5 + Bootstrap grid + CSS3) → form validation + DOM manipulation for live feedback → responsiveness testing.

**[11 Marks]** Describe in detail the approach to the Event Management Website mini project with responsive interface via AI tools.
Same steps as 7M, expanded, PLUS review/ethical checks (verify AI code for bugs/security, check accessibility, confirm no unlicensed assets used).

---

# 🎯 FINAL PRIORITY ORDER (topic-wise, sabse pehle padho)

1. Generative AI — **Very High**
2. Prompt Engineering — **Very High**
3. Role of AI/LLMs in SDLC + AI coding assistants — **Very High**
4. HTML5 Document Structure — **Very High**
5. CSS3 — **Very High**
6. Responsive Web Design & Bootstrap — **Very High**
7. DOM Manipulation — **Very High**
8. Form Validation — **Very High**
9. Ethical & Responsible AI Use — **Very High**
10. Form Validation + DOM Manipulation combined flow — **High**
11. Front-end / Back-end / Full-Stack Development — **High**
12. Evolution of Web Technologies — **Medium**
13. AI-assisted UI/UX design, responsive layouts, wireframing — **Medium**
14. Website Accessibility & Optimization — **Medium**
15. Mini Projects (Portfolio Website / Event Management Website) — **Medium**

*Guaranteed nahi hai koi bhi question exactly aise aayega — ye priority order syllabus + reference notes ke hisaab se hai.*
