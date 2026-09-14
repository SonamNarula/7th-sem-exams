# Web Development Using AI
## Unit 1 + Unit 2 — Complete 7-Mark Question Bank

> **Note on scope:** This question bank is built from the official syllabus topics only. No previous-year papers, teacher notes/PPTs, class tests, or assignment sheets were provided, so no PYQ-frequency claims are made anywhere in this document. Priority tags (🔥/⭐/○) reflect how central a topic is to the syllabus and how naturally it forms a 7-mark examiner question — not actual past-paper frequency.

---

# UNIT 1 — INTRODUCTION TO WEB DEVELOPMENT AND GENERATIVE AI

---

## Q1. Evolution of Web Technologies

### Question
**Explain the evolution of web technologies from Web 1.0 to Web 3.0. [7 Marks]**

*Possible examiner variations:*
- Discuss the evolution of the World Wide Web with suitable examples.
- Differentiate between Web 1.0, Web 2.0, and Web 3.0.
- Trace the journey of web technologies highlighting key characteristics of each phase.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction — what "evolution of web" means
2. Web 1.0 — definition, characteristics, examples
3. Web 2.0 — definition, characteristics, examples
4. Web 3.0 — definition, characteristics, examples
5. Comparison table
6. Conclusion — significance of this evolution for modern development

### Exam-Ready Answer

**Introduction**
The World Wide Web has evolved through three broad phases — Web 1.0, Web 2.0, and Web 3.0 — each reflecting changes in how content is created, shared, and consumed, and each requiring new web development skills.

**Web 1.0 (Static Web, ~1991–2004)**
- Read-only, static HTML pages with no interactivity.
- Content authored by a small number of publishers; users were passive consumers.
- No user accounts, comments, or personalization.
- **Example:** early company brochure websites, static HTML pages.

**Web 2.0 (Social/Interactive Web, ~2004–present)**
- Read-write web enabling two-way communication.
- User-generated content, social media, blogs, wikis.
- Uses AJAX, JavaScript frameworks for dynamic, interactive pages.
- **Example:** Facebook, YouTube, Wikipedia.

**Web 3.0 (Semantic/Intelligent Web, emerging)**
- Focuses on decentralization, machine-understandable data, and AI-driven personalization.
- Associated with blockchain, semantic web, and intelligent agents.
- **Example:** decentralized applications (dApps), AI-personalized search/recommendations.

**Comparison Table**

| Feature | Web 1.0 | Web 2.0 | Web 3.0 |
|---|---|---|---|
| Nature | Read-only | Read-write | Read-write-execute |
| Content | Static | User-generated | AI/semantic-driven |
| Interaction | None | High | Personalized/intelligent |
| Technology | Basic HTML | AJAX, JS frameworks | AI, blockchain, semantic web |
| Example | Static brochure sites | Facebook, YouTube | dApps, AI assistants |

**Conclusion**
This evolution shows a consistent trend toward greater interactivity, user participation, and intelligence — directly motivating why modern web developers must now also understand AI-assisted tools and techniques, which form the core theme of this course.

---

## Q2. Front-end, Back-end and Full Stack Development

### Question
**Explain Front-end, Back-end, and Full Stack development. Differentiate between them with examples. [7 Marks]**

*Possible examiner variations:*
- What is full stack development? Explain its components.
- Differentiate between client-side and server-side development with suitable technologies.
- Describe the roles and responsibilities of a front-end, back-end, and full stack developer.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction
2. Front-end development — definition, technologies, responsibilities
3. Back-end development — definition, technologies, responsibilities
4. Full stack development — definition, example stack (MERN)
5. Comparison table
6. Conclusion

### Exam-Ready Answer

**Introduction**
Modern web applications are built in layers — the part users see and interact with, and the part that manages data and logic behind the scenes. These layers are handled by front-end, back-end, and full stack developers respectively.

**Front-end Development**
- Also called **client-side development**; concerned with the visual, interactive part of a website.
- Runs in the user's browser.
- **Core technologies:** HTML (structure), CSS (styling), JavaScript (interactivity).
- **Frameworks:** React.js, Angular, Vue.js.
- **Responsibilities:** layout, responsiveness, UI/UX, form handling on the client side.

**Back-end Development**
- Also called **server-side development**; concerned with data, logic, and server operations.
- Runs on the server, invisible to the end user.
- **Core technologies:** Node.js, Python (Django/Flask), PHP, Java.
- **Databases:** MySQL, MongoDB.
- **Responsibilities:** business logic, authentication, database management, APIs.

**Full Stack Development**
- Involves working on **both** front-end and back-end.
- A full stack developer can independently design and build an entire application.
- **Example stack — MERN:** MongoDB (database), Express.js (back-end framework), React.js (front-end), Node.js (server runtime).

**Comparison Table**

| Aspect | Front-end | Back-end | Full Stack |
|---|---|---|---|
| Location | Client (browser) | Server | Both |
| Visibility | Visible to user | Hidden | Both |
| Technologies | HTML, CSS, JS, React | Node.js, PHP, DB | Combination (e.g., MERN) |
| Focus | UI/UX | Logic, data | End-to-end application |

**Conclusion**
While front-end and back-end developers specialize in one layer, full stack developers combine both skill sets, offering flexibility and end-to-end ownership of a project — a highly valued skill in today's industry.

---

## Q3. Artificial Intelligence and Generative AI

### Question
**Explain Artificial Intelligence and Generative AI. Discuss how Generative AI differs from traditional AI approaches. [7 Marks]**

*Possible examiner variations:*
- What is Generative AI? Explain its working principle with examples.
- Discuss the relationship between AI, Machine Learning, Deep Learning, and Generative AI.
- Explain Generative AI and its applications in software/web development.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction to AI
2. AI, ML, DL relationship (with diagram)
3. Generative AI — definition and working
4. Difference: Generative vs Discriminative (traditional) AI
5. Applications of Generative AI
6. Conclusion

