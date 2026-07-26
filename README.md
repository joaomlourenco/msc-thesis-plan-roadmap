# MSc Thesis Plan Roadmap
## A Success Guide for the MSc Plan (with the NOVAthesis LaTeX Template)

Welcome to the first major milestone of your Master's journey. The **MSc Plan** is not just a hurdle; it is the architectural blueprint for your research. Your goal is to produce a short document that proves your problem is worth solving, that you understand the landscape, and that you have a realistic path to execution.

While certain sections of this document offer general guidance, this resource is specifically designed for Computer Science students at [NOVA FCT](www.di.fct.unl.pt). Readers from other scientific domains are advised to consider the inherent technical, methodological, and cultural distinctions.

---

## 1. The MSc Plan at a Glance

The MSc dissertation is divided into two distinct phases: the **preparation** (the MSc Plan) and the **elaboration** (the MSc Thesis). The MSc Plan is a 12 ECTS course, corresponding to an effort of approximately 320 hours, i.e., about 16 hours (two full working days) per week over 20 weeks.

### Deliverables and Evaluation

- **The Document:** You must write a document of **at most 35 pages** using the School's official template (**NOVAthesis**, see Section 10). The limit refers to the main content (pages numbered with arabic numbers) and does not include the Bibliography; frontmatter is numbered with roman numerals. It is strongly recommended **not** to add appendices or annexes, as committee members will most likely not look at them.
    - *Note:* The MSc Plan is a solid foundation for your final MSc Thesis. However, it should **never be used “as is”** in the final stage; it must be carefully revised, expanded, and updated as your research evolves and results are obtained (see Section 13).
- **The MSc Plan Discussion:** The *MSc Plan* phase concludes with an exam including an oral presentation of approximately 15 slides (~15 minutes: 3–5 min for Context & Problem, 5–8 min for Related Work, and 4–6 min for Work Plan), followed by a Q&A session.
- **The Committee:** The committee is nominated by the MSc Coordinator after the submission of the MSc plan. It includes your advisor and another professor from the department, who will carefully review your document and discuss your work plan with you. The attitude is generally positive and constructive, but be prepared for “hard” questions on any of the expectations listed in Section 2.
- **The Result:** The result is binary: **Approved** or **Failed**. Failing requires the student to repeat the defense of the MSc Plan in the following semester (on the same topic—if the advisor agrees to continue supervision—or a different topic).
- **Industry Partnerships & NDAs:** For MSc plans and theses conducted in partnership with a company or industry sponsor, Non-Disclosure Agreements (NDAs) can be signed to protect corporate interests, allowing for a closed (non-public) defense.

### Mandatory: AI Disclosure Statement

According to NOVA FCT regulations, both the MSc Plan and the MSc Thesis **must** include an AI Disclosure Statement. The **NOVAthesis** template includes a standardized form for this disclosure.

- **The Requirement:** You must accurately and transparently declare how (and to what extent) AI tools (like LLMs, GitHub Copilot, etc.) were used in the research, coding, or writing process using the template's standardized form.
- **Why it Matters:** A clear declaration is crucial for the **credibility** and **evaluation** of your work. It allows the committee to properly appreciate your original contributions and ensures scientific integrity.
- **Consequence:** Failure to disclose or providing an inaccurate declaration can lead to serious ethical queries and may affect the final evaluation.

---

## 2. What Is Expected from You

By the end of this phase, you are expected to be able to:

- **Understand the Proposal:** Properly grasp the core of your thesis proposal.
- **Present Context:** Clearly present the “context” for your topic and work.
- **Identify the Problem:** Clearly identify the specific problem you are going to solve.
- **Define Objectives:** Clearly identify the objectives of your work.
- **Single-Phrase Insight:** Express the core insight behind your proposed approach in a single phrase or paragraph.
- **Master Related Work:** Demonstrate solid knowledge of the “related work,” providing a critical perspective (pros and cons) of the most relevant aspects. Expect some non-trivial questions on this topic.
- **Master the Background:** Demonstrate solid knowledge of the fundamentals (background) of the areas related to the topic. Expect some non-trivial questions on this topic.
- **Critical Tech Evaluation:** Demonstrate a critical evaluation of the relevant technologies.
- **Work Plan:** Propose a credible work plan for the “elaboration” phase (see *Temporal Planning* in Section 5 for detailed guidance).

---

## 3. How You Will Work: The Weekly Meeting

> _This section is tightly connected with my own working and supervising methodology.  Your adviser may have different rules or even a different methodology. Please confirm with them what does and does not apply._

Your progress rests on a simple, disciplined weekly rhythm with your advisor. Get this rhythm right and everything else becomes easier. When there is co-supervision, usually both advisers participate in the weekly meeting (sporadically only one may attend).

### The Weekly Cycle

- **The meeting (day X):** You meet your advisor once a week, on a fixed weekday. **You and your advisor agree on day X at the beginning of the semester.**
- **The deliverable (day X-2):** By the end of the day, two days before the meeting, you send your advisor a document with whatever you wrote during that week.
    - **Format:** Write it in **LaTeX and deliver it as a PDF** (use the NOVAthesis template from the start). If you worked in a new separate document that week, send that document. If the work continued on a document from the previous week, send the whole document with a clear note stating what is new. The contents grow with your work: usually you begin with notes on the background and related work, then the Introduction (with a clear definition of your goals), and later the work plan.
    - **How to send it:** Agree the channel with your advisor (e.g., email, a shared Overleaf project, or a Git repository).
    - **If you wrote nothing that week:** Still send an email on day X-2 saying so, and state whether the meeting should be held or cancelled.
- **The feedback (day X):** At the meeting you receive feedback on what you wrote, following the agenda below.
- **After the meeting:** Write a brief **minute (transcription)** of the meeting and send it to your advisor, so that decisions and open points are never lost between weeks.

### The Meeting Agenda

You drive the agenda. Come prepared to cover:

1.  A summary of what was done the previous week.
2.  The lessons learned from that week's work.
3.  Open points, doubts, and analysis of results.
4.  Comments on the text you sent on day X-2.
5.  Planning for the coming week.

