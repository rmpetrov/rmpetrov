# Roman Petrov

**Senior QA Engineer / SDET | Test Automation & AI Quality Engineering**

I bring 7+ years of software testing and quality engineering experience across manual and automated testing of web applications, REST APIs, integrations, regression coverage, and release quality. My focus is maintainable automation, reliable execution, test data management, and defect investigation.

My recent independent portfolio work extends this background through TypeScript/Playwright automation and Python-based AI/LLM evaluation. These projects demonstrate newer engineering skills developed outside my professional employment.

**Location:** Massachusetts, USA · **Work authorization:** U.S. Citizen

**Contact:** [LinkedIn](https://www.linkedin.com/in/rmpetrov/) · [rpetrovqa@gmail.com](mailto:rpetrovqa@gmail.com) · [Resume (PDF)](./Roman_Petrov_Resume.pdf)

## Featured Projects

### [Playwright TypeScript Quality Framework](https://github.com/rmpetrov/playwright-ts-quality-framework)

A comprehensive TypeScript and Playwright automation framework for a local React/Fastify Order Management Console.

- **23 API scenarios + 23 UI scenarios per browser** across Chromium, Firefox, and WebKit: **92 total Playwright executions** (23 API + 69 UI).
- Independent API contract and business-rule validation covers **all 16 order-status combinations**, with separate HTTP reads checking accepted changes and unchanged state after rejection.
- Parallel-safe namespace fixtures isolate test data and verify teardown, including after assertion failures.
- Deterministic network failure injection exercises UI recovery; independent backend state verification checks for unintended writes and confirms successful recovery.
- Selected axe-core accessibility scans complement keyboard navigation, visible focus, focus restoration, and contrast testing. These checks do not establish full WCAG compliance.
- GitHub Actions runs with **zero configured retries** and retains diagnostic reports, traces, screenshots, and cleanup evidence.

The application runs locally as a controlled test fixture.

### [AI Quality Evaluation Framework](https://github.com/rmpetrov/ai-quality-evals)

An offline-first Python framework for RAG and LLM quality evaluation, separating retrieval testing, response validation, and human semantic review.

- **24 authored evaluation scenarios**, BM25 retrieval, and deterministic offline replay.
- Local inference through Ollama using **qwen2.5:3b**, with optional OpenAI Responses API integration.
- **Six deterministic consistency checks** and SHA-256-bound human semantic review across **five scoring dimensions**.
- Versioned prompts, paired A/B evaluation, and auditable reports preserve reviewable evidence.

Human review identified evidence contradictions and unsupported personal claims that structural metrics missed.

In a small prompt A/B experiment, automatic answerability classification was **3/8 for v1** and **6/8 for v2**, across four selected questions repeated twice. Mean human answer correctness for **paired run 02** was **v1: 2.0/2; v2: 1.0/2**, over four paired applicable cases. Answerability classification does not measure factual correctness. This was a small experiment, not a statistically representative benchmark; **prompt v1 remains the default**. See the [findings and limitations](https://github.com/rmpetrov/ai-quality-evals/blob/main/docs/prompt-ab-findings.md).

## Additional QA Projects

- **[playwright-tests](https://github.com/rmpetrov/playwright-tests):** Python, Playwright, and pytest UI/API automation with page objects, CI diagnostics, and [published HTML reports](https://rmpetrov.github.io/playwright-tests/).
- **[sdet-toolbox](https://github.com/rmpetrov/sdet-toolbox):** Small, runnable QA engineering examples covering API, contract, data-quality, UI, and performance checks using local sample code and data.

## Technical Skills

These skills combine my professional QA background with independent project work. TypeScript and the AI Quality capabilities below are newer skills demonstrated in my portfolio.

- **Programming:** Python, TypeScript, JavaScript, SQL, Java.
- **Automation:** Playwright, pytest, Selenium, TestNG, API and integration testing.
- **AI Quality (portfolio):** RAG evaluation, retrieval metrics, prompt A/B experiments, human semantic review, Ollama.
- **Engineering:** Git, GitHub Actions, Jenkins, Docker, Postman, CI/CD, Allure.
- **Quality Practices:** Test strategy, regression testing, troubleshooting, test data management, accessibility testing, release readiness.

## Let's Connect

I'm open to Senior QA Engineer, SDET, Test Automation Engineer, and AI Quality Engineering opportunities. Please reach out by email or LinkedIn.