### Exam-Ready Answer

**Introduction**
Artificial Intelligence (AI) is the branch of computer science focused on building systems that simulate human intelligence — reasoning, learning, and decision-making. Generative AI is a specialized, rapidly growing branch of AI that focuses on *creating* new content rather than simply analyzing existing data.

**AI → ML → DL → Generative AI (Relationship)**

```
Artificial Intelligence (broadest field)
   └── Machine Learning (learns patterns from data)
         └── Deep Learning (neural networks, large data)
               └── Generative AI (creates new content)
```

- **Machine Learning:** systems learn from data without explicit rule-based programming.
- **Deep Learning:** uses multi-layered neural networks to model complex patterns.
- **Generative AI:** built on deep learning (often transformer architectures) to *generate* new text, images, audio, or code.

**What is Generative AI?**
Generative AI refers to AI models trained on large datasets that learn the underlying patterns/distribution of that data, and can then generate new, original content resembling it — e.g., ChatGPT (text), DALL·E (images), GitHub Copilot (code).

**Generative vs Traditional (Discriminative) AI**

| Traditional/Discriminative AI | Generative AI |
|---|---|
| Classifies or predicts labels from input | Creates new content/output |
| Learns a decision boundary between classes | Learns the full data distribution |
| Example: spam vs. not-spam classifier | Example: text/image/code generator |
| Output: a label or number | Output: new text, image, audio, or code |

**Applications of Generative AI**
- Text generation and summarization (ChatGPT).
- Code generation and completion (GitHub Copilot).
- Image/design generation (DALL·E, Midjourney).
- Automated content creation for websites and portfolios.

**Conclusion**
Generative AI represents a paradigm shift from AI that merely *analyzes* data to AI that *creates*, making it foundational to AI-assisted software and web development, which this course builds upon.

---

## Q4. Large Language Models (LLMs)

### Question
**What are Large Language Models (LLMs)? Explain their architecture and role in AI-assisted software development. [7 Marks]**

*Possible examiner variations:*
- Explain the working of LLMs with a suitable diagram.
- Discuss the applications of LLMs in web/software development.
- What is transformer architecture? Explain its importance in LLMs.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction/definition
2. Working principle (training + transformer architecture)
3. Key concepts: tokens, attention mechanism
4. Examples of LLMs
5. Role/applications in software development
6. Limitations
7. Conclusion

### Exam-Ready Answer

**Introduction**
A **Large Language Model (LLM)** is a deep learning model trained on massive amounts of text data to understand, generate, and manipulate human language. LLMs form the backbone of modern Generative AI tools used in software development.

**Working Principle**
- LLMs are trained on huge text corpora (books, code, websites) using **transformer architecture**.
- Text is broken into small units called **tokens** (words or sub-words).
- The **attention mechanism** allows the model to weigh the relevance of different tokens in a sequence, capturing context and relationships regardless of their position.
- During generation, the model predicts the most probable next token based on all previous tokens, repeating this process to form coherent output.

**Simplified Flow**

```
Input Text → Tokenization → Transformer Layers (Attention) → Probability Distribution → Next Token Prediction → Output Text
```

**Examples of LLMs**
GPT (OpenAI), Claude (Anthropic), Gemini (Google), LLaMA (Meta).

**Role in AI-Assisted Software Development**
- **Code generation and completion** — e.g., GitHub Copilot suggesting code as developers type.
- **Debugging assistance** — explaining errors and suggesting fixes.
- **Documentation writing** — auto-generating comments and README files.
- **Natural language interfaces** — allowing developers to describe requirements in plain English and receive code.

**Limitations**
- Can produce **hallucinations** (plausible but incorrect information).
- Requires human verification for correctness and security.
- Limited by training data cutoff and lack of true understanding.

**Conclusion**
LLMs have transformed software development by enabling natural-language-driven coding assistance, but they must be used alongside careful human review to ensure accuracy and reliability.

---

## Q5. AI-assisted Software Development Lifecycle (SDLC)

### Question
**Explain the AI-assisted Software Development Life Cycle. Describe how AI can be integrated into different phases of SDLC. [7 Marks]**

*Possible examiner variations:*
- Describe how AI can be integrated into different phases of SDLC.
- Explain the role of AI in the software development lifecycle with suitable examples.
- Discuss the benefits and limitations of AI-assisted SDLC.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction to SDLC
2. Traditional SDLC phases (diagram)
3. AI integration at each phase
4. Benefits
5. Limitations
6. Conclusion

### Exam-Ready Answer

**Introduction**
The **Software Development Life Cycle (SDLC)** is a structured process for building software, consisting of sequential phases. **AI-assisted SDLC** refers to embedding AI tools within these phases to increase speed, accuracy, and efficiency.

**Traditional SDLC Phases**

```
Requirement Analysis → Design → Implementation/Coding → Testing → Deployment → Maintenance
```

**AI Integration at Each Phase**

| SDLC Phase | Role of AI |
|---|---|
| Requirement Analysis | AI tools analyze documents/stakeholder input to extract and summarize requirements |
| Design | AI generates UI/UX wireframes, layout suggestions, and architecture diagrams |
| Implementation/Coding | AI coding assistants (e.g., GitHub Copilot) auto-generate/complete code |
| Testing | AI generates test cases, detects bugs, and predicts failure-prone modules |
| Deployment | AI assists in configuration, monitoring, and automated deployment pipelines |
| Maintenance | AI detects anomalies, suggests bug fixes, and automates routine updates |

**Benefits of AI-Assisted SDLC**
- Faster development through automated code generation.
- Reduced human error via automated testing and review.
- Improved documentation and requirement clarity.
- Lower cost and shorter time-to-market.