The meeting is **preferably in person** (online only if necessary) and lasts **30 to 60 minutes**.

### Managing the Semester's Rhythm

Your semester is not uniform. Mid-semester brings peak-pressure periods from other courses (tests and projects).

- **It is fine to pause.** You may reasonably decide not to work on the thesis during those weeks, and even cancel the meeting. **If you cancel, do it on day X-2**, not at the last minute.
- **Work ahead early.** The key to not accumulating a backlog is to *work ahead* at the start of the semester, when the load from other courses is minimal. In the framework of the thesis plan, “working ahead” means: define the objectives, study the background, study the related work, study the related technologies, and define the work plan.

---

## 4. Your Thesis Is an Experiment: The Scientific Method in Engineering

Before diving into the document structure, step back and notice something useful: the engineering process you already know is the scientific method in disguise. Your thesis is not “just building a system”; it is running an experiment.

| The Scientific Method | The Engineering Process |
|---|---|
| Observation & research question | Requirements & problem statement |
| Literature review | Study of existing systems and prior art |
| Hypothesis | Your design and its core insight |
| Experiment | Prototype, tests, and benchmarks |
| Analysis & conclusion | Evaluation against the requirements |
| Peer review & replication | Code review & reproducible builds |
| New questions | Next iteration |

Keep five consequences in mind:

- **Debugging is the scientific method.** You observe a failure, hypothesize its cause, predict what a fix should change, instrument the code, and accept or reject the hypothesis. If you debug by random mutation, you are doing bad science.
- **Your prototype is the experimental apparatus, not the contribution.** The system you build plays the role a telescope plays for an astronomer: it exists to test your insight. Your contribution is the validated insight, and that is why the committee will keep asking about validation.
- **Iteration is part of the method.** Each development cycle produces evidence that confirms or refutes your assumptions, and your plan should be revised accordingly. Neither science nor engineering is a linear waterfall.
- **Beware of contamination.** In a wet lab, a dirty test tube or a stray bacterium invalidates the experiment. Your test machine is your lab bench, and it contaminates just as easily: background processes competing for CPU, cache, or network, other users on a shared server, a changed library version, or even thermal throttling can silently alter the functional behavior or the performance of your prototype. Control the environment (dedicated machine, pinned dependencies, repeated runs) and record its state, so that contamination can be detected and your results reproduced.
- **Predict before you run.** You can only perceive a malfunction, or a contaminated result, if you knew what to expect. Before running an experiment, write down your prediction: the expected values, or at least the expected trend and order of magnitude. Without a prediction made *before* running the experiment (or analyzing the results), every result looks valid, and errors pass unnoticed. With a prediction, a surprise becomes a signal: either a discovery or a bug to investigate. This is exactly how a wet-lab scientist spots a contaminated culture: by knowing what a clean one looks like.

The analogies above also have limits, and knowing them keeps you honest: science optimizes for *knowledge* (a negative result is still a result), while engineering optimizes for a *working artifact* (a negative result means rework); and nature's laws do not change during your experiment, but requirements do.

This mapping is exactly what the suggested structure in Section 5 implements: Chapter 1 of the Dissertation Plan document states your question and hypothesis, Chapter 2 is your literature review, and Chapter 3 is your experiment design.

---

## 5. Document Structure (Suggestions Only)

> **Important Note:** The structure, organization, and contents listed below are **ONLY SUGGESTIONS** (hints) and should never be followed blindly. Every research project is unique; you are expected to create your own document structure tailored to your specific topic, goals, and approach.

The following three chapters represent a typical baseline for an MSc Plan. Together, they must tell a cohesive story: from the broad context of the field to the specific technical gap you intend to fill, and finally to the concrete engineering roadmap you will follow.

### Chapter 1: The Introduction (The Hook)

The introduction is where you “win or lose” your reader. It must provide a logical bridge from the general domain to your specific niche.

#### The “Six-Move” Checklist

1.  **Context (Establish the Territory):** Why does this field matter today?
    - *Mentorship Advice:* Use recent stats or industry trends (e.g., “The 300% increase in IoT deployment...”).
2.  **Problem Statement (Identify the Gap):** What is the specific “pain point”?
    - *Mentorship Advice:* Get inspired by the phrase: “Current approaches fail to address [X] because [Y].”
3.  **Objectives (Fill the Gap):** State your goals very objectively. **Do not** use generic statements. Use S.M.A.R.T. criteria for justifying the relevance of your goals.
    - *S.M.A.R.T:* Specific, Measurable, Achievable, Relevant, and Time-bound.
4.  **Insight & Expected Contributions (The “Value Add”):** What is your “secret sauce”?
    - *Mentorship Advice:* Don't just say “I will build a system.” Use a phrasing that highlights the specific value added:
        - **Performance-Oriented:** “The system will leverage [Novel Insight X] to achieve **[Performance Gain Y]**.”
        - **Capability-Oriented:** “The system will leverage [Novel Insight X] to **enable [New Functionality Z]**, overcoming the [Specific Barrier] inherent in current approaches.”
        - **Property-Oriented:** “By incorporating [Novel Insight X], the system will **guarantee [Property P]** (e.g., leveraging blockchain to achieve **auditability**) while maintaining [Baseline Performance].”
        - **Process-Oriented:** “The system will apply [Novel Insight X] to **simplify [Task T]**, reducing the [Operational Complexity] (e.g., leveraging LLMs to **automate the generation of boilerplate code**) associated with [Current Methods].”
    - *If you cannot yet quantify the gain,* focus on the **Behavioral Change** or the **Structural Trade-off**:
        - **Behavioral Validation:** “The system will leverage [Insight X] to **ensure [Behavior B]** under [Condition S], validating the robustness of the approach where current solutions fail.”
        - **Trade-off Analysis:** “The system will apply [Insight X] to **shift the trade-off** between [Metric A] and [Metric B], providing a more favorable balance for [Specific Use Case].”
