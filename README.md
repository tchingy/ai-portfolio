# AI Portfolio — HVAC to AI Career Transition

> *A credentialed HVAC engineer stress-testing AI models against real trade knowledge.*

---

## About Me

I'm an HVAC professional with a **BSc in Mechanical Engineering**, **MSc in Industrial and Production Technology**, and **EPA Section 608 Universal Certification (Types I, II & III)** — now building applied AI skills through hands-on projects.

My edge: I can look at an AI-generated HVAC report summary and immediately spot if the model dropped a critical fault code, misread a refrigerant reading, or missed a safety recommendation. That combination of field credentials and AI tooling is what SME annotation, AI QA, and prompt engineering roles are built for.

---

## Projects

### 1. HVAC Report Summariser · [Live Demo](https://huggingface.co/spaces/Tchingy/hvac-report-summariser)
`hvac_report_summariser.ipynb`

Summarises long HVAC maintenance reports into concise, accurate briefings using Facebook's BART model. Deployed as a live web app — paste any report and get an AI summary instantly.

- Achieved ~67% compression while retaining technical terms (410A refrigerant, 45uf 450v capacitor, G4 filters)
- Documented parameter engineering findings across different `max_length` values
- Identified model limitations around safety-critical prioritisation in medical settings
- **Skills:** Hugging Face Transformers, BART, tokenization, beam search, Gradio, Spaces deployment

---

### 2. HVAC Sentiment Analyser
`hvac_sentiment_analyser.ipynb`

Classifies HVAC customer feedback as positive or negative using a DistilBERT pipeline. Evaluated model performance against real trade language.

- 9/10 accuracy on domain-specific reviews
- Identified a domain mismatch — "fault" (routine HVAC term) triggered false negatives due to movie-review training data
- Proposed fix: fine-tune on HVAC-labelled data for production use
- **Skills:** Hugging Face Pipelines, sentiment classification, confidence score analysis, edge case identification

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Core scripting |
| Hugging Face Transformers | NLP model loading and inference |
| Gradio + HF Spaces | Live app deployment |
| Google Colab | Cloud notebook execution |
| PyTorch | Model backend |
| GitHub | Version control and portfolio hosting |

---

## Target Roles
AI QA Tester · Data Annotator / SME Annotator · Prompt Engineer · AI Operations Coordinator · AI Customer Success Specialist

---

*Portfolio actively growing — more projects in progress.*
