# MSc Thesis Plan Roadmap
## The Success Guide for the NOVAthesis LaTeX Template

Welcome to the first major milestone of your Master’s journey. The **MSc Plan** is not just a hurdle; it is the architectural blueprint for your research. Your goal is to produce a document of **at most 35 pages** (using the `novathesis` LaTeX template) that proves your problem is worth solving, you understand the landscape, and you have a realistic path to execution.

---

## Document Structure
The following three chapters form the core of your MSc Plan. Together, they must tell a cohesive story: from the broad context of the field to the specific technical gap you intend to fill, and finally to the concrete engineering roadmap you will follow.

### Chapter 1: The Introduction (The Hook)
The introduction is where you “win or lose” your reader. It must provide a logical bridge from the general domain to your specific niche.

#### The “Four-Move” Checklist
1.  **Context (Establish the Territory):** Why does this field matter today? 
    *   *Mentorship Advice:* Use recent stats or industry trends (e.g., “The 300% increase in IoT deployment...”).
2.  **Problem Statement (Identify the Gap):** What is the specific “pain point”? 
    *   *Mentorship Advice:* Get inspired by the phrase: “Current approaches fail to address [X] because [Y].”
3.  **Objectives (Fill the Gap):** State your goals very objectively. **Do not** use generic statements. Use S.M.A.R.T. criteria for justifying the relevance of your goals.
    *   *S.M.A.R.T:* Specific, Measurable, Achievable, Relevant, and Time-bound.
4.  **Insight & Expected Contributions (The “Value Add”):** What is your “secret sauce”?
    *   *Mentorship Advice:* Don’t just say “I will build a system.” Say “The system will leverage [Novel Insight X] to achieve [Performance Gain Y].”

> **Pro-Tip:** Write the Introduction last (or rewrite it after your Methodology is firm). You can only introduce a journey once you know where it ends.

---

### Chapter 2: Background vs. Related Work vs. Related Technologies
A common mistake is treating these as the same. Think of them as **“The Science vs. The Neighbors vs. The Gear.”**

#### Scientific Background (The “Book Knowledge”)
These are the foundational theories, definitions, and technologies that a peer needs to understand your work.
*   **Focus:** Fundamental concepts, protocols, mathematics, hardware specs, and established algorithms.
*   **Source:** Textbooks, tutorials, and seminal (old but gold) papers.
*   **Checklist:** *“If I mention a term that isn’t common knowledge, is it defined here?”*

#### Related Work (The “State of the Art”)
This is the neighborhood you are moving into. It includes those working on your *exact* problem, but also those solving **analogous problems** in different domains.
*   **Focus:** Papers from the last 2–5 years.
*   **Think Laterally:** Sometimes the best solution for your problem comes from a different field. 
    *   *Example:* If you are analyzing GPS trajectories, you might look at bioinformatics algorithms for DNA string comparison. By converting GPS coordinates into a sequence of symbols (chars), you can use established “string matching” techniques to find patterns in movement.
*   **The Synthesis Matrix:** Don’t write a list of summaries (“Author A did X. Author B did Y.”). Create a table comparing existing works based on features, performance, or limitations.
*   **Transposing the Matrix (The Pro Move):** Use the *columns* (properties/features) of your matrix as your subheadings, not the rows (authors). 
    *   *Why?* Writing about “Scalability” or “Accuracy” across all papers is much more insightful than writing three separate paragraphs about three different papers. It forces you to compare them directly and makes the “Gap” in the literature obvious.
*   **Gap Analysis:** This is the most critical section. You must conclude this chapter by explaining why the existing works (including the analogous ones) are insufficient for your specific problem.

#### Related Technologies (The “Building Blocks”)
While Background covers *theory*, Related Technologies covers the *tools* you will actually use to achieve your objectives.
*   **Focus:** Specific frameworks (e.g., TensorFlow, React), APIs, hardware platforms (e.g., Jetson Nano), or protocols mentioned in your objectives.
*   **The “Why” Factor:** Don’t just list them. Justify why you chose [Tech A] over [Tech B]. (e.g., “While Docker is common, we use Podman because of its rootless architecture, which is critical for our security objective [O2]”).
*   **Integration:** This section should link the problems identified in the *Related Work* to the specific tools you’ll use to solve them in your *Methodology*.