5.  **Scope & Assumptions (Define the Boundaries):** Prevent “scope creep” by clearly stating what is *not* being done and what you are taking for granted.
    - *Example (Scope):* “This thesis focuses on inference optimization. Training and federated learning are out of scope.”
    - *Example (Assumptions):* “We assume constant network bandwidth of 10 Mbps and hardware availability of at least one NVIDIA T4 GPU.”
6.  **Document Organization (The Roadmap):** Close the chapter with a short paragraph describing the structure of the rest of the document.
    - *Example:* “The rest of this document is organized as follows: Chapter 2 reviews... Chapter 3 presents...”

> **Pro-Tip:** Write a draft of your Introduction early, to ensure you are in sync with your advisor in terms of the problem and objectives. Later (maybe even as a last task), after your Methodology is firm, revise it carefully. *You can only properly introduce a journey once you know where it ends.*

### Chapter 2: Background, Related Work, and Related Technologies

A common mistake is treating these three as the same. Think of them as **“The Science vs. The Neighbors vs. The Gear.”** (This heading describes the *contents*; pick your own chapter title and split into more chapters if it suits your topic.)

#### Scientific Background (The “Book Knowledge”)

These are the foundational theories, definitions, and technologies that a peer needs to understand your work.

- **Focus:** Fundamental concepts, protocols, mathematics, hardware specs, and established algorithms.
- **Source:** Textbooks, tutorials, and seminal (old but gold) papers.
- **Checklist:** *“If I mention a term that isn't common knowledge, is it defined here?”*

#### Related Work (The “State of the Art”)

This is the neighborhood you are moving into. It includes not only those working on your *exact* problem, but also those solving **analogous problems** in different domains.

**The Four Pillars of Related Work:**

- **Different Method, Same Problem:** Work tackling your exact problem with a different technical approach.
- **Same Method, Different Problem:** Work using your proposed technology applied to a different domain.
- **Similar Method, Similar Problem:** Your “closest neighbors” from which you must distinguish your niche.
- **Problem Domain Discussion:** Broad papers covering the general domain and boundaries of your research.

**Advanced Strategies:**

- **Focus:** Papers from the last 2-5 years.
- **Think Laterally:** Sometimes the best solution for your problem comes from a different field.
    - *Example:* If you are analyzing GPS trajectories, you might look at bioinformatics algorithms for DNA string comparison. By converting GPS coordinates into a sequence of symbols (chars), you can use established “string matching” techniques to find patterns in movement.
- **The Synthesis Matrix:** Don't write a list of summaries (“Author A did X. Author B did Y.”). Create a table comparing existing works based on features, performance, or limitations.
- **Transposing the Matrix (The Pro Move):** Use the *columns* (properties/features) of your matrix as your subheadings, not the rows (authors).
    - *Why?* Writing about “Scalability” or “Accuracy” across all papers is much more insightful than writing three separate paragraphs about three different papers. It forces you to compare them directly and makes the “Gap” in the literature obvious.
- **Gap Analysis:** This is the most critical section. You must conclude this chapter by explaining why the existing works (including the analogous ones) are insufficient for your specific problem.

#### Related Technologies (The “Building Blocks”)

While Background covers *theory*, Related Technologies covers the *tools* you will actually use to achieve your objectives.

- **Focus:** Specific frameworks (e.g., TensorFlow, React), APIs, hardware platforms, or protocols mentioned in your objectives.
- **The “Why” Factor:** Don't just list them. Justify why you chose [Tech A] over [Tech B]. (e.g., “While Docker is common, we use Podman because of its rootless architecture, which is critical for our security objective [O2]”).
- **Integration:** This section should link the problems identified in the *Related Work* to the specific tools you'll use to solve them in your *Methodology*.

#### Critical & Assertive Evaluation (The “Verdict”)

This chapter is not just a summary; it is an **argument**. You must be critical and assertive regarding the state of the art and the available technologies.

- **Identify Limitations:** Be explicit about what existing works fail to do. This “critical gap” is the justification for your own research.
- **Identify Reusable Assets:** Not everything in previous work is “bad.” Identify good aspects, specific algorithms, or architectural patterns that are solid and can be reused in your solution.
- **Organizational Strategy:** You can choose the style that best fits your narrative:
    - **In-Section Analysis:** Provide a critical summary and “reusability verdict” immediately after discussing each major work or technology.
    - **Chapter Synthesis:** Dedicate a final section at the end of the chapter to provide a consolidated, comparative analysis of all the “neighbors” and “gear” you've discussed.

### Chapter 3: Work Plan & Methodology (The Blueprint)

This is where you prove you are an engineer/scientist, not just a dreamer.

**The Opening Statement:** Start this chapter with a very brief (one paragraph) presentation of the specific problem you are addressing and the core insight behind your proposed solution. This “refresher” ensures the reader has the key context before diving into the technical details.

#### Proposed Solution (The “What”)

- **Architecture:** Use a clean, vector-based diagram (use TikZ or draw.io exported as PDF; see *Visuals & Layout* in Section 9).
- **Work Environment:** Detail the software stacks, hardware constraints, or laboratory settings you will rely on.

#### Validation Strategy (The “How”)

- **Metrics/KPIs:** Define exactly how you will measure success. Broaden your evaluation beyond simple accuracy depending on your field:
    - **Systems:** Throughput, latency, fault tolerance, energy consumption.
    - **Security:** False positives/negatives, detection rate, attack surface.
    - **HCI:** Usability metrics, task completion time, user satisfaction.
    - **Theory:** Time/Space complexity bounds, proofs of correctness.
- **Comparison & Baselines:** You must compare your solution against known standards to prove its value.
    - **Naïve Baseline:** A standard, simple, or “vanilla” implementation.
    - **SOTA (State of the Art):** The best-performing method identified in your Related Work.
    - **Ablation Study:** Your system with specific features disabled to measure the individual impact of your contributions.

#### Reproducibility Plan (Scientific Rigor)

Ensuring others can replicate your results is key to scientific credibility.

- **Artifacts:** Define how you will package your work (e.g., Docker containers, `requirements.txt` or `environment.yml` files, and the use of deterministic seeds).
- **Experiment Tracking:** Describe how you will log configurations (e.g., via YAML/JSON files) and record results to ensure every run is traceable.