**Limitations**
- AI-generated code/tests may contain errors requiring human validation.
- Over-reliance on AI can reduce developers' deep understanding of code.
- Data privacy and security concerns when using AI tools on proprietary code.

**Conclusion**
AI-assisted SDLC does not replace traditional development phases but **augments** each of them with automation and intelligence, making the overall process faster and more efficient — provided human oversight is maintained at every stage.

---

## Q6. AI Coding Assistants

### Question
**What are AI Coding Assistants? Explain their features, benefits, and limitations with examples. [7 Marks]**

*Possible examiner variations:*
- Discuss the role of AI coding assistants in modern software development.
- Explain any two AI coding assistant tools with their key features.
- What are the advantages and limitations of using AI in coding?

### ⭐ Priority
⭐ Important

### Answer Structure
1. Introduction/definition
2. Key features
3. Example tools with brief description
4. Benefits
5. Limitations
6. Conclusion

### Exam-Ready Answer

**Introduction**
**AI Coding Assistants** are tools powered by Large Language Models that help developers write, complete, debug, and optimize code through intelligent, context-aware suggestions.

**Key Features**
- **Code completion** — suggests the rest of a line/function as the developer types.
- **Natural language to code** — converts plain-English descriptions into working code.
- **Bug detection and fixing** — identifies errors and proposes corrections.
- **Documentation generation** — auto-writes comments and docstrings.
- **Code explanation** — explains unfamiliar or legacy code.

**Example Tools**

| Tool | Description |
|---|---|
| GitHub Copilot | AI pair-programmer integrated into code editors, suggests code in real time |
| Claude / ChatGPT | Conversational AI that generates, explains, and debugs code |
| Amazon CodeWhisperer | AI code suggestion tool integrated with AWS services |

**Benefits**
- Increases development speed and productivity.
- Reduces syntax errors and repetitive coding tasks.
- Helps beginners learn faster through instant explanations.
- Provides instant documentation and examples.

**Limitations**
- May generate **incorrect, inefficient, or insecure** code.
- Lacks full understanding of overall project context.
- Can lead to over-dependence, weakening a developer's own problem-solving skills.
- Raises concerns about code originality/licensing.

**Conclusion**
AI coding assistants significantly boost developer productivity, but their output must always be **reviewed and validated by a human developer** before being deployed in production systems.

---

## Q7. Prompt Engineering Fundamentals

### Question
**What is Prompt Engineering? Explain its key techniques with examples. [7 Marks]**

*Possible examiner variations:*
- Discuss different prompting techniques used in Generative AI with examples.
- Explain the characteristics of a well-designed prompt.
- What is zero-shot and few-shot prompting? Explain with examples.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction/definition
2. Elements of a good prompt
3. Prompting techniques (with examples)
4. Importance of prompt engineering
5. Conclusion

### Exam-Ready Answer

**Introduction**
**Prompt Engineering** is the practice of designing, structuring, and refining input instructions ("prompts") given to an AI model in order to obtain accurate, relevant, and useful outputs.

**Elements of a Good Prompt**
- **Clarity** — unambiguous instructions.
- **Context** — background information relevant to the task.
- **Specificity** — clearly defined output format/constraints.
- **Examples** (where useful) — sample input/output pairs to guide the model.

**Key Prompting Techniques**

| Technique | Description | Example |
|---|---|---|
| Zero-shot prompting | Asking the AI to perform a task with no examples given | "Translate this sentence to French." |
| Few-shot prompting | Giving a few examples within the prompt to guide output | Showing 2–3 sample Q&A pairs before the actual question |
| Chain-of-thought prompting | Asking the AI to reason step-by-step before answering | "Solve this step by step: ..." |
| Role-based prompting | Assigning the AI a role/persona to shape its response style | "Act as a senior web developer and review this code." |

**Importance of Prompt Engineering**
- Well-designed prompts drastically improve output accuracy and reduce repeated corrections.
- Essential for effectively using AI coding assistants, chatbots, and content-generation tools.
- Reduces ambiguity, minimizing the chances of AI hallucination or irrelevant output.

**Conclusion**
As Generative AI tools become integral to software and web development, prompt engineering has emerged as a critical skill — the quality of AI output is directly dependent on the quality of the prompt provided.

---

## Q8. Ethical and Responsible Use of AI in Software Development

### Question
**Discuss the ethical concerns and responsible practices related to the use of AI in software development. [7 Marks]**

*Possible examiner variations:*
- What are the key ethical issues in using Generative AI for coding?
- Explain the concept of AI bias and data privacy with examples.
- Discuss guidelines for responsible use of AI-assisted tools in development.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction
2. Key ethical concerns (each explained)
3. Responsible AI practices/guidelines
4. Importance of human oversight
5. Conclusion

### Exam-Ready Answer

**Introduction**
As AI tools become deeply embedded in software development, it is essential to use them **ethically and responsibly** to avoid harm, bias, and misuse, while ensuring transparency and accountability.

**Key Ethical Concerns**

- **AI Bias** — AI models can produce unfair or skewed outputs if trained on imbalanced or prejudiced data (e.g., biased hiring-recommendation code).
- **Data Privacy** — AI tools may process sensitive user or proprietary code data, risking unauthorized exposure.
- **Intellectual Property/Plagiarism** — AI-generated code may unintentionally resemble copyrighted code from training data.
- **AI Hallucination** — AI can confidently generate false or fabricated information, misleading developers if unverified.
- **Over-reliance** — Excessive dependence on AI can erode developers' fundamental coding and problem-solving skills.
- **Accountability** — Unclear responsibility when AI-generated code causes bugs, security flaws, or failures.

**Responsible AI Practices**
- Always **review and test** AI-generated code before deployment.
- Ensure **transparency** — disclose where AI tools were used.
- Protect **sensitive data** — avoid feeding confidential information into public AI tools.
- Regularly check outputs for **bias and fairness**.
- Maintain **human oversight** as the final decision-maker.

