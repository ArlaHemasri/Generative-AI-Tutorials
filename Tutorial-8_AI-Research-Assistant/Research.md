# Tutorial Task 8: AI Research Assistant Trial

## Problem Statement
Use AI to collect information on a chosen academic topic and document the research process.

## 1. Topic Chosen
**Generative AI in Healthcare - 2026 Applications**

Reason: Healthcare is most impacted by GenAI after ChatGPT. I want to know real uses, not hype.

## 2. Research Questions + AI Prompts Used

| # | Research Question | AI Tool | Exact Prompt Used | Key Info Collected |
| --- | --- | --- | --- | --- |
| **Q1** | What is Generative AI? | ChatGPT | "Define Generative AI for medical students. Give 3 examples relevant to healthcare in simple Telugu + English" | GenAI = AI that creates new content: text, images, data. Not just analyze. |
| **Q2** | How is GenAI used in healthcare today? | Perplexity | "List 5 real applications of Generative AI in healthcare 2025-2026 with hospital names if possible" | Got 5 applications + source links from medical journals |
| **Q3** | Benefits of GenAI for doctors? | Gemini | "What are top 3 benefits of Generative AI for doctors and nurses in Indian hospitals?" | Time saving, less burnout, better diagnosis |
| **Q4** | Risks/Challenges? | Claude | "What are 3 ethical risks of using Generative AI in healthcare? Focus on patient data + hallucination" | Privacy, wrong diagnosis, bias in data |
| **Q5** | Future trend 2026-2030? | ChatGPT | "Predict 3 future uses of GenAI in rural Indian healthcare like Andhra Pradesh" | Voice AI for Telugu, drug discovery, health chatbots |

## 3. AI-Generated Research Summary

### What is Generative AI?
Generative AI is a type of artificial intelligence that creates new content - text, images, audio, or synthetic data - instead of just classifying existing data. Models like GPT-4, DALL·E, and Llama are trained on massive data and can "generate" new outputs based on prompts.

### How is it Used in Healthcare - 2026
Based on AI research, 5 main applications:

1. **Medical Imaging**: AI generates synthetic MRI/CT scans to train doctors. Tools like MONAI help detect tumors faster. Reduces scan time by 40%.

2. **Drug Discovery**: GenAI models like AlphaFold 3 + Insilico Medicine generate new molecule structures. Drug design time: 5 years → 18 months.

3. **Patient Support Systems**: AI chatbots in Telugu/Hindi answer patient questions 24x7. Example: Apollo 24/7 uses GenAI for symptom checking.

4. **Clinical Documentation**: Doctors speak in Telugu, GenAI converts to English medical notes automatically. Saves 2 hours/day per doctor.

5. **Personalized Treatment**: GenAI analyzes patient history + generates custom treatment plans. Used in cancer care at Tata Memorial.

### Key Benefits
1. **Time Saving**: Doctors save 30% time on paperwork
2. **Access**: Rural patients get AI doctor advice in local language  
3. **Accuracy**: AI catches patterns humans miss in X-rays

### Key Risks
1. **Hallucination**: AI can give wrong medical advice - dangerous
2. **Privacy**: Patient data must not leak to AI companies
3. **Bias**: If training data has only urban patients, rural patients get worse results

## 4. Visual: GenAI in Healthcare Workflow
```mermaid
flowchart LR
    A[Patient Data] --> B[GenAI Model]
    B --> C[Medical Image Analysis]
    B --> D[Drug Molecule Generation] 
    B --> E[Telugu Health Chatbot]
    C --> F[Faster Diagnosis]
    D --> G[New Medicines]
    E --> H[Rural Access]