# 🤖 AI Portfolio — HVAC to AI Career Transition

**Built by a working HVAC technician learning to apply AI in the trades.**

This portfolio documents my hands-on journey transitioning from HVAC field work into AI-adjacent roles — including AI QA Testing, Data Annotation, and Prompt Engineering. Each project uses real HVAC domain knowledge as the test environment, which means I'm not just learning AI tools — I'm stress-testing them against a field I've worked in professionally.

---

## 👤 About Me

I'm an HVAC professional with a **BSc in Mechanical Engineering**, an **MSc in Industrial and Production Technology**, and **EPA Section 608 Universal Certification (Types I, II & III)**. I have hands-on experience in residential and commercial HVAC systems, backed by both field credentials and an engineering academic foundation.

I'm currently building applied AI skills with a focus on:

- **AI QA Testing** — evaluating model outputs for accuracy, edge cases, and failure modes
- **Data Annotation / Subject Matter Expert Annotation** — applying domain knowledge to label and validate AI training data
- **Prompt Engineering** — designing inputs that get reliable, useful outputs from language models

My combination of engineering education, EPA certification, and field experience is a direct asset when evaluating AI tools against real-world technical scenarios — I can identify errors that a general user would miss.

---

## 📁 Projects

### 1. [`hvac_report_summariser.ipynb`](./hvac_report_summariser.ipynb)
**Task:** Summarise long HVAC service reports into short, accurate summaries using a pre-trained NLP model.

- **Model:** `facebook/bart-large-cnn` (via Hugging Face Transformers)
- **Approach:** Loads the BART model locally, tokenizes HVAC report text, and generates a condensed summary using beam search decoding
- **Domain value:** Tested against realistic HVAC field report language — refrigerant readings, fault codes, equipment descriptions — to evaluate whether the model preserves technically important details or drops them
- **Skills demonstrated:** Hugging Face Transformers, tokenization, text generation, domain-specific model evaluation

---

### 2. [`hvac_sentiment_analyser.ipynb`](./hvac_sentiment_analyser.ipynb)
**Task:** Classify the sentiment of HVAC customer feedback and service notes as positive, negative, or neutral.

- **Model:** Hugging Face sentiment analysis pipeline (transformer-based)
- **Approach:** Passes HVAC-specific text samples through a pre-trained sentiment classifier and evaluates the output labels and confidence scores
- **Domain value:** Assesses how well a general-purpose sentiment model handles technical and trade-specific language — identifying cases where industry phrasing confuses the model
- **Skills demonstrated:** Hugging Face Pipelines, sentiment classification, output evaluation, edge case identification

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Core scripting language |
| Jupyter Notebook | Interactive development environment |
| Hugging Face Transformers | Pre-trained NLP model loading and inference |
| Google Colab | Cloud-based notebook execution |
| PyTorch | Model backend |
| GitHub | Version control and portfolio hosting |

---

## 🎯 Target Roles

- AI QA Tester
- Data Annotator / Subject Matter Expert Annotator
- Prompt Engineer
- AI Tools Evaluator (Industrial / Building Systems domain)

---

## 📌 What Makes This Portfolio Different

Most AI portfolios are built by developers testing models on generic datasets. Mine is built by a **credentialed domain expert** — someone with an engineering degree, a master's in industrial technology, and EPA Universal Certification — who can look at an AI summary of an HVAC report and immediately spot if the model got the fault diagnosis wrong, misrepresented a refrigerant reading, or dropped a critical safety note. That combination of formal engineering training, trade certification, and AI tooling is exactly what's needed in SME annotation and AI QA roles.

---

## 🔗 Contact

Open to opportunities in AI QA, annotation, and prompt engineering — especially in industrial, building systems, or trades-adjacent applications.

> *This portfolio is actively growing. More projects coming as my AI learning roadmap progresses.*