**Conclusion**
Ethical and responsible AI use ensures that the benefits of AI-assisted development — speed, efficiency, and innovation — do not come at the cost of fairness, privacy, security, or accountability.

---

## Q9. Mini Project — AI-generated Personal Portfolio Website

### Question
**Explain the process of developing a Personal Portfolio Website using AI-assisted tools. [7 Marks]**

*Possible examiner variations:*
- Describe the steps involved in creating an AI-generated portfolio website.
- Discuss how AI tools can be used at each stage of building a portfolio website.

### ⭐ Priority
⭐ Important

### Answer Structure
1. Introduction/objective
2. Sections of a portfolio website
3. Step-by-step AI-assisted development process
4. Tools used at each step
5. Conclusion

### Exam-Ready Answer

**Introduction**
This mini project involves designing and building a **Personal Portfolio Website** using AI tools to assist with content, design, and code generation, applying the concepts learnt in Unit 1.

**Typical Sections of a Portfolio Website**
- Home/About Me
- Skills
- Projects
- Contact/Resume

**Step-by-Step AI-Assisted Development Process**

| Step | Description | Example AI Tool |
|---|---|---|
| 1. Content generation | Draft "About Me", skill descriptions, project summaries using AI | ChatGPT |
| 2. Layout/design | Generate wireframe and layout suggestions | Figma AI, Uizard |
| 3. Code generation | Generate HTML/CSS/JS structure from prompts | GitHub Copilot, ChatGPT |
| 4. Responsive design | AI suggests media queries and responsive components | AI coding assistant |
| 5. Review and refine | Manually test, debug, and personalize AI-generated output | Developer review |

**Conclusion**
This mini project demonstrates practical application of AI-assisted development — from content and design generation to code writing — reflecting how AI accelerates the modern web development workflow while still requiring human review and refinement.

---

# UNIT 2 — AI-ASSISTED FRONT-END DEVELOPMENT

---

## Q10. HTML5 — Features and New Elements

### Question
**Explain the new features introduced in HTML5 with suitable examples. [7 Marks]**

*Possible examiner variations:*
- Discuss the semantic elements introduced in HTML5.
- How does HTML5 differ from HTML4? Explain with examples.
- Explain multimedia support in HTML5.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction
2. New semantic elements
3. Multimedia support
4. New form input types
5. Canvas and SVG
6. HTML5 vs HTML4 table
7. Conclusion

### Exam-Ready Answer

**Introduction**
**HTML5** is the fifth and current major version of Hypertext Markup Language, introducing semantic structure, native multimedia support, and improved form handling compared to earlier versions.

**New Semantic Elements**
HTML5 introduced tags that describe the *meaning* of content, improving readability, SEO, and accessibility:
- `<header>`, `<footer>`, `<nav>`, `<article>`, `<section>`, `<aside>`.

**Native Multimedia Support**
- `<video>` and `<audio>` tags allow embedding media directly without third-party plugins (like Flash).

**New Form Input Types**
- `email`, `date`, `number`, `range`, `url`, `tel` — enabling built-in validation and better mobile keyboards.

**Canvas and SVG**
- `<canvas>` allows drawing graphics/animations dynamically via JavaScript.
- SVG support allows scalable vector graphics for crisp, resizable images.

**HTML5 vs HTML4**

| Feature | HTML4 | HTML5 |
|---|---|---|
| Semantic tags | Not available | Available (`<header>`, `<article>`, etc.) |
| Multimedia | Requires plugins | Native `<video>`/`<audio>` |
| Graphics | Not supported | `<canvas>`, SVG supported |
| Form inputs | Basic types only | New types (email, date, etc.) |
| Offline support | No | Local storage / offline APIs |

**Conclusion**
HTML5's semantic structure, multimedia support, and enhanced forms make it far more powerful and developer-friendly, forming the structural foundation for AI-assisted responsive web design covered later in this unit.

---

## Q11. CSS3 — Box Model, Flexbox, and Grid

### Question
**Explain the CSS Box Model. Discuss Flexbox and Grid layout systems in CSS3 with examples. [7 Marks]**

*Possible examiner variations:*
- Explain CSS3 layout techniques: Flexbox and Grid.
- Describe the CSS Box Model with a diagram.
- Differentiate between Flexbox and CSS Grid.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction to CSS3
2. Box Model (diagram + explanation)
3. Flexbox — explanation and use case
4. Grid — explanation and use case
5. Comparison table
6. Conclusion

### Exam-Ready Answer

**Introduction**
**CSS3** is the latest version of Cascading Style Sheets, introducing powerful layout systems such as **Flexbox** and **Grid**, along with the foundational **Box Model** that governs how every element is sized and spaced.

**CSS Box Model**
Every HTML element is treated as a rectangular box composed of four layers, from inside out:

```
 ┌─────────────── Margin ───────────────┐
 │ ┌──────────── Border ─────────────┐  │
 │ │ ┌────────── Padding ─────────┐  │  │
 │ │ │        Content              │  │  │
 │ │ └─────────────────────────────┘  │  │
 │ └───────────────────────────────────┘  │
 └─────────────────────────────────────────┘
```
- **Content:** actual text/image inside the element.
- **Padding:** space between content and border.
- **Border:** edge surrounding the padding.
- **Margin:** space outside the border, separating it from other elements.

**Flexbox**
- A **one-dimensional** layout model for arranging items in a row or column.
- Items can be aligned, spaced, and reordered flexibly regardless of size.
- **Use case:** navigation bars, aligning items within a single row/column.

**CSS Grid**
- A **two-dimensional** layout model allowing simultaneous control over rows and columns.
- Ideal for complex page layouts.
- **Use case:** full page layouts with header, sidebar, content, and footer.