---

### Chapter 3: Workplace & Methodology (The Blueprint)
This is where you prove you are an engineer/scientist, not just a dreamer.

#### Proposed Solution (The “What”)
*   **Architecture:** Use a clean, vector-based diagram (use TikZ or draw.io exported as PDF).
*   **Functional Specs:** Detail the “Workplace”—the software stacks, hardware constraints, or laboratory settings.

#### Validation Strategy (The “How”)
*   **Metrics/KPIs:** Define exactly how you will measure success. Is it *Latency (ms)*? *Accuracy (%)*? *Energy Consumption (J)*? 
*   **Comparison:** Who is your “Baseline”? You must compare your solution against a known standard or a “vanilla” implementation.

#### Temporal Planning (The “When”)
*   **Gantt Chart:** Use `pgfgantt` in LaTeX. 
*   **Reality Check:** 
    *   *Month 1-2:* Setup & Prototyping.
    *   *Month 3-5:* Implementation & Data Collection.
    *   *Month 6:* Analysis & Thesis Writing.
*   **Buffer:** Always add a 20% “Oh no!” buffer for debugging and hardware failures.

---

## Citation Mechanics & Ethics
In technical writing, citations are the “currency” of credibility. Misplacing them can lead to ambiguity or, worse, accusations of plagiarism.

### Where to Place the Citation?
The placement of a citation changes its meaning. Follow these rules:

1.  **Near the Subject (Specific Attribution):** Use this when you are attributing a specific idea, algorithm, or result to a specific author.
    *   *Example:* “The Fast-Flux algorithm, proposed by Smith et al. [14], improves latency by...”
2.  **End of the Sentence (General Support):** Use this when the entire sentence is supported by a source.
    *   *Example:* “Recent studies show that edge computing reduces jitter in autonomous systems [22].”
3.  **End of the Paragraph (Block Support):** **Avoid this.** Placing a single citation at the end of a paragraph is ambiguous. Does it support the last sentence or the whole paragraph? 
    *   *Pro-Tip:* Cite as early as possible in the paragraph to establish the source of the logic.

### Ethics & Giving Credit
*   **The “Common Knowledge” Test:** You don’t need to cite that “the sky is blue” or “Python is a programming language.” You **must** cite everything else: data, unique diagrams, specific metrics, and controversial claims.
*   **Paraphrasing != Originality:** Even if you rewrite a paragraph in your own words, the *idea* still belongs to the original author. Cite it.
*   **Self-Plagiarism:** If you published a paper in a conference during your MSc, you must still cite yourself when including that work in your thesis.
*   **The “Shadow” Citation:** If Paper A cites Paper B for a specific fact, you should ideally read and cite Paper B (the primary source) rather than just relying on Paper A’s interpretation.
*   **Citing Code & Libraries:** If you use a specific GitHub repository or a specialized library (e.g., a custom CUDA kernel), cite it. If there is no paper, cite the URL and the version/commit hash used.
*   **Honest Acknowledgement:** If a colleague or an AI tool helped significantly with a specific proof or debugging session, mention it in the “Acknowledgements” section. Transparency is the best defense against ethical queries.

> **Pro-Tip:** Use `\cite{...}` immediately after the word or phrase it supports. In LaTeX, ensure there is a non-breaking space (`~`) before the citation: `...logic~ \cite{key}`. Also, use `\citeauthor{key}` to properly typeset the authors’ names in your text.

---

## Technical Writing & Typography
An engineering thesis is a technical manual, not a novel. Clarity and precision are your primary goals. Use these rules to ensure your text is professional and readable.

### The Writing Style
*   **Short & Punchy Sentences:** Avoid long, winding sentences with multiple sub-clauses. If a sentence is longer than three lines, break it in two.
*   **Active Voice (The “I/We” Rule):** In modern engineering, we avoid the passive voice (“The data was collected”). Use the active voice to clarify responsibility: “I collected the data” or “We implemented the algorithm.”
*   **Repeat the Subject:** Avoid using “it,” “this,” or “that” to start a sentence unless the reference is 100% clear. It is better to repeat the noun (“The algorithm improves...”) than to leave the subject implicit.
*   **No “Fluff”:** Delete words like “very,” “extremely,” or “basically.” If a result is significant, the data will show it.