#### Temporal Planning (The “When”)

- **Defining Task Scope:** Each task should have a clear **boundary** and a specific **deliverable** (e.g., a software module, a dataset, or a draft chapter). A well-scoped task is small enough to be manageable (2-4 weeks) but large enough to represent significant progress.
    - *Rule of Thumb:* If you can't describe the “Done” state in one sentence, the task is too broad.
- **How to Define Tasks:** Use a top-down approach. Start with major milestones (e.g., “Prototype Complete”) and break them into technical sub-tasks (e.g., “Database Schema Design,” “API Implementation”). Ensure each task is **actionable** and **measurable**.
- **Managing Task Overlap:** Parallelism is often necessary (e.g., writing the background while waiting for data collection).
    - **Loose Coupling:** Ensure overlapping tasks don't block each other.
    - **Resource Allocation:** Be realistic about your cognitive load; don't plan three high-intensity coding tasks for the same week.
    - **Buffer for Context Switching:** Overlapping tasks require “mental rebooting.” Add extra time to your estimates when switching between radically different domains (e.g., hardware setup vs. literature review).
- **Interdependencies:** Use a Gantt Chart (`pgfgantt`) to visualize the critical path. Clearly identify which tasks are **blocking** (Task B cannot start until Task A ends) and which are **concurrent**.
- **Reality Check:**
    - *Month 1-2:* Environment Setup, Prototyping, and Initial Implementation.
    - *Month 3-5:* Core Development, Experimentation, and Data Collection.
    - *Month 6:* Final Analysis, Evaluation, and Thesis Writing.
- **The “Oh No!” Buffer:** Always add a 20% margin to your timeline for unexpected bugs, hardware failures, or advisor feedback cycles.

#### Risk Assessment & Contingency Planning (Plan B)

Identify key technical, data, or experimental risks early and define realistic mitigation strategies:
- **Data Risk:** What if the required dataset is unavailable, incomplete, or restricted? Identify fallback datasets or synthetic data generation techniques.
- **Dependency & Tooling Risk:** What if key third-party libraries or open-source implementations are unmaintained or broken? Plan for alternative tools or baseline implementations.
- **Hardware & Resource Constraints:** What if required GPU time, server access, or hardware components are delayed? Outline low-scale local testing methods as a fallback.
- **Performance Risk:** What if the proposed insight does not outperform the baseline as expected? Define intermediate evaluation milestones so negative results lead to timely iteration rather than a blocked thesis.

---

## 6. Working with the Literature

Reading effectively is as important as writing. Not all papers are created equal.

### Finding Papers: Beyond Keywords