**Flexbox vs Grid**

| Feature | Flexbox | Grid |
|---|---|---|
| Dimension | One-dimensional | Two-dimensional |
| Best for | Rows OR columns | Rows AND columns together |
| Use case | Navbars, toolbars | Full page layouts |

**Conclusion**
The Box Model governs individual element spacing, while Flexbox and Grid provide modern, flexible ways to arrange multiple elements — together forming the foundation of responsive CSS3 layouts.

---

## Q12. Responsive Web Design

### Question
**Explain Responsive Web Design. Discuss the techniques used to achieve responsiveness with examples. [7 Marks]**

*Possible examiner variations:*
- What is Responsive Web Design? Explain the role of media queries.
- Discuss the mobile-first approach in responsive design.
- Explain the key principles used to design responsive websites.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction/definition
2. Need for responsive design
3. Key techniques (media queries, fluid grids, flexible images, viewport)
4. Mobile-first approach
5. Example
6. Conclusion

### Exam-Ready Answer

**Introduction**
**Responsive Web Design (RWD)** is an approach to web design that makes web pages render well across a variety of devices and screen sizes — from mobile phones to large desktop monitors — by using flexible layouts and adaptive styling.

**Need for Responsive Design**
With the wide variety of devices in use today, a website designed for only one screen size would look broken or be unusable on others, harming user experience and SEO ranking.

**Key Techniques**

- **Fluid Grid Layout:** using relative units (%, `fr`, `em`) instead of fixed pixels so layout elements resize proportionally.
- **Flexible Images/Media:** using `max-width: 100%` so images scale within their container.
- **Media Queries:** CSS rules that apply different styles based on device characteristics such as width:
  ```css
  @media (max-width: 768px) {
    .container { flex-direction: column; }
  }
  ```
- **Viewport Meta Tag:** controls page scaling on mobile browsers:
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```

**Mobile-First Approach**
Design is first built for the smallest screen and then progressively enhanced with media queries for larger screens — improving performance and ensuring core usability on mobile devices.

**Example**
A three-column layout on desktop can collapse into a single column on mobile using a media query and Flexbox's `flex-direction: column`.

**Conclusion**
Responsive Web Design combines fluid grids, flexible media, and media queries to ensure a consistent, usable experience across devices — a core requirement for any modern website, including AI-generated layouts covered later in this unit.

---

## Q13. Bootstrap Framework

### Question
**What is Bootstrap? Explain its grid system and key components with examples. [7 Marks]**

*Possible examiner variations:*
- Explain the Bootstrap 12-column grid system with an example.
- Discuss the advantages of using Bootstrap for responsive web design.
- Describe any four Bootstrap components with their use.

### ⭐ Priority
⭐ Important

### Answer Structure
1. Introduction/definition
2. Grid system explanation
3. Key components
4. Advantages
5. Conclusion

### Exam-Ready Answer

**Introduction**
**Bootstrap** is a free, open-source front-end framework that provides pre-built CSS and JavaScript components to help developers build responsive, mobile-first websites quickly and consistently.

**Bootstrap Grid System**
- Based on a **12-column** responsive layout using `container`, `row`, and `col` classes.
- Columns automatically adjust width based on screen size using breakpoint classes (`col-sm`, `col-md`, `col-lg`, etc.).

```html
<div class="container">
  <div class="row">
    <div class="col-md-6">Column 1</div>
    <div class="col-md-6">Column 2</div>
  </div>
</div>
```

**Key Bootstrap Components**

| Component | Purpose |
|---|---|
| Navbar | Responsive navigation bar |
| Card | Flexible content container (image + text + actions) |
| Modal | Pop-up dialog box |
| Carousel | Image/content slideshow |
| Buttons | Pre-styled, responsive button classes |

**Advantages of Bootstrap**
- Speeds up development with ready-made responsive components.
- Ensures cross-browser compatibility.
- Provides a consistent, professional design out-of-the-box.
- Mobile-first by default.

**Conclusion**
Bootstrap significantly reduces development time by providing a tested, responsive component library, making it a preferred choice for building consistent, mobile-friendly websites quickly.

---

## Q14. JavaScript Fundamentals

### Question
**Explain the fundamental concepts of JavaScript with suitable examples. [7 Marks]**

*Possible examiner variations:*
- Discuss variables, data types, and functions in JavaScript.
- Explain the difference between var, let, and const with examples.
- Describe how JavaScript adds interactivity to web pages.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction
2. Variables and data types
3. Operators
4. Functions
5. Events
6. Example code
7. Conclusion

### Exam-Ready Answer

**Introduction**
**JavaScript** is a lightweight, interpreted, client-side scripting language used to add interactivity, logic, and dynamic behavior to web pages, complementing HTML (structure) and CSS (styling).

**Variables and Data Types**
- Declared using `var`, `let`, or `const`.
- **Data types:** String, Number, Boolean, Undefined, Null, Symbol (primitive); Object (non-primitive, includes Arrays and Functions).

| var | let | const |
|---|---|---|
| Function-scoped | Block-scoped | Block-scoped |
| Redeclarable | Not redeclarable | Not redeclarable |
| Reassignable | Reassignable | Not reassignable |

**Operators**
Arithmetic (`+`, `-`), comparison (`==`, `===`), logical (`&&`, `||`), assignment (`=`, `+=`).

**Functions**
Reusable blocks of code that perform a task:
```javascript
function greet(name) {
  return "Hello, " + name;
}
```
ES6 introduced shorter **arrow functions**:
```javascript
const greet = (name) => "Hello, " + name;
```

**Events**
JavaScript can detect and respond to user actions (click, hover, keypress) using event handlers:
```javascript
document.getElementById("btn").addEventListener("click", function() {
  alert("Button clicked!");
});
```

**Conclusion**
JavaScript's variables, functions, and event-handling capabilities together enable dynamic, interactive behavior on web pages — forming the scripting foundation used later for DOM manipulation and form validation.

---

## Q15. DOM Manipulation

### Question
**What is the Document Object Model (DOM)? Explain how JavaScript is used to manipulate the DOM with examples. [7 Marks]**

*Possible examiner variations:*
- Explain DOM manipulation with suitable examples of methods used.
- Discuss how the DOM tree structure represents an HTML document.
- Explain the use of event listeners in DOM manipulation.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction/definition of DOM
2. DOM tree structure (diagram)
3. Common DOM selection methods
4. DOM manipulation methods (content, style, attributes)
5. Event handling example
6. Conclusion

### Exam-Ready Answer

**Introduction**
The **Document Object Model (DOM)** is a programming interface that represents an HTML document as a hierarchical tree of objects (nodes), allowing JavaScript to dynamically access, modify, add, or remove content, structure, and styling.

**DOM Tree Structure**

```
        document
           │
         <html>
        /      \
   <head>      <body>
                /    \
           <h1>      <p>