### Visuals & Layout
*   **Vectors over Rasters:** Always use **PDF** or **EPS** for your diagrams and plots. These are vector formats that stay sharp at any zoom level. Only use PNG/JPG for actual photographs.
*   **Floating Objects (Figures & Tables):** In LaTeX, figures and tables are “floats.” They don’t have to stay exactly where you write the code. They should be at the top or bottom of the page near where they are first mentioned. 
    *   *Rule:* Never say “the figure below.” Always use a reference: “As shown in Figure~\ref{fig:arch}...”
*   **Know Your Caption Style:** The expected detail in captions varies by field.
    *   **Concise Style (e.g., CS/Engineering):** Captions are brief identifiers (e.g., “Figure 4.1: System Architecture overview”). Detailed technical analysis belongs in the main text.
    *   **Self-Contained Style (e.g., Life Sciences):** Captions are detailed enough that the reader can understand the figure or table without reading the main text.
    *   *Rule:* Consult your advisor or field-specific standards to determine which convention is expected for your thesis.
*   **Consistent Units:** Always use a non-breaking space between a number and its unit (e.g., 10~ms, 50~GB). Use the `siunitx` package for perfect formatting.

### Typographic Precision
*   **Italics for Emphasis:** Use italics sparingly for new terms. Never use **bold** or ALL CAPS for emphasis within a paragraph. 
    *   *LaTeX Pro-Tip:* Use `\emph{...}` rather than `\textit{...}`. The `\emph` command is context-aware and will correctly handle nested emphasis (e.g., italics within an already italicized block).
*   **Quotes:** Always use typographic “curly” quotes. In LaTeX, this is done using two backticks for open (``) and two single quotes for close ('').
*   **Dashes:** Use an en-dash (`--`) for ranges (e.g., 10–20 pages) and an em-dash (`---`) for parenthetical thoughts.

---

## LaTeX Tips & Tricks
The `novathesis` template is powerful, but these specific packages and practices will elevate your document from “good” to “professional.”

### Essential Packages
*   **`booktabs`:** Forget the standard horizontal and vertical lines. Use `\toprule`, `\midrule`, and `\bottomrule` to create clean, professional tables that look like they belong in a high-end journal.
*   **`cleveref`:** Tired of typing “Figure~\ref{...}”? This package automates it. Just use `\cref{label}`, and it will automatically detect if it’s a Figure, Table, or Equation and format the text accordingly.
*   **`enumitem`:** Gives you total control over lists (`itemize`, `enumerate`). Use it to reduce vertical spacing between items or to change numbering styles (e.g., a), b), c)).
*   **`graphicx`:** The standard for including images. Always use `\includegraphics[width=FACTOR\textwidth]{...}` (e.g., `\includegraphics[width=0.75\textwidth]{...}`) to ensure your figures scale properly with your margins. **Pre-loaded in the `novathesis` template**.
*   **`fontenc [T1]`:** Ensures your PDF uses modern fonts that support accented characters and allows for proper copy-pasting from the final document, by using `\usepackage[T1]{fontenc}`. **Pre-loaded in the `novathesis` template**.
*   **`siunitx`:** The absolute gold standard for units. Use `\unit{10}{\milli\second}` to ensure the spacing and font for units are always mathematically correct.
*   **`microtype`:** A “magic” package that slightly adjusts character spacing to eliminate awkward gaps in justified text and reduces the number of hyphens at the end of lines. **Pre-loaded in the `novathesis` template**.
*   **`glossaries-extra`:** Managing acronyms manually is a recipe for error. Use this to define terms once and have LaTeX handle the “First mention (Full Name)” vs. “Subsequent mention (Acronym)” logic automatically. **Pre-loaded in the `novathesis` template**.

### Workflow Hacks
*   **Comment your logic:** Use `%` to leave notes for yourself or your advisor in the source code.
*   **Labels with Prefixes:** Stay organized with a consistent labeling system: `fig:architecture`, `tab:results`, `eq:objective`, `lst:algorithm`.
*   **The “Non-breaking Space” (`~`):** Always place a tilde before a `\cite`, `\ref`, or before numbers in general to prevent them from jumping to a new line alone (e.g., “In~1974 there was a revolution in Portugal.”).
*   **TikZ for Diagrams:** For the bravest students, learning `TikZ` allows you to "code" your diagrams directly in LaTeX, ensuring perfect font consistency with your main text.