1.  **[Google Scholar](https://scholar.google.com):** The essential starting point for broad searches.
2.  **[ResearchRabbit](https://www.researchrabbit.ai):** Best for “Discovery.” It maps the citation graph of your starting papers.
3.  **[Connected Papers](https://www.connectedpapers.com):** Visualizes the “neighborhood” of a single seminal paper.
4.  **[Semantic Scholar](https://www.semanticscholar.org):** Uses AI to tell you which citations actually *influenced* the work vs. just mentioning it.

**The Snowballing Strategy:**

- **Backward Snowballing:** Use the references within a paper to find **older** related work.
- **Forward Snowballing:** Use the “Cited by” link in Google Scholar to find **newer** related work that has built upon that paper since its publication.

### Filtering for Quality: Is the Paper Worth Reading?

Use heuristics to decide within minutes if a paper deserves a deep dive or should be discarded. Evaluate the **venue** first, using established “observatories”:

- **[CORE Rankings](https://portal.core.edu.au/conf-ranks/):** The primary ranking for Computer Science conferences. Aim for A* or A; B is acceptable; C requires scrutiny.
- **[SJR (Scimago Journal Rank)](https://www.scimagojr.com/):** A measure of scientific influence of scholarly journals. Look for Q1 (top 25%) or Q2.
- **[Google Scholar Metrics (H5-Index)](https://scholar.google.com/citations?view_op=top_venues):** Shows the impact of a venue over the last 5 years, across various categories.
- **Citation Count:** A 3-4 year old paper with 100+ citations is a “must-read.” (Check via Google Scholar.)

Also learn **speed reading** techniques for scientific papers (e.g., first pass: title, abstract, intro, section headings, conclusions) to handle large quantities of information.

### Organizing the Chaos

- **Categorization:** Use your literature review to put order into the chaos by categorizing papers, making it beneficial for your readers.
- **AI Synthesis:** Tools like **[NotebookLM](https://notebooklm.google.com)** can help you *compare and synthesize* your curated PDFs. Upload your “must-read” papers and ask, e.g., “_What are the common limitations mentioned across these 5 papers?_” Use the output to inform your own analysis; do **not** paste generated text as your Related Work section (see below and the AI Disclosure Statement in Section 1).

### Using AI/LLMs with Integrity

Use LLMs as a **Rubber Duck** or **Tutor**, never as a ghostwriter (see Section 8 for the full do/don't list).

- **Hallucination Check:** **Never** trust an LLM's citation list. They often invent titles that sound real. Always find the DOI yourself.
- **Prompting for Integrity:**
    - *Bad:* “Write the introduction for my thesis on AI.”
    - *Good:* “I have these three objectives for my thesis. Can you help me find logical inconsistencies or gaps in my reasoning?”

---

## 7. Citation Mechanics & Ethics

In technical writing, citations are the “currency” of credibility. Misplacing them can lead to ambiguity or, worse, accusations of plagiarism.

### Where to Place the Citation?

The placement of a citation changes its meaning. Follow these rules:

1.  **Near the Subject (Specific Attribution):** Use this when you are attributing a specific idea, algorithm, or result to a specific author.
    - *Example:* “The Fast-Flux algorithm, proposed by Smith et al. [14], improves latency by...”
2.  **End of the Sentence (General Support):** Use this when the entire sentence is supported by a source.
    - *Example:* “Recent studies show that edge computing reduces jitter in autonomous systems [22].”
3.  **End of the Paragraph (Block Support):** **Avoid this.** Placing a single citation at the end of a paragraph is ambiguous. Does it support the last sentence or the whole paragraph?
    - *Pro-Tip:* Cite as early as possible in the paragraph to establish the source of the logic.

(For the LaTeX mechanics of citing, see *Workflow Hacks* in Section 10.)

### A Well-Formatted Bibliography Matters

Your bibliography is the first thing an expert reader inspects, and a messy one signals carelessness. Aim for **clean, consistent, and complete** BibTeX entries.

- **Start from quality sources.** Prefer publisher metadata over the “messy” BibTeX from Google Scholar. Use [DOI2BIB](https://www.doi2bib.org) for a clean entry from a DOI, [AnyStyle](https://anystyle.io) to turn a plain-text reference list into structured BibTeX, or a reference manager like [Zotero](https://www.zotero.org) with [Better BibTeX](https://retorque.re/zotero-better-bibtex/).
- **Clean your `.bib` file.** Over time your file accumulates duplicates, inconsistent fields, and broken capitalization. Tidy it with an online tool like [BibTeX Tidy](https://flamingtempura.github.io/bibtex-tidy/), or locally with [betterbib](https://github.com/nschloe/betterbib) or [bibtool](https://ctan.org/pkg/bibtool).
- **Be consistent.** Use the same key style, keep author names in full, and protect capitals in titles with braces (e.g., `title = {A Study of {TCP} Congestion}`) so your bibliography style does not lowercase acronyms.
- **Verify, always.** Whatever generated the entry (a tool or an LLM), check the authors, year, venue, and DOI against the real publication before trusting it.

(See Section 11 for the full list of bibliography tools.)

### Ethics & Giving Credit

- **The “Common Knowledge” Test:** You don't need to cite that “the sky is blue” or “Python is a programming language.” You **must** cite everything else: data, unique diagrams, specific metrics, and controversial claims.
- **Paraphrasing ≠ Originality:** Even if you rewrite a paragraph in your own words, the *idea* still belongs to the original author. Cite it. The same applies to schemes and figures.
- **Self-Plagiarism:** If you published a paper in a conference during your BSc, you must still cite yourself when including that work in your thesis.
- **The “Shadow” Citation:** If Paper A cites Paper B for a specific fact, you should ideally read and cite Paper B (the primary source) rather than just relying on Paper A's interpretation.
- **Citing Code & Libraries:** If you use a specific GitHub repository or a specialized library (e.g., a custom CUDA kernel), cite it. If there is no paper, cite the URL and the version/commit hash used.
- **Honest Acknowledgement (final thesis):** The MSc Plan usually has no Acknowledgements section, but the final thesis does. There, acknowledge institutional support (the School and the Department), academic support (teachers and advisors), and technical support (a colleague or an AI tool that helped significantly with a specific proof or debugging session). It is also good practice to acknowledge the author of the **NOVAthesis** template.

---

## 8. Ethical Use of AI Tools

AI tools (LLMs like ChatGPT or Claude, coding assistants like GitHub Copilot, research aids like NotebookLM) are now part of the academic toolbox. Used well, they make you faster; used badly, they undermine the very thing a thesis is meant to prove: that *you* did the work and understand it. The guiding principle is simple: **AI is your assistant, not your author.** You remain fully responsible for every word, result, and citation in your document.

Remember that whatever you use and however you used it must be declared in your **AI Disclosure Statement** (see Section 1). Moderation is part of integrity: if AI wrote it, you did not, and you cannot honestly claim it as your contribution.

### What You Can Do (AI as Assistant)

- **Brainstorm and challenge ideas:** Ask it to find logical gaps in your reasoning, list counter-arguments, or suggest alternative approaches. Use it as a *rubber duck* and a *tutor*.
- **Understand hard material:** Ask it to explain a difficult paper, concept, or error message in simpler terms (then verify against the primary source).
- **Improve your own text:** Paste text *you wrote* and ask for feedback on clarity, grammar, or structure. This is especially useful when English is not your first language.
- **Assist with mechanics:** Convert a raw reference into a BibTeX entry, draft boilerplate code, or generate a first LaTeX table or TikZ sketch, always reviewing and correcting the output yourself.
- **Summarize and compare *your* sources:** Upload papers *you have curated* and ask for a comparative synthesis to inform (not replace) your own analysis.

### What You Should Not Do (AI as Author)

- **Do not let AI write your content:** Never paste generated paragraphs as your Introduction, Related Work, or analysis. The ideas and their expression must be yours.
- **Do not trust AI facts or citations:** LLMs *hallucinate*, confidently inventing plausible-sounding references, results, and quotes. **Always** verify every fact and locate every DOI yourself.
- **Do not outsource your thinking:** If you cannot explain, defend, or reproduce something in your thesis, it should not be there. The committee will ask, and “the AI wrote it” is not an answer.
- **Do not upload confidential or unpublished work carelessly:** Check where your data goes and whether it may be used for training, especially with third-party tools (see the caution in Section 11).
- **Do not hide your usage:** Undisclosed or misrepresented AI use is an integrity violation and can seriously affect your evaluation.

> **The Litmus Test:** If a tool helps *you* think, learn, or polish, it is probably fine. If it thinks *for you* or produces content you then claim as your own, it is not. When in doubt, ask your advisor and disclose it.

---

## 9. Technical Writing & Typography

An engineering thesis is a technical manual, not a novel. Clarity and precision are your primary goals. Use these rules to ensure your text is professional and readable.

### The Writing Style

- **Short & Punchy Sentences:** Avoid long, winding sentences with multiple sub-clauses. If a sentence is longer than three lines, break it in two.
- **Prefer the Active Voice:** The active voice clarifies responsibility: “We implemented the algorithm” instead of “The algorithm was implemented.” Agree with your advisor on the person to use (“I” vs. “we”); “we” is the most common choice, and the passive voice is still acceptable where the actor is irrelevant (e.g., in method descriptions).
- **Repeat the Subject:** Avoid using “it,” “this,” or “that” to start a sentence unless the reference is 100% clear. It is better to repeat the noun (“The algorithm improves...”) than to leave the subject implicit.
- **No “Fluff”:** Delete words like “very,” “extremely,” or “basically.” If a result is significant, the data will show it.
- **Precision & Quantifiability:** Avoid vague adjectives like “fast,” “efficient,” or “better.” If a result is good, quantify it. Use benchmarks or specific metrics (e.g., “The system maintains a latency below 50 ms under peak load”).
- **Parallel Structure:** When listing items or comparing ideas, use the same grammatical pattern. This improves scannability and logical flow (e.g., “The module handles data ingestion, metric calculation, and report generation”).
- **One Idea, One Paragraph:** Start every paragraph with a **topic sentence** that captures its main point. If you transition to a new concept, start a new paragraph. This prevents dense “walls of text.”
- **The “Present Tense” Convention:** Use the present tense to describe your proposed architecture, algorithms, and established scientific facts. Use the past tense only for actions already completed (e.g., “We conducted the survey in 2023”).
- **Spell & Grammar Check:** Run every chapter through a checker (e.g., [LanguageTool](https://languagetool.org), or the checkers built into Overleaf and VS Code). Sloppy typos undermine the committee's trust in your technical rigor.

### Visuals & Layout

- **Vectors over Rasters:** Always use **PDF** when exporting your diagrams and plots. These are vector formats that stay sharp at any zoom level. Only use PNG/JPG for actual photographs. Both EPS and SVG are also excellent source vector formats that can be converted to PDF for inclusion in your LaTeX document.
- **Screenshots & Themes:** If you must include screenshots of software or code, **do not** use dark mode. Always use a light theme when taking the screenshot for better readability and professional appearance on paper/standard PDF viewers.
- **Floating Objects (Figures & Tables):** In LaTeX, figures and tables are “floats.” They don't have to stay exactly where you write the code. They should be at the top or bottom of the page near where they are first mentioned.
    - *Rule:* Never say “the figure below.” Always use a reference: “As shown in Figure~\ref{fig:arch}...”
- **Know Your Caption Style:** The expected detail in captions varies by field.
    - **Concise Style (e.g., Computer Science/Engineering):** Captions are brief identifiers (e.g., “Figure 4.1: System Architecture overview”). Detailed technical analysis belongs in the main text.
    - **Self-Contained Style (e.g., Life Sciences):** Captions are detailed enough that the reader can understand the figure or table without reading the main text.
    - *Rule:* Consult your advisor or field-specific standards to determine which convention is expected for your thesis.
- **Consistent Units:** Always use a non-breaking space between a number and its unit (e.g., 10\~ms, 50\~GB). Even better, use the `siunitx` package for perfect formatting.

### Typographic Precision

- **Italics for Emphasis:** Use italics sparingly for new terms. Never use **bold** or ALL CAPS for emphasis within a paragraph.
    - *LaTeX Pro-Tip:* Use `\emph{...}` rather than `\textit{...}`. The `\emph` command is context-aware and will correctly handle nested emphasis (e.g., italics within an already italicized block).
- **Quotes:** Always use typographic “curly” quotes. In LaTeX, use two backticks for open (``) and two single quotes for close (''), or better, use `\enquote{...}` from the `csquotes` package (see Section 10), which also adapts to the document language.
- **Dashes:** Use an en-dash (`--`) for ranges (e.g., 10--20 pages) and an em-dash (`---`) for parenthetical thoughts.

---

## 10. LaTeX & the NOVAthesis Template

### Getting the Template

Use the **NOVAthesis** template, available on **[Overleaf](https://www.overleaf.com/latex/templates/novathesis-template/mpxfgrvskvwy)** or **[GitHub](https://github.com/joaomlourenco/novathesis)**. It's the easiest way to ensure your formatting meets university standards.

- **Documentation & Help:** Check the template's [Wiki](https://github.com/joaomlourenco/novathesis/wiki) first. For problems and questions, use the [GitHub issues](https://github.com/joaomlourenco/novathesis/issues) and [discussions](https://github.com/joaomlourenco/novathesis/discussions) pages.

### Local Installation (Recommended for Large Documents)

Overleaf is great for starting out, but the free plan has a **compile timeout** that a full thesis (many figures, glossaries, bibliography) can easily exceed. A local installation has no timeouts, works offline, and pairs naturally with Git. Install a **TeX distribution**:

- **[TeX Live](https://www.tug.org/texlive/)** (Linux, Windows, macOS): The reference distribution. Prefer the **full** installation so all packages are available offline; update packages with `tlmgr`.
- **[MacTeX](https://www.tug.org/mactex/)** (macOS): TeX Live packaged for the Mac, bundled with useful GUI tools.
- **[MiKTeX](https://miktex.org)** (Windows, also Linux/macOS): A lighter alternative that installs missing packages on the fly.

Then pick an **editor**:

- **[VS Code](https://code.visualstudio.com) + [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop):** The power-user setup, with Git integration.
- **[TeXstudio](https://www.texstudio.org):** A classic, batteries-included LaTeX IDE.

And build with **`latexmk`**, which automatically runs LaTeX and the bibliography tool the right number of times. Make sure your editor and `latexmk` are configured for the same engine and bibliography backend the template is configured to use (check the template documentation for the supported engines and for `biber` vs. `bibtex`).

Finally, keep your sources under **version control** (Git/GitHub): it is your backup, your history, and your safety net the night before the deadline.

### Essential Packages Already Included in NOVAthesis

- [`microtype`](https://www.ctan.org/pkg/microtype): A “magic” package that slightly adjusts character spacing to eliminate awkward gaps in justified text and reduces the number of hyphens at the end of lines.
- [`glossaries-extra`](https://www.ctan.org/pkg/glossaries-extra): Managing acronyms manually is a recipe for error. Use this to define terms once and have LaTeX handle the “First mention (Full Name)” vs. “Subsequent mention (Acronym)” logic automatically.
- [`graphicx`](https://www.ctan.org/pkg/graphicx): The standard for including images. Always use `\includegraphics[width=FACTOR\textwidth]{...}` (e.g., `\includegraphics[width=0.75\textwidth]{...}`) to ensure your figures scale properly with your margins.
- [`fontenc [T1]`](https://www.ctan.org/pkg/fontenc): With pdfLaTeX, `\usepackage[T1]{fontenc}` ensures proper hyphenation of accented words and correct copy-paste from the final PDF. (Not needed with the Unicode-based XeLaTeX/LuaLaTeX engines.)
- [`hyperref`](https://www.ctan.org/pkg/hyperref): Transforms your citations, references, and URLs into clickable links. It also automatically generates a PDF outline (bookmarks), making your document much easier to navigate on digital screens.
- [`PGF/TikZ`](https://www.ctan.org/pkg/pgf): A powerful tool for creating complex, high-quality vector graphics directly within LaTeX. It ensures that your diagrams use the same fonts and mathematical symbols as your main text for a perfectly integrated look. For the bravest students: “coding” your diagrams pays off in consistency.

### Other Very Useful Packages

- [`booktabs`](https://www.ctan.org/pkg/booktabs): Forget the standard horizontal and vertical lines. Use `\toprule`, `\midrule`, and `\bottomrule` to create clean, professional tables that look like they belong in a high-end journal.
- [`cleveref`](https://www.ctan.org/pkg/cleveref): Tired of typing `Figure~\ref{...}`? This package automates it. Just use `\cref{label}`, and it will automatically detect if it's a Figure, Table, or Equation and format the text accordingly. (Load it **after** `hyperref`.)
- [`enumitem`](https://ctan.org/pkg/enumitem): Gives you total control over lists (`itemize`, `enumerate`). Use it to reduce vertical spacing between items or to change numbering styles (e.g., a), b), c)).
- [`siunitx`](https://www.ctan.org/pkg/siunitx): The absolute gold standard for units. Use `\qty{10}{\milli\second}` for quantities and `\unit{\milli\second}` for standalone units, ensuring the spacing and font are always correct.
- [`csquotes`](https://www.ctan.org/pkg/csquotes): Provides advanced facilities for inline and block quotations (`\enquote{...}`). It automatically handles nested quotes and ensures that punctuation is placed correctly according to your document's language settings.
- [`todonotes`](https://www.ctan.org/pkg/todonotes): A lifesaver during the drafting phase. It allows you to place ‘To-Do’ notes in the margins or as a list at the beginning of the document, ensuring you never forget to address a pending task or a comment from your advisor.
- [`algorithmicx`](https://www.ctan.org/pkg/algorithmicx): Provides a flexible environment for typesetting algorithms in a clear, structured way. It supports nested loops, conditionals, and can be customized to match the pseudocode style of your specific research community.
- [`amsmath`, `amssymb`](https://www.ctan.org/pkg/amsmath): The industry standard for mathematical typesetting. They provide advanced environments for multi-line equations, custom operators, and a vast library of mathematical symbols.
- [`amsthm`](https://www.ctan.org/pkg/amsthm): Offers a structured way to typeset theorems, definitions, lemmas, and proofs. It allows you to easily switch between different styles while maintaining consistent numbering.
- [`listings`](https://www.ctan.org/pkg/listings): A robust package for including source code. It supports syntax highlighting, line numbering, and can import code directly from external files.
- [`minted`](https://www.ctan.org/pkg/minted): An alternative to `listings` that uses the Python-based Pygments library for superior syntax highlighting. Note that it requires compiling with `-shell-escape` and a working Python/Pygments installation (Overleaf handles this automatically).
- [`xurl`](https://www.ctan.org/pkg/xurl): A simple but essential package that allows URLs to break at any character, preventing long web addresses from overflowing into the margins.
- [`widows-and-orphans`](https://www.ctan.org/pkg/widows-and-orphans): Helps you maintain high typographic standards by identifying ‘widows’ (a single line at the top of a page) and ‘orphans’ (a single line at the bottom) and providing warnings.

### Workflow Hacks

- **Comment your logic:** Use `%` to leave notes for yourself or your advisor in the source code.
- **Labels with Prefixes:** Stay organized with a consistent labeling system: `fig:architecture`, `tab:results`, `eq:objective`, `lst:algorithm`.
- **The “Non-breaking Space” (`~`):** Always place a tilde before a `\cite` or `\ref`, and before numbers in general, to prevent them from jumping to a new line alone: `...logic~\cite{key}`, “In~1974 there was a revolution in Portugal.” (No space after the tilde!)
- **Citing Authors in Text:** Use `\citeauthor{key}` to properly typeset the authors' names in your text, and place `\cite{...}` immediately after the word or phrase it supports (see *Where to Place the Citation?* in Section 7).

---

## 11. The MSc Toolbox

### Online Editors

- **[Overleaf](https://www.overleaf.com):** The standard for collaboration and ease of use. (Mind the free-plan compile timeout on large documents; see *Local Installation* in Section 10.)
- **[OpenAI Prism](https://prism.openai.com):** A modern alternative for AI-assisted collaborative editing.
- **[Octree](https://www.useoctree.com) / [Bibby AI](https://trybibby.com):** AI-native LaTeX editors that offer project-wide awareness and formatting assistance.
- **[WebLaTeX](https://github.com/sanjib-sen/WebLaTex):** Recommended only for advanced, “tech-safe” users who require specialized control over their environment.

> **Caution (AI editors):** Before committing to any AI-native editor, verify that it compiles the NOVAthesis template correctly, consider where your unpublished work is being uploaded, and remember that any AI assistance must be reported in your AI Disclosure Statement (Section 1).

### Bibliography Management

- **[Zotero](https://www.zotero.org):** The gold standard for managing references. Use the **[Better BibTeX](https://retorque.re/zotero-better-bibtex/)** extension for the best results with LaTeX.
- **[DOI2BIB](https://www.doi2bib.org):** A simple and effective tool to generate clean, minimal BibTeX entries from a DOI. Avoid the “messy” BibTeX often found on Google Scholar.
- **Other DOI-to-BibTeX Tools:** If DOI2BIB is unavailable, try **[ZoteroBib (zbib.org)](https://zbib.org/)** or **[BibTeX.com](https://www.bibtex.com/c/doi-to-bibtex-converter/)** for reliable metadata fetching.
- **[AnyStyle](https://anystyle.io):** Paste a plain-text reference list (one reference per line) and it parses each into structured BibTeX, ideal for references that have no DOI.
- **Cleaning `.bib` files (online):** **[BibTeX Tidy](https://flamingtempura.github.io/bibtex-tidy/)** makes spacing consistent, removes duplicates and unwanted fields, and sorts entries, all in the browser.
- **Cleaning `.bib` files (local):** **[betterbib](https://github.com/nschloe/betterbib)** cross-checks your entries against online sources and fixes faulty ones (`betterbib update in.bib`, `betterbib format`); **[bibtool](https://ctan.org/pkg/bibtool)** offers fine-grained field manipulation and de-duplication.
- **LLM Assistance:** LLMs can convert raw text references into clean BibTeX entries and search for DOIs. You **must** manually verify the quality of the generated entry and the validity of the DOI (see Section 8).

### Essential Web Utilities

- **[Detexify](https://detexify.kirelabs.org/classify.html):** LaTeX symbol classifier (handwriting recognition).
- **[Mathpix Snip](https://mathpix.com):** The gold standard for equation OCR. Convert screenshots of complex formulas (from papers or handwriting) directly into clean LaTeX code.
- **[Tables Generator](https://www.tablesgenerator.com):** Design your tables in a visual, spreadsheet-like interface and export the LaTeX code. It saves hours of manual formatting.
- **[Mathcha](https://www.mathcha.io):** A powerful visual editor for mathematics and **TikZ diagrams**. Draw your architecture diagrams visually and export them as pure TikZ code.
- **[TikZcd-editor](https://tikzcd.yichuanshen.de):** A specialized visual tool for creating commutative diagrams and category theory maps.

---

## 12. Final Submission Checklist

- [ ] **Length:** Is it under 35 pages? (Quality > Quantity).
- [ ] **AI Disclosure:** Is the mandatory AI Disclosure Statement included, accurate, and complete?
- [ ] **Visual Themes:** Are all screenshots taken in **light mode**? (Dark mode screenshots are hard to read in print).
- [ ] **Figures:** Are all diagrams vector-based (PDF/SVG)? Can you read the text on the axes of your plots?
- [ ] **The “Story”:** Does the Related Work naturally lead to the Gap, which naturally leads to your Solution?
- [ ] **Work Plan:** Does the Gantt chart show the critical path, and does the timeline include the 20% buffer?
- [ ] **References:** Is every citation in the text present in the Bibliography? (LaTeX does this automatically, but check for “??”).
- [ ] **Tone:** Is it objective? (Avoid “I think,” “I feel,” “I believe.” Use “The data suggests,” “The proposed model...”).

---

## 13. Transitioning from MSc Plan to Final Thesis

The MSc Plan is the architectural blueprint, but the final MSc Thesis is the completed building. When moving from Phase 1 (Plan) to Phase 2 (Thesis), apply these essential revision rules:

- **Chapter 1 (Introduction):** Must be carefully revised to eliminate all references to future intentions (e.g., replace “We will propose...”, “We plan to evaluate...” with past/present tense describing what was actually achieved).
- **Chapter 2 (Background & Related Work):** Must be revised in light of the real work developed during the thesis. Remove literature or technology sections that turned out to be irrelevant, and add new papers or tools discovered during implementation.
- **Chapter 3 (Work Plan):** Is mostly discarded as a standalone chapter in the final thesis (since temporal planning is no longer relevant after completion). However, key technical components—such as system architecture, design decisions, and evaluation methodologies—should be carefully adapted and integrated into the dedicated Architecture, Implementation, and Evaluation chapters of the final MSc Thesis.

### Appendices and Annexes (For the Final Thesis)

In the MSc Plan you are advised **not** to use appendices or annexes (see Section 1). In the final thesis they become useful, so it is worth knowing the difference:

- **An appendix** contains supporting material that **you produced** but that would break the flow of the main text: full proofs, extra result tables, detailed configuration files, questionnaire forms, or long code listings.
- **An annex** contains supporting material **produced by others** that you include for reference: a datasheet, a third-party standard, or an external report.

Use them for material that a reader *might* want to consult but does not *need* in order to follow your argument. Keep three rules in mind:

- **The main text must stand on its own.** Anything essential to your argument belongs in the body, not in an appendix. Reference each appendix/annex explicitly from the text (e.g., “the full results are listed in Appendix~B”); an appendix nobody is pointed to will not be read.
- **Do not use them as a dumping ground** to hide content that would otherwise exceed a page limit or to pad the document.
- **They come after the bibliography** and are usually labelled with letters (Appendix A, B, ...). The NOVAthesis template provides the proper environment for both.

---

## 14. Further Reading

- [Advice for writing LaTeX documents](https://github.com/dspinellis/latex-advice), by [Diomidis Spinellis](https://github.com/dspinellis)
- [How to Write a Great Research Paper](https://www.microsoft.com/en-us/research/academic-program/write-great-research-paper/), by *Simon Peyton Jones*
- [The Science of Scientific Writing](https://www.americanscientist.org/blog/the-long-view/the-science-of-scientific-writing), by *George Gopen* and *Judith Swan* @ American Scientist
- [The Not So Short Introduction to LaTeX 2ε](https://tobi.oetiker.ch/lshort/lshort.pdf), by *Tobias Oetiker*
- [TeXample.net (TikZ Gallery)](https://texample.net/tikz/examples/) and [TikZ.net](https://tikz.net): Massive collections of TikZ examples with source code
- [Friends Don't Let Friends Make Bad Graphs](https://github.com/cxli233/FriendsDontLetFriends), by [C. Li](https://github.com/cxli233)
- [Ten Simple Rules for Better Figures](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003833), by *Rougier et al.*
- [Awesome LaTeX](https://github.com/egeerardyn/awesome-LaTeX?tab=readme-ov-file#packages), by *Egon Geerardyn*

---

**Mastering the MSc Plan is about proving you have a map. Once you have the map, the journey becomes a matter of discipline. Good luck!**