```
Each HTML tag becomes a **node** in this tree that JavaScript can select and manipulate.

**Common DOM Selection Methods**

| Method | Purpose |
|---|---|
| `getElementById()` | Selects element by ID |
| `getElementsByClassName()` | Selects elements by class |
| `querySelector()` | Selects first matching element (CSS-style selector) |
| `querySelectorAll()` | Selects all matching elements |

**DOM Manipulation Methods**
```javascript
let el = document.getElementById("title");
el.innerHTML = "New Heading";        // Change content
el.style.color = "blue";             // Change style
el.setAttribute("class", "active");  // Change attribute
```

**Event Handling Example**
```javascript
document.getElementById("submitBtn").addEventListener("click", function() {
  document.getElementById("msg").innerText = "Form submitted!";
});
```

**Conclusion**
DOM manipulation allows web pages to update content and respond to user actions in real time without reloading, making it essential for building interactive, dynamic front-end interfaces.

---

## Q16. Forms and Form Validation

### Question
**Explain HTML forms and discuss client-side and server-side form validation with examples. [7 Marks]**

*Possible examiner variations:*
- Discuss the importance of form validation in web development.
- Differentiate between client-side and server-side validation with examples.
- Explain the GET and POST methods used in HTML forms.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction to HTML forms
2. Form elements and attributes
3. GET vs POST
4. Client-side validation (with example)
5. Server-side validation
6. Comparison table
7. Conclusion

### Exam-Ready Answer

**Introduction**
An **HTML form**, defined using the `<form>` tag, is used to collect user input (text, choices, files) and send it to a server for processing. **Form validation** ensures that the data entered is correct and complete before submission.

**Common Form Elements**
`<input>`, `<label>`, `<textarea>`, `<select>`, `<button>` — with attributes like `type`, `name`, `placeholder`, and `required`.

**GET vs POST**

| GET | POST |
|---|---|
| Data appended to URL | Data sent in request body |
| Visible, less secure | Hidden, more secure |
| Limited data size | Larger data allowed |
| Used for retrieving data | Used for submitting sensitive/large data |

**Client-Side Validation**
Performed in the browser using HTML attributes or JavaScript, giving instant feedback:
```html
<input type="email" required pattern="[a-z0-9]+@[a-z]+\.[a-z]{2,3}">
```
- Fast, but can be bypassed by disabling JavaScript.

**Server-Side Validation**
Performed on the server after form submission, re-checking data for correctness and security (e.g., using PHP/Node.js). Cannot be bypassed by the user, making it essential for security.

**Comparison Table**

| Aspect | Client-side | Server-side |
|---|---|---|
| Location | Browser | Server |
| Speed | Instant feedback | Slightly slower |
| Security | Can be bypassed | Cannot be bypassed |
| Purpose | UX improvement | Data integrity & security |

**Conclusion**
While client-side validation improves user experience with instant feedback, server-side validation is essential for security and data integrity — a robust web form should implement **both** together.

---

## Q17. AI-assisted UI/UX Design

### Question
**Explain the role of AI in UI/UX design. Discuss the benefits and limitations of AI-assisted design tools. [7 Marks]**

*Possible examiner variations:*
- Discuss how Generative AI tools assist in designing user interfaces.
- Explain the process of AI-assisted UI/UX design with examples.
- What are the advantages and challenges of using AI in UI/UX design?

### ⭐ Priority
⭐ Important

### Answer Structure
1. Introduction to UI/UX
2. Role of AI in design process
3. Example AI tools
4. Benefits
5. Limitations
6. Conclusion

### Exam-Ready Answer

**Introduction**
**UI (User Interface)** design focuses on the visual layout of an application, while **UX (User Experience)** design focuses on overall usability. **AI-assisted UI/UX design** uses AI tools to generate, suggest, and optimize interface elements, speeding up the design process.

**Role of AI in the Design Process**
- Generates layout and color-scheme suggestions based on design trends.
- Auto-creates wireframes and prototypes from text prompts or sketches.
- Analyzes user behavior data to suggest personalized interface improvements.
- Assists in accessibility checks (contrast, font size).

**Example AI Tools**
- **Figma (with AI plugins)** — design and prototyping with AI-assisted suggestions.
- **Uizard** — converts sketches/text prompts into UI designs.
- **Galileo AI** — generates UI designs from text descriptions.

**Benefits**
- Speeds up prototyping and iteration.
- Reduces design effort for repetitive elements.
- Provides data-driven personalization.
- Helpful for non-designers to create professional-looking interfaces.

**Limitations**
- May lack brand-specific context or creative originality.
- Accessibility and usability still require human validation.
- Over-reliance can lead to generic, templated designs.

**Conclusion**
AI-assisted UI/UX design tools significantly speed up the design workflow, but human designers remain essential for ensuring the final interface is contextually appropriate, accessible, and aligned with brand identity.

---

## Q18. AI-generated Responsive Layouts and Wireframing using AI Tools

### Question
**Explain the process of generating responsive layouts and wireframes using AI tools. [7 Marks]**

*Possible examiner variations:*
- Discuss how AI tools assist in wireframing and responsive layout generation.
- Explain the steps involved in creating an AI-generated responsive webpage layout.
- What is wireframing? Explain its importance before development.

### ⭐ Priority
⭐ Important

### Answer Structure
1. Introduction to wireframing
2. Introduction to AI-generated responsive layouts
3. Step-by-step process
4. Tools used
5. Advantages
6. Conclusion

### Exam-Ready Answer

**Introduction**
**Wireframing** is the creation of a basic visual skeleton of a webpage/app showing structure and placement of elements, done before detailed design. **AI-generated responsive layouts** extend this by using AI to auto-generate adaptive HTML/CSS structures that work across screen sizes.

**Why Wireframe First?**
Wireframing helps plan content hierarchy and navigation flow without being distracted by colors or detailed visuals, saving rework later in development.

**Step-by-Step AI-Assisted Process**

| Step | Description | Example Tool |
|---|---|---|
| 1. Concept input | Describe the page requirement in text or upload a sketch | Uizard, Figma AI |
| 2. Wireframe generation | AI generates a basic structural layout | Uizard |
| 3. Responsive layout generation | AI produces HTML/CSS with grid/flexbox and media queries | GitHub Copilot, ChatGPT |
| 4. Review & refinement | Developer checks breakpoints, accessibility, and correctness | Manual review |

**Advantages**
- Drastically reduces time spent on initial design and layout coding.
- Ensures consistency across pages when using AI-suggested design systems.
- Useful for rapid prototyping and iteration in early project stages.

**Conclusion**
AI tools for wireframing and responsive layout generation streamline the early design-to-code pipeline, but developers must still verify cross-device behavior, accessibility, and code quality before deployment.

---

## Q19. Website Accessibility

### Question
**Explain the concept of Website Accessibility. Discuss WCAG guidelines and techniques to improve accessibility. [7 Marks]**

*Possible examiner variations:*
- What is web accessibility? Why is it important?
- Discuss techniques to make a website accessible to users with disabilities.
- Explain the role of semantic HTML in accessibility.

### ⭐ Priority
🔥 Very Important

### Answer Structure
1. Introduction/definition
2. Why accessibility matters
3. WCAG guidelines overview
4. Techniques to improve accessibility
5. Example
6. Conclusion

### Exam-Ready Answer

**Introduction**
**Website Accessibility** refers to designing and developing websites so that people with disabilities — visual, auditory, motor, or cognitive — can perceive, understand, navigate, and interact with them effectively.

**Why Accessibility Matters**
- Ensures **equal access** to information and services for all users.
- Many countries legally require compliance (e.g., ADA, WCAG-based regulations).
- Improves usability and SEO for **all** users, not just those with disabilities.

**WCAG (Web Content Accessibility Guidelines)**
WCAG is built around four principles, often remembered as **POUR**:
- **Perceivable** — content must be presentable in ways users can perceive (e.g., alt text for images).
- **Operable** — interface components must be operable (e.g., keyboard navigation).
- **Understandable** — content and operation must be understandable.
- **Robust** — content must work with a wide variety of assistive technologies.

**Techniques to Improve Accessibility**
- Use **semantic HTML** (`<header>`, `<nav>`, `<main>`) so screen readers interpret structure correctly.
- Provide **`alt` text** for all meaningful images.
- Ensure sufficient **color contrast** between text and background.
- Enable **keyboard navigability** for all interactive elements.
- Use **ARIA** (Accessible Rich Internet Applications) attributes where semantic HTML is insufficient.

**Example**
```html
<img src="chart.png" alt="Bar chart showing quarterly sales growth">
```

**Conclusion**
Website accessibility is both an ethical responsibility and, increasingly, a legal requirement — semantic HTML, proper alt text, keyboard support, and WCAG compliance together ensure an inclusive web experience for all users.

---

## Q20. Website Optimization

### Question
**Explain the techniques used for website optimization. Discuss their impact on performance and SEO. [7 Marks]**

*Possible examiner variations:*
- Discuss various techniques to improve website loading speed.
- Explain the role of image compression and minification in optimization.
- How does website optimization affect SEO ranking?

### ⭐ Priority
⭐ Important

### Answer Structure
1. Introduction/definition
2. Need for optimization
3. Key techniques
4. Impact on SEO
5. Conclusion

### Exam-Ready Answer

**Introduction**
**Website Optimization** refers to improving a website's loading speed, performance, and overall efficiency through technical and content-level improvements, directly affecting user experience and search engine ranking.

**Need for Optimization**
Slow websites lead to higher bounce rates, poor user experience, and lower search engine rankings, making optimization essential for both usability and visibility.

**Key Optimization Techniques**

| Technique | Description |
|---|---|
| Image compression | Reduces image file size while preserving visual quality |
| Minification | Removes unnecessary characters (spaces, comments) from CSS/JS files |
| Lazy loading | Loads images/content only when they enter the viewport |
| Caching | Stores static resources locally to avoid repeated downloads |
| Code splitting/bundling | Combines/splits files efficiently to reduce HTTP requests |
| CDN (Content Delivery Network) | Serves content from servers closer to the user for faster delivery |

**Impact on SEO**
- Search engines like Google factor **page speed** into ranking algorithms.
- Faster, optimized websites reduce bounce rate and increase user engagement, indirectly boosting SEO performance.
- Mobile optimization is especially critical since most search traffic is mobile-first indexed.

**Conclusion**
Website optimization — through image compression, minification, lazy loading, and caching — directly improves both user experience and SEO ranking, making it a critical final step in modern responsive web development.

---

## Q21. Mini Project — College Event Management Website

### Question
**Explain the design and development process of an AI-generated College Event Management Website with a responsive interface. [7 Marks]**

*Possible examiner variations:*
- Discuss the key features and AI-assisted development steps for a College Event Management Website.
- Explain how AI tools can be used to design a responsive interface for an event management system.

### ⭐ Priority
⭐ Important

### Answer Structure
1. Introduction/objective
2. Key features required
3. AI-assisted development process (steps)
4. Responsive design considerations
5. Conclusion

### Exam-Ready Answer

**Introduction**
This mini project involves designing and developing a **College Event Management Website** with a responsive interface, using AI tools to assist in layout generation, UI design, and code development — applying concepts covered throughout Unit 2.

**Key Features of the Website**
- Event listing/calendar page.
- Event registration form (with validation).
- Admin panel for adding/managing events.
- Responsive navigation and layout across devices.

**AI-Assisted Development Process**

| Step | Description | AI Tool Example |
|---|---|---|
| 1. Wireframing | Generate a basic layout structure from a text prompt | Uizard, Figma AI |
| 2. UI design | Generate color scheme, typography, and component design | AI UI/UX tools |
| 3. HTML/CSS/JS generation | Auto-generate responsive structure and styling code | GitHub Copilot, ChatGPT |
| 4. Form & validation | Generate registration form with client-side validation | AI coding assistant |
| 5. Testing & refinement | Manually test across devices; fix bugs and accessibility issues | Developer review |

**Responsive Design Considerations**
- Use Bootstrap or CSS Grid/Flexbox for a mobile-first, multi-device layout.
- Ensure the registration form and event listings adapt cleanly to smaller screens using media queries.

**Conclusion**
This mini project demonstrates end-to-end application of AI-assisted front-end development — from wireframing to responsive, validated forms — reflecting how AI tools can accelerate real-world website development while requiring human testing and refinement for a production-ready result.

---

# 🔥 TOP 30 MUST-PREPARE 7-MARK QUESTIONS

1. Explain the evolution of web technologies from Web 1.0 to Web 3.0.
2. Explain Front-end, Back-end, and Full Stack development with a comparison.
3. Explain Artificial Intelligence and Generative AI, and how Generative AI differs from traditional AI.
4. What are Large Language Models (LLMs)? Explain their architecture and role in software development.
5. Explain the AI-assisted Software Development Life Cycle with AI integration at each phase.
6. Discuss the benefits and limitations of AI-assisted SDLC.
7. What are AI Coding Assistants? Explain their features, benefits, and limitations.
8. What is Prompt Engineering? Explain key techniques with examples.
9. Discuss ethical concerns and responsible practices in using AI for software development.
10. Explain the process of developing an AI-generated Personal Portfolio Website.
11. Explain the new features introduced in HTML5 with examples.
12. Explain the CSS Box Model, Flexbox, and Grid layout systems.
13. Explain Responsive Web Design and the techniques used to achieve responsiveness.
14. What is Bootstrap? Explain its grid system and key components.
15. Explain the fundamental concepts of JavaScript (variables, data types, functions).
16. What is the DOM? Explain how JavaScript is used to manipulate it.
17. Explain HTML forms and discuss client-side vs server-side validation.
18. Differentiate between GET and POST methods used in HTML forms.
19. Explain the role of AI in UI/UX design with benefits and limitations.
20. Explain the process of generating responsive layouts and wireframes using AI tools.
21. Explain Website Accessibility and WCAG guidelines with techniques to improve it.
22. Explain the techniques used for Website Optimization and their impact on SEO.
23. Explain the design and development process of the College Event Management Website mini project.
24. Differentiate between Web 1.0, Web 2.0, and Web 3.0 with examples.
25. Explain the relationship between AI, Machine Learning, Deep Learning, and Generative AI.
26. Discuss zero-shot and few-shot prompting with examples.
27. Explain semantic elements in HTML5 and their importance for accessibility/SEO.
28. Differentiate between Flexbox and CSS Grid with use cases.
29. Explain the mobile-first approach in responsive web design.
30. Discuss AI bias and data privacy as ethical concerns in AI-assisted development.

---

# ⚡ 7-MARK ANSWER WRITING TEMPLATE

Use this reusable structure for any 7-mark question in this subject:

1. **Introduction (1–1.5 marks)**
   Start with a precise definition of the main concept in 2–3 lines. Avoid vague or story-like openings.

2. **Core Explanation / Main Concepts (3–4 marks)**
   - Break the concept into logical sub-points or stages.
   - Use headings/bullet points, not paragraphs, wherever possible.
   - Include a **diagram, flowchart, or table** if the concept has stages, comparisons, or architecture (SDLC phases, DOM tree, Box Model, etc.) — diagrams earn easy marks and show clarity.

3. **Example / Code Snippet (1 mark)**
   Include one short, relevant example (real-world example or a short code snippet) to demonstrate applied understanding — this is what separates a 7-mark answer from a 2-mark definition.

4. **Advantages / Limitations / Comparison (where relevant) (1 mark)**
   If the question allows it, add a short table of benefits/limitations or a comparison with a related concept — this demonstrates deeper conceptual understanding, not just memorization.

5. **Conclusion (0.5–1 mark)**
   End with 2–3 lines connecting the concept back to its practical importance in web development or AI-assisted development — do not simply repeat the introduction.

**General Tips**
- Always underline or bold key terms.
- Use tables for any "differentiate/compare" question — they score better than paragraph comparisons.
- Keep the total answer length proportional to 7 marks: detailed but not padded with repetition.
- Never present a 7-mark answer as a list of definitions only — the answer must show *how* and *why*, not just *what*.