---

## The MSc Toolbox

### Literature Search: Beyond Keywords
1.  **[ResearchRabbit](https://www.researchrabbit.ai):** Best for “Discovery.” It maps the citation graph of your starting papers.
2.  **[Connected Papers](https://www.connectedpapers.com):** Visualizes the “neighborhood” of a single seminal paper.
3.  **[Semantic Scholar](https://www.semanticscholar.org):** Uses AI to tell you which citations actually *influenced* the work vs. just mentioning it.
4.  **[Google Scholar](https://scholar.google.com):** The essential starting point for broad searches.

**The Snowballing Strategy:** 
*   **Backward Snowballing:** Use the references within a paper to find **older** related work.
*   **Forward Snowballing:** Use the “Cited by” link in Google Scholar to find **newer** related work that has built upon that paper since its publication.

### Academic Credibility: The “Quality Filter”
Evaluate your sources using these industry standards:
*   **CORE Rankings (CS Only):** Aim for A* or A conferences. B is acceptable. C requires scrutiny. [Portal](https://portal.core.edu.au/conf-ranks/)
*   **SJR (Scimago Journal Rank):** Look for Q1 (top 25%) or Q2 journals.
*   **H5-Index:** Found on Google Scholar “Metrics.” It shows the impact of a venue over the last 5 years.
*   **Citation Count:** If a paper from 2022 has 100+ citations, it’s a “must-read.”

### AI & LLM Pedagogy (Ethics & Integrity)
Use LLMs as a **Rubber Duck** or **Tutor**, never as a ghostwriter.
*   **NotebookLLM:** Upload your “must-read” PDFs. Ask: “What are the common limitations mentioned across these 5 papers?”
*   **Hallucination Check:** **Never** trust an LLM’s citation list. They often invent titles that sound real. Always find the DOI yourself.
*   **Prompting for Integrity:** 
    *   *Bad:* “Write the introduction for my thesis on AI.”
    *   *Good:* “I have these three objectives for my thesis. Can you help me find logical inconsistencies or gaps in my reasoning?”

### Technical Workflow
*   **Online Editors:**
    *   **[Overleaf](https://www.overleaf.com):** The standard for collaboration and ease of use.
    *   **[OpenAI Prism](https://prism.openai.com):** A modern alternative for AI-assisted collaborative editing.
    *   **[WebLaTeX](https://github.com/sanjib-sen/WebLaTex):** Recommended only for advanced, “tech-safe” users who require specialized control over their environment.
*   **Template:** Use the **novathesis** template (available on **[Overleaf](https://www.overleaf.com/latex/templates/novathesis-template/mpxfgrvskvwy)** or **[GitHub](https://github.com/joaomlourenco/novathesis)**). It’s the easiest way to ensure your formatting meets university standards.
*   **Bib Management:** 
    *   **Zotero:** The gold standard for managing references.
    *   **DOI2BIB:** Use this to generate clean, minimal BibTeX entries. Avoid the “messy” BibTeX often found on Google Scholar.
    *   **LLM Assistance:** LLMs can convert raw text references into clean BibTeX entries and search for DOIs. You **must** manually verify the quality of the generated entry and the validity of the DOI.
*   **Local Setup:** For power users, use **VS Code + LaTeX Workshop + GitHub**.

---

## Final Submission Checklist
- [ ] **Length:** Is it under 35 pages? (Quality > Quantity).
- [ ] **Figures:** Are all diagrams vector-based (PDF/SVG)? Can you read the text on the axes of your plots?
- [ ] **The “Story”:** Does the Related Work naturally lead to the Gap, which naturally leads to your Solution?
- [ ] **References:** Is every citation in the text present in the Bibliography? (LaTeX does this automatically, but check for “??”).
- [ ] **Tone:** Is it objective? (Avoid “I think,” “I feel,” “I believe.” Use “The data suggests,” “The proposed model...”).

---

**Mastering the MSc Plan is about proving you have a map. Once you have the map, the journey becomes a matter of discipline. Good luck!**
