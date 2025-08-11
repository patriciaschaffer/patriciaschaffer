# Bias in AI Responses:  
## A Prompt-Based Analysis of Tone, Ideology, and Temperature in Large Language Models

*Patricia Schaffer, June 2025*

---

## Overview

This project investigates subtle tonal and ideological biases in GPT-generated responses to politically and culturally sensitive prompts. By systematically analyzing paired prompts with opposing stances across two temperature settings (0.7 and 1.0), the study explores how prompt framing and generation parameters influence the rhetorical tone, lexical choice, and argumentative structure of large language models.

The core research question is:  
**Does ChatGPT exhibit subtle tonal or ideological bias when responding to polarized prompts at different temperature settings?**

---

## Project Structure

---

## Usage

- Raw prompt/response pairs can be found in the `data/raw/` folder.  
- Detailed linguistic and sentiment analyses are available in `matrices.md` and `analysis.md`.  
- The final report (`final_report.md`) synthesizes quantitative data and qualitative insights.  
- To reproduce or extend the analysis, follow the methods described in `methodology.md`.

---

## Key Findings

- **Temperature Effects:** Lower temperature (0.7) prompts more cautious, hedged language; higher temperature (1.0) generates more confident and rhetorically focused responses.  
- **Bias Patterns:** “Pro” stances tend to be framed warmly and affirmatively, while “critical” stances often hedge more and concede to opposing views, indicating subtle model bias toward inclusive, collectivist values.  
- **Prompt Framing:** The wording of prompts, especially modal verbs like “might,” significantly affects neutrality and response tone.  
- **Lexical and Structural Markers:** Pronoun choice, vocabulary, and argument sequencing vary systematically by stance and temperature.  
- **Methodological Notes:** Prompt design and session setup (including VPN use) critically impact response quality and consistency.

---

## Ethical Considerations

Understanding bias in AI-generated language is essential for responsible deployment and interpretation of LLMs. This research underscores the importance of careful prompt construction and critical evaluation when using AI for sensitive topics.

---

## Future Directions

- Expanding to multiple LLMs for cross-model bias comparison.  
- Incorporating more diverse cultural and ideological perspectives.  
- Exploring interactive user influence on response tone.  
- Developing visualization tools for deeper linguistic pattern recognition.

---

*Thank you for exploring this analysis of AI-generated discourse. Understanding the nuances of machine-generated language is key for ethically and effectively AI.*

